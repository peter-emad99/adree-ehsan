<script setup>
import Navbar from "./components/Navbar.vue";
import AppLayout from "./components/AppLayout.vue";
import HeroSection from "./components/HeroSection.vue";
</script>

<template>
  <AppLayout>
    <HeroSection />
    <div class="container">
      <section class="page-section">
        <div class="section-header">
          <div class="section-header-divider"></div>
          <div class="section-header-title-wrapper">
            <h2 class="title title-secondary section-title">من فرص التبرع</h2>
          </div>
        </div>
        <div class="section-content">
          <div class="cards-container">
            <template v-for="(item, index) in 3" :key="index">
              <div class="card">
                <div class="card-header">
                  <h3 class="card-title">بناء مسجد</h3>
                  <button class="card-header-action">
                    <img class="btn-icon" src="/share.svg" alt="" />
                  </button>
                </div>
                <img src="/hero-section.jpg" alt="" class="card-img" />
                <div class="card-content">
                  <div class="info-list">
                    <div class="info-item">
                      <span class="info-item_label">تم جمع</span>
                      <span class="info-item_text">1,041,321 ر.س</span>
                    </div>
                    <div class="info-item">
                      <span class="info-item_label">المبلغ المتبقي</span>
                      <span class="info-item_text">3,958,679 ر.س</span>
                    </div>
                  </div>
                  <div class="card-progress">
                    <div class="progress"></div>
                    <div class="progress-value">97%</div>
                  </div>
                  <div class="card-form">
                    <div class="radio-group">
                      <div class="radio-item">100 رس</div>
                      <div class="radio-item">100 رس</div>
                      <div class="radio-item">100 رس</div>
                      <div class="radio-item">100 رس</div>
                    </div>
                    <input
                      type="text"
                      class="input input-rounded-full"
                      placeholder="قيمة التبرع"
                    />
                  </div>
                  <footer class="card-footer">
                    <button class="btn btn-secondary">تبرع الآن</button>
                    <button class="btn btn-primary">
                      <img src="/shopping-cart2.svg" alt="" class="btn-icon" />
                      اضف للسلة
                    </button>
                  </footer>
                </div>
              </div>
            </template>
          </div>
        </div>
        <footer class="section-footer">
          <button class="btn btn-primary">تبرع الآن</button>
        </footer>
      </section>
      <section class="page-section">
        <header class="section-header">
          <div class="section-header-divider"></div>
          <div class="section-header-title-wrapper">
            <h2 class="title title-secondary section-title">
              الجهات الإشرافية
            </h2>
          </div>
        </header>
        <div class="section-content">
          <div class="logos-container">
            <img src="/logos/DGA.svg" alt="" class="logo" />
            <img src="/logos/HRSD.svg" alt="" class="logo" />
            <img src="/logos/mci.svg" alt="" class="logo" />
            <img src="/logos/MOE.svg" alt="" class="logo" />
            <img src="/logos/MOF.svg" alt="" class="logo" />
            <img src="/logos/MOF.svg" alt="" class="logo" />
            <img src="/logos/MOI.svg" alt="" class="logo" />
            <img src="/logos/MOJ.svg" alt="" class="logo" />
            <img src="/logos/MOMRA.svg" alt="" class="logo" />
            <img src="/logos/NC.svg" alt="" class="logo" />
            <img src="/logos/PSS.svg" alt="" class="logo" />
            <img src="/logos/SAMA.svg" alt="" class="logo" />
            <img src="/logos/sdaia.svg" alt="" class="logo" />
          </div>
        </div>
      </section>
    </div>
  </AppLayout>
</template>

<style></style>
