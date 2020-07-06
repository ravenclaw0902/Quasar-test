<template v-for="mess in btn_messages" :key="mess.id" >
  <q-btn icon="check_circle" glossy color="green" @click="acceptLang">{{mess.btn_title}}</q-btn>
</template>

<script>
export default {
  name: 'ButtonMessages',
  props: {
    id: {
      type: Number,
      default: '1'
    },
    btn_lang: {
      type: String,
      default: 'ru_ru'
    },
    btn_title: {
      type: String,
      default: 'Сохранить изменения'
    },
    btn_success: { type: String, default: 'Изменения успешно сохранены' }
  }
}
</script>