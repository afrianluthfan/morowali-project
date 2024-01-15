<template>
  <div class="wrapper-topbar">
    <div class="topbar">
      <div class="bartipis" />
      <h1 class="admin-desa">Admin Desa xxxx</h1>
      <p>Kabupaten, yyyy</p>
      <!-- Tambahkan konten atau komponen lain sesuai kebutuhan -->
    </div>
    <div class="containerbtn">
      <button>user</button>
    </div>
  </div>
</template>

<style scoped>
.containerbtn {
  display: flex;
  justify-content: flex-end;
  align-items: center;
  padding-right: 100px;
}

.wrapper-topbar {
  display: grid;
  grid-template-columns: auto auto;
}
.topbar {
  display: grid;
  grid-template-columns: 1% 1fr;
  grid-template-rows: repeat(2, minmax(0, 1fr));
  padding-top: 10px;
  padding-bottom: 10px;
}

.bartipis {
  --tw-bg-opacity: 1;
  background-color: rgb(0 0 0 / var(--tw-bg-opacity));
  width: 0.25rem /* 4px */;
  grid-row: span 2 / span 2;
  height: 100%;
}

.admin-desa {
  font-size: 1.5rem /* 24px */;
  font-weight: 700;
}
</style>
