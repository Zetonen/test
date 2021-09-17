<template>
    <header class="navbar " role="navigation" aria-label="main navigation">
        <div class="navbar-brand">
            <a class="navbar-item" href="/">
                <strong class="btn-header-nav-main_black">Home</strong>
            </a>

            <a class="navbar-item" href="/">
                <strong class="btn-header-nav_main">About me</strong>
            </a>

            <a class="navbar-item" href="/">
                <strong class="btn-header-nav_main">Skills</strong>
            </a>

            <a class="navbar-item" href="/">
                <strong class="btn-header-nav_main">Portfolio</strong>
            </a>

            <a class="navbar-item" href="/">
                <strong class="btn-header-nav_main">Contacts</strong>
            </a>

        </div>

        <hr>
    </header>
</template>

<script>
    export default {
        name: "Nav_main"
    }
</script>

<style >
    hr{
        size: 1px;
        width: 940.6px;
    }
    .btn-header-nav_main{
        font-family: Gilroy-Bold;
        font-size: 18px;
        line-height: 22px;
        color: #828282;

    }

    .navbar-brand{
        display: flex;
        justify-content: space-around;
        padding: 23px;
    }
    .btn-header-nav-main_black{
        color: #070707;
    }
</style>
