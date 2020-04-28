<template>
  <div>
      <input type="date" v-model="inputDate" placeholder="Enter Date">
      <input type="time" v-model="inputTime">
      <input type="text" v-model="inputName" placeholder="Timer Name">
      <input type="button" v-on:click="startTimer" value="Start Timer">
  </div>
</template>

<script>
export default {
    name: 'TimerInput',
    inputName: String,
    inputDate: String,
    inputTime: String,
    methods: {
        startTimer: function() {
            console.log(this.inputName)
            console.log(this.inputDate)
            console.log(this.inputTime)
        }
    }
}
</script>

<style>

</style>