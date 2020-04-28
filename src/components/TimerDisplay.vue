<template>
  <div>
      <p>{{days}} : {{hours}} : {{minutes}} : {{seconds}}</p>
  </div>
</template>

<script>
export default {
    name: 'TimerDisplay',
    props: {
        days: {default: 0, type: Number},
        hours: {default: 0, type: Number},
        minutes: {default: 0, type: Number},
        seconds: {default: 0, type: Number},
    }
}
</script>

<style>

</style>