<script setup>
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <svg
    width="625"
    height="272"
    viewBox="0 0 625 272"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
    class="w-[624.16px] h-[271.23px]"
    preserveAspectRatio="none"
  >
    <RouterLink
      to="/com"
      class="stroke-black transition ease hover:stroke-rouge"
      :class="{
        'stroke-rouge': $route.name === 'com',
      }"
    >
      <!--PATH com-->
      <path
        d="M10.8252 60.285L13.2009 144.038H324.125L321.749 24.6345H110.806V83.1471H83.4182V60.7786L10.8252 60.285Z"
        class="transition ease hover:fill-rouge fill-black partiecom"
        :class="{
          'fill-rouge': $route.name === 'com',
        }"
      ></path>
      <!--PATH com-->
      <path
        d="M0 60.8008H88.8419V84.2462H106.077V25.7786H110.806"
        stroke-miterlimit="10"
        class="partiecom"
      ></path>
      <!--PATH com-->
      <path
        d="M13.0439 153.932H324.125"
        stroke-miterlimit="10"
        class="partiecom"
      ></path>
      <!--PATH com-->
      <path
        d="M264.688 19.4294H327.217V37.0415"
        stroke-miterlimit="10"
        class="partiecom"
      ></path>
    </RouterLink>

    <RouterLink
      to="/crea"
      class="stroke-black transition ease hover:stroke-bleu"
      :class="{
        'stroke-bleu': $route.name === 'crea',
      }"
    >
      <path
        d="M624.157 29.2339V122.881H591.211V145.451"
        stroke-miterlimit="10"
      ></path>
      <path
        d="M395.889 99.413H388.291V145.451H581.775V112.314H614.027V29.2339H395.889V99.413Z"
        class="transition ease hover:fill-bleu fill-black"
        :class="{
          'fill-bleu': $route.name === 'crea',
        }"
      ></path>
      <path d="M396.001 0V99.413H380.604" stroke-miterlimit="10"></path>
      <path d="M357.272 144.307H388.291V99.4128" stroke-miterlimit="10"></path>
      <path
        d="M369.599 144.307H368.344V153.932H369.599V144.307Z"
        class="fill-bleu"
        stroke-miterlimit="10"
      ></path>
      <path d="M389.031 118.618H380.604" stroke-miterlimit="10"></path>
    </RouterLink>

    <RouterLink
      to="/dev"
      class="stroke-black transition ease hover:stroke-vert"
      :class="{
        'stroke-vert': $route.name === 'dev',
      }"
    >
      <path
        d="M420.004 223.259H380.604V163.176H507.793V263.598H419.108L420.004 223.259Z"
        class="transition ease hover:fill-vert fill-black"
        :class="{
          'fill-vert': $route.name === 'dev',
        }"
      ></path>
      <path d="M420.004 271.226H507.792" stroke-miterlimit="10"></path>
      <path d="M506.582 190.839V153.932" stroke-miterlimit="10"></path>
    </RouterLink>

    <RouterLink
      to="/secret"
      class="stroke-black transition ease hover:stroke-jaune"
      :class="{
        'stroke-jaune': $route.name === 'secret',
      }"
    >
      <path
        d="M373.365 25.689H348.397V50.6824H373.365V25.689Z"
        class="transition ease hover:fill-jaune fill-black"
        :class="{
          'fill-jaune': $route.name === 'secret',
        }"
        stroke-miterlimit="10"
      ></path>
      <path d="M333.941 25.689H348.397" stroke-miterlimit="10"></path>
      <path d="M373.387 50.6824V68.6086" stroke-miterlimit="10"></path>
    </RouterLink>
  </svg>
</template>
<style scoped></style>
