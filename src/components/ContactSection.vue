<script setup>
import ContactInfo from './contact/ContactInfo.vue';
import ContactForm from './contact/ContactForm.vue';
</script>

<template>
<section class="p-4 py-20">
    <div class="mx-auto max-w-7xl w-full">
      <div class="grid lg:grid-cols-2 grid-cols-1 items-center">
        <contact-info phone="111-223-55" email="me@sadhin.me" address="Nakla,Sherpur" />
        <contact-form :displayPhone = false />

      </div>
    </div>
  </section>
</template>

<style scoped>
</style>