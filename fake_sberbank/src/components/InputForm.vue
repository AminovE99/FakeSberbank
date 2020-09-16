<template>
  <div>
    <form id="demo" @submit.prevent="onSubmit">
      <p>
        <label for="money">Количество переведенных денег: </label>
        <input id="money" v-model="money">
      </p>
      <p>
        <label for="last_name">Первая буква фамилии</label>
        <input id="last_name" v-model="last_name">
        <label for="first_name">Имя</label>
        <input id="first_name" v-model="first_name">
        <label for="middle_name">Отчество</label>
        <input id="middle_name" v-model="middle_name">
      </p>
      <button type="submit">Generate</button>
    </form>
  </div>
</template>
<script>
export default {
  data () {
    return {
      money: '',
      first_name: '',
      middle_name: '',
      last_name: ''
    }
  },
  methods: {
    onSubmit () {
      console.log(this.money)
      console.log(this.first_name)
    }
  }
}
</script>
