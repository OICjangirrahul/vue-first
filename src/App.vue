<template>
<v-div>

<two/>
  <one/>
</v-div>
</template>

<script>
import two from './components/two.vue'
import one from './components/one.vue';

export default {
  components: { two,one },
  name: 'App',

  data: () => ({
    //
  }),
};
</script>
