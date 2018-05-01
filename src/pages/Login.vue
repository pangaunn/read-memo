<template>
  <section class="section">
    <div class="container">
      <div class="f-s-30px">Read Memooooo</div>
      <button class="button" @click="login">Login</button>
    </div>
  </section>
</template>

<script>
export default {
  methods: {
    login () {
      console.log('login')
    }
  }
}
</script>
