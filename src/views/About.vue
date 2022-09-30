<script lang="ts">
import Vue from 'vue';
import { r2 } from '@/modules/reexported';
import n2 from '@/modules/n2';
import { s2 } from '@/modules/single';

export default Vue.extend({
  created() {
    r2();
    s2();
    n2();
  },
});
</script>

<template>
  <div class="about">
    <h1>This is an about page</h1>
  </div>
</template>
