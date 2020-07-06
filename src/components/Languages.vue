<template>
  <q-select
    :options="lang.lang_code"
    :label="lang.lang_name"
    style="width: auto; max-width: 250px; margin: 5px"
  />
</template>

<script>
export default {
  name: 'Languages',
  props: {
    id: {
      type: Number,
      value: '',
      default: '1'
    },
    lang_code: {
      type: String,
      value: '',
      default: 'ru_ru'
    },
    lang_name: {
      type: String,
      value: '',
      default: 'Русский'
    }
  }
}
</script>