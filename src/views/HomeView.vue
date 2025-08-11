<script setup>
import Header from "@/components/Header.vue"
import Contact from "@/components/Contact.vue"
import Footer from "@/components/Footer.vue"
import Skip from "@/components/Skip.vue";
import Intro from "@/components/Intro.vue";
import Skill from "@/components/Skill.vue";
import Port from "@/components/Port.vue";
import Site from "@/components/Site.vue";
</script>

<template>
    <Skip></Skip>
    <Header/>
    <main id="main" role="main">
        <Intro></Intro>
        <Skill></Skill>
        <Site/>
        <Port></Port>
        <Contact/>
    </main>

    
    <Footer/>

</template>