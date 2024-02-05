<script setup lang="ts">
import { name } from "../package.json";
import {AboutCard} from 'ui'
import { config } from './mocks/index';
</script>

<template>
  <AboutCard>
    <h1>{{ name }}</h1>
    <p>{{ config.name }}</p>
    <p>{{ config.description }}</p>
    <p>{{ config.about }}</p>
  </AboutCard>
</template>
