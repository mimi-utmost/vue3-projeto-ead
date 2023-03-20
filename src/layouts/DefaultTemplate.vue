<template>
    <div>
        <header-component/>

        <section>
            <router-view></router-view>
        </section>

        <footer-component/>
    </div>
</template>

<script>

import FooterComponent from './components/FooterComponent.vue'

import HeaderComponent from './components/HeaderComponent.vue'

export default {
    name: 'DefaultTemplate',
    components: {
        HeaderComponent,
        FooterComponent
    }
}
</script>