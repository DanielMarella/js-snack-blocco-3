<template>
    <div>
        <ul>
            <li>
                {{ navElement.text }}

            </li>
        </ul>



    </div>
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