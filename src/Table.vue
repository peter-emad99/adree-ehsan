<script setup>
import AppLayout from "./components/AppLayout.vue";
</script>

<template>
  <AppLayout>
    <div class="container">
      <div class="page-content">
        <h2 class="title page-title title-black">قائمة الطلبات</h2>

        <table>
          <thead>
            <tr>
              <th>الطلب</th>
              <th>المسجل</th>
              <th>الموقع</th>
              <th>الحالة</th>
              <th>التاريخ</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td>الطلب الاول</td>
              <td>مسجل الدخول</td>
              <td>www.google.com</td>
              <td>
                <span class="badge badge-positive">موافق</span>
              </td>
              <td>2022-01-01</td>
            </tr>
            <tr>
              <td>الطلب الثاني</td>
              <td>مسجل الدخول</td>
              <td>www.google.com</td>
              <td>
                <span class="badge badge-notice">ملاحظة</span>
              </td>
              <td>2022-01-02</td>
            </tr>
            <tr>
              <td>الطلب الثالث</td>
              <td>مسجل الدخول</td>
              <td>www.google.com</td>
              <td>
                <span class="badge badge-negative">غير موافق</span>
              </td>
              <td>2022-01-03</td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
  </AppLayout>
</template>

<style></style>
