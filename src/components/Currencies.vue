<template v-for="curr in currencies" :key="curr.id">
  <q-select
    :options="curr.code"
    style="width: auto; max-width: 250px; margin: 5px"
  >{{curr.name_ru_ru}}</q-select>
</template>

<script>
export default {
  name: 'Currencies',
  props: {}
}
</script>