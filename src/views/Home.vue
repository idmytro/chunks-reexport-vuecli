<script lang="ts">
import Vue from 'vue';
import { r1 } from '@/modules/reexported';
import n1 from '@/modules/n1';
import { s1 } from '@/modules/single';

export default Vue.extend({
  created() {
    r1();
    s1();
    n1();
  },
});
</script>

<template>
  <div class="home">
    HOME
  </div>
</template>
