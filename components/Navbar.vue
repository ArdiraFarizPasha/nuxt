<template>
    <div class="navbar-wrapper">
      <div>
        <img src="~/assets/bicarakan-long-logo-blue-cropped.webp" class="navbar-icon" />
      </div>
      <div class="navbar-menu-wrapper">
        <div class="navbar-menu-single-wrapper">
          Podcast
        </div>
        <div class="navbar-menu-single-wrapper">
          Tentang Kami
        </div>
        <div class="navbar-menu-single-wrapper">
          Konselor
        </div>
        <div class="navbar-menu-single-wrapper">
          Testimoni
        </div>
        <button class="jadwalkan-sesi-button">
          Jadwalkan Sesi
        </button>
      </div>
    </div>
</template>

<style lang="scss">

.navbar-icon {
  width: 200px;
}

.navbar-wrapper {
    padding: 1rem 0rem ;
    min-height: 3rem;
    width: 100%;
    background-color: #f5f5f5;
    overflow: hidden;
    position: fixed; /* Set the navbar to fixed position */
    top: 0; /* Position the navbar at the top of the page */
    display: flex;
    justify-content: space-between;
}

.navbar-menu-wrapper {
    display: flex;
    align-items: center;
    justify-content: center;
}

.navbar-menu-single-wrapper {
    margin: 0rem 1rem;
}

.jadwalkan-sesi-button {
    padding: 12px;
    text-align: center;
    background: #225acf;
    border-radius: 8px;
    color: white;
    margin: 0rem 1rem;
}

</style>