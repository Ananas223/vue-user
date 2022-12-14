<template>
  <UserCard 
  v-bind:name="name"
  v-bind:surname="surname"
  v-bind:patr="patr"
  v-bind:location="location"
  v-bind:mail="mail"
  v-bind:phone="phone"></UserCard>
</template>

<script>
import UserCard from './components/UserCard.vue'

export default {
  name: 'App',
  components: {
    UserCard
  },
  data(){
    return{
    name: 'Иван',
    surname: 'Иванов',
    patr: 'Иванович',
    location: 'Москва',
    mail: 'mail@',
    phone: '88000000',
    }
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
