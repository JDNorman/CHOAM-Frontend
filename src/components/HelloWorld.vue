<script setup>
defineProps({
  welcomemsg: {
    type: String,
    required: false,
  },
  headmsg: {
    type: String,
    required: false,
  },
  submsg: {
    type: String,
    required: false,
  },
  showImg: {
    type: Boolean,
    required: true,
  }
})
</script>

<template>
  <div class="greetings flex">
    <img alt="CHOAM logo" class="logo w-36 h-36" src="../assets/logo.svg" v-if="showImg" />
    <div class="text">
      <div class="m-4">
        <h3>{{ welcomemsg }}</h3>
        <h1 class="yellow">{{ headmsg }}</h1>
      </div>
    </div>
    <h3 class="submsg text-purple disabled relative self-center">{{ submsg }}</h3>
  </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 5rem;
  position: relative;
  top: -10px;
  font-family: 'Made Tommy', serif;
}

.submsg {
  font-family: 'Playwrite CA';
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
