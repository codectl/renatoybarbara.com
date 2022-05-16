<script setup>
// import Header from "@/components/Header.vue"
import Home from "@/components/Home.vue"
</script>

<template>
  <q-layout view="lhr lpr lfr" class="">

    <div class="row">
      <q-header reveal :reveal-offset="0" :style="{
        backgroundColor: 'transparent',
        fontFamily: 'Reenie Beanie, cursive',
        color: '#274C77'
      }" class="col-sm-10 col-md-8 offset-sm-1 offset-md-2">
        <q-toolbar>
          <q-toolbar-title :style="{
            fontWeight: 700,
            fontSize: '1.2rem',
          }">
            Renato & Barbara
          </q-toolbar-title>
        </q-toolbar>
      </q-header>
    </div>

    <q-page-container>
      <!--      <Home/>-->
      <q-page>
        <Home/>
      </q-page>

      <q-page-scroller position="bottom-right" :scroll-offset="150">
        <q-btn fab icon="keyboard_arrow_up" color="accent"/>
      </q-page-scroller>
    </q-page-container>

    <!--    <q-footer>-->
    <!--      <q-toolbar>-->
    <!--        <q-toolbar-title>-->
    <!--          <div>Title</div>-->
    <!--        </q-toolbar-title>-->
    <!--      </q-toolbar>-->
    <!--    </q-footer>-->

  </q-layout>
</template>

<style scoped>
</style>
