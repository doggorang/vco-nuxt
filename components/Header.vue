<script>
const isActive = ref(false)

const isHome= window.location.pathname == '/' ? ref(true) : ref(false),
        isAbout= window.location.pathname == '/about' ? ref(true) : ref(false),
        isProduct= window.location.pathname == '/product' ? ref(true) : ref(false),
        isContact= window.location.pathname == '/contact' ? ref(true) : ref(false);
</script>

<template>
    <header class="page-head slider-menu-position">
        <nav class="navbar navbar-expand-lg navbar-dark" style="background-color: #110a06;">
        <a class="navbar-brand" href="/">
            <img src="@/assets/images/logo/logo-header.png" width="70" height="55" alt="">
        </a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav mr-auto">
                <li class="nav-item" :class="{ active: isActive }">
                    <NuxtLink to="/">Home</NuxtLink>
                </li>

                <!-- <li class="nav-item" :class="{ 'active': home == 1 }">
                    <a class="nav-link" href="/">Home</a>
                </li>
                <li class="nav-item" :class="{ 'active': about == 1 }">
                    <a class="nav-link" href="/about">About</a>
                </li>
                <li class="nav-item" :class="{ 'active': product == 1 }">
                    <a class="nav-link" href="/product">Product</a>
                </li>
                <li class="nav-item" :class="{ 'active': contact == 1 }">
                    <a class="nav-link" href="/contact">Contact</a>
                </li> -->
            </ul>
        </div>
        </nav>
    </header>
</template>