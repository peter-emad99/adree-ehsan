<script setup>
import AppLayout from "./components/AppLayout.vue";
import FormField from "./components/FormField.vue";
</script>

<template>
  <AppLayout>
    <div class="container login-container">
      <div class="login-card">
        <div class="login-card-icon">
          <img src="/phone.svg" alt="" class="btn-icon" />
        </div>
        <div class="login-card-title title-secondary">تسجيل الدخول</div>
        <div class="form-field">
          <label for="name" class="form-field-label">الاسم</label>
          <input
            type="text"
            class="form-field-control input-rounded-full"
            id="name"
            placeholder="الاسم"
          />
        </div>
        <button class="login-card-action btn btn-primary">سجل الدخول</button>
        <div class="login-card-footer">
          <span class="text-primary">ليس لديك حساب؟</span>
          <button class="btn btn-secondary-text btn-sm">انشاء حساب</button>
        </div>
      </div>
    </div>
  </AppLayout>
</template>

<style></style>
