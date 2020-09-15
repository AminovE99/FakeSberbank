<template>
  <div id="app">
    <HelloModal />
    <InputForm />
    <SberbankEntity />
  </div>
</template>

<script>
import SberbankEntity from '@/components/SberbankEntity'
import HelloModal from '@/components/HelloModal'
import InputForm from '@/components/InputForm'
export default {
  name: 'App',
  components: {
    SberbankEntity,
    HelloModal,
    InputForm
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
