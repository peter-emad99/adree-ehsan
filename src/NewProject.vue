<script setup>
import FormField from "./components/FormField.vue";
import AppLayout from "./components/AppLayout.vue";
</script>

<template>
  <AppLayout>
    <div class="container">
      <div class=".page-content">
        <h2 class="title title-black page-title">المشروع الجديد</h2>
        <div class="form-fields-grid">
          <FormField />
          <FormField />
          <FormField />
          <FormField />
          <FormField />
          <FormField />
          <button class="btn btn-primary">انشاء مشروع</button>
          <button class="btn btn-primary-outline">انشاء مشروع</button>
        </div>
      </div>
    </div>
  </AppLayout>
</template>

<style></style>
