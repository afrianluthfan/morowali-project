<template>
  <div class="topbar">
    <div class="bartipis" />
    <h1>Admin Desa xxxx</h1>
    <p>Kabupaten, yyyy</p>
    <!-- Tambahkan konten atau komponen lain sesuai kebutuhan -->
  </div>
</template>

<style scoped>
.topbar {
  display: grid;
  grid-template-columns: 1% 1fr;
  grid-template-rows: repeat(2, minmax(0, 1fr));
}

.bartipis {
  --tw-bg-opacity: 1;
  background-color: rgb(0 0 0 / var(--tw-bg-opacity));
  width: 0.25rem /* 4px */;
  grid-row: span 2 / span 2;
}
</style>
