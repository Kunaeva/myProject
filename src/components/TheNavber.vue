<template>
    <div class="navbar" v-if="visible">
        <h3>Gmail</h3>
        <ul class="navbar-menu">
            <li><a href="#">Главная</a></li>
            <li>
                <a href="#">Почта</a>
            </li>
            <li>
                <a href="#">Выйти</a>
            </li>
        </ul>
    </div>
</template>

<script>
export default {
    props:{
        visible:{
            type: Boolean,
            default: false
        }
    }
}
</script>