<template>
  <div>
    <p>mainComp {{ func1() }}</p>
    <LIbComp></LIbComp>
  </div>
</template>

<script setup lang="ts">

import LIbComp from 'lib/components/LibComp.vue'
import {func1} from 'lib/components/utilcode'


</script>
