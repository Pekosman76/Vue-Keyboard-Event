<template>
  <div>

  </div>
</template>

<script>
export default {
  methods: {
    getKeyboard: function(event) {
      console.log(event.key)
    }
  },
  mounted () {
    window.addEventListener("keydown", this.getKeyboard);
  }
}
</script>

<style>

</style>