<template v-for="item in transport_types" :key="item.position">
  <q-list>
    <q-item>
      <q-item-section>
        <q-img :src="item.image_url" style="height: auto; max-width: 150px; margin-right: 20px"/>
        <q-item-label>{{ item.title_ru_ru }}</q-item-label>
      </q-item-section>
    </q-item>
  </q-list>
</template>

<script>
export default {
  name: 'TransportTypes',
  props: {}
}
</script>
