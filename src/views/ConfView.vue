<template>
  <div class="about">
    <h1>Конференции</h1>
  </div>
  <p v-if="seen">Now you see me</p>
  <button :disabled="isButtonDisabled">Button</button>
</template>
