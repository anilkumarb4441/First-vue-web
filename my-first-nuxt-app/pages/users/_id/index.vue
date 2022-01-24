<template>
    <h2> A single Users ID : {{$route.params.id}} </h2>
</template>

<script>
export default {
    validate(data) {
        // console.log(data)
        // return data.params.id == 1;              // this in invalid
        return /^\d+$/.test(data.params.id);
    },
    layout: 'users',
};

</script>