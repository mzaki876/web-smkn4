<!-- <template>
    <div class="bg-dark text-white py-4 px-5 d-flex justify-content-between align-items-center">
        <div class="d-flex align-items-center">
            <img src="/asset/img/LOGO-SMK4 1.png" alt="SMKN Logo" class="me-3">
            <div>
                <h1 class="display-5 fw-bold">{{ title }} <span class="fst-italic">{{ subtitle }}</span></h1>
                <p class="mb-0">{{ address }}</p>
            </div>
        </div>
        <img src="/asset/img/logo 1.png" alt="Kota Tasik Logo">
    </div>
</template>

<script>
export default {
    data() {
        return {
            title: 'SMKN 4',
            subtitle: 'Tasikmalaya',
            address: 'Jln. Depok, Sukamenak, Purbartau, Kota Tasikmalaya, 46196',
            logoLeft: 'https://via.placeholder.com/70',
            logoRight: 'https://via.placeholder.com/70'
        };
    }
}
</script>

<style>
/* Tambahkan CSS kustom di sini jika diperlukan */
</style> -->


<template>
    <div class="header-container bg-dark text-white py-3 px-5 d-flex justify-content-between align-items-center">
            <img src="/asset/img/LOGO-SMK4 1.png" class="school-logo me-3">
            <div class="flex-grow-1 text-center">
      <h1 class="school-title">{{ title }} <span class="school-subtitle">{{ subtitle }}</span></h1>
      <p class="school-address">{{ address }}</p>
        </div>
        <img src="/asset/img/logo 1.png" alt="Kota Tasik Logo" class="city-logo">
    </div>
</template>

<script>
export default {
    data() {
        return {
            title: 'SMKN 4',
            subtitle: 'Tasikmalaya',
            address: 'Jln. Depok, Sukamenak, Purbartau, Kota Tasikmalaya, 46196',
            logoLeft: '/path/to/smkn-logo.png',
            logoRight: '/path/to/kota-logo.png'
        };
    }
}
</script>

<style>
@font-face {
  font-family: 'Font';
  src: url('/asset/style/04B_30__.TTF') format('truetype');
}
.header-container {
  font-family: 'Arial', sans-serif;
}


.school-logo,
.city-logo {
    height: 70px;
}

.school-title {
    font-family: 'Font', cursive;
    font-size: 2.5rem;
    font-weight: bold;
    text-align: center;
}

.school-subtitle {
    font-style: italic;
}

.school-address {
    margin-top: 5px;
    font-size: 1rem;
    text-align: center;
}
</style>