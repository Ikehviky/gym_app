<template>
    <div>
        <p>This is Dashboard, welcome {{lname}} {{fname}}</p>
    </div>
</template>

<script>
    export default {
        props: ['fname', 'lname']
    }
</script>