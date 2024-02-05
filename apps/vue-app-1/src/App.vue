<script setup lang="ts">
import { name } from "../package.json";
import {AboutCard} from 'ui'
</script>

<template>
  <AboutCard>
    <h1>{{ name }}</h1>
  </AboutCard>
</template>
