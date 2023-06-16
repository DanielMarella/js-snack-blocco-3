<template>

        <ul>
            <li>
                {{ navElement.text }}

            </li>
        </ul>




</template>
<script>
export default {

    name : 'NavLink',

    props : [

        'navElement'
    ]
}
</script>
<style lang="scss">

</style>