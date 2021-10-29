<template>
  <div class="container-jumbo-tron">
    <div class="jumbo-tron-logo-wrapper">
      <img
        src="~/assets/icon-bicarakan-white-cropped.webp"
        class="jumbo-tron-logo-background"
      />
    </div>
    <div class="jumbo-tron-logo-wrapper woman-jumbotron">
      <img
        src="~/assets/woman-banner-jumbotron.webp"
        class="person-main-first-banner"
      />
    </div>
    <div class="content-text-banner-wrapper">
      <div class="row">
        <div class="col-lg-6">
          <div class="main-title-first-banner">
            Psikolog Klinis Terbaik, Profesional, Berempati, dan Non-Judgmental
          </div>
          <div class="subtitle-first-banner">
            Bicarakan isi hatimu, temukan jalan keluar atas masalahmu.
          </div>
          <button class="jadwalkan-konseling-button">
            Jadwalkan Konsultasi
          </button>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss">
.person-main-first-banner {
  width: 300px;
}

.jadwalkan-konseling-button {
  display: flex;
  flex-direction: row;
  align-items: flex-start;
  padding: 15px 30px;
  position: absolute;
  background: #ffb01a;
  border-radius: 30px;
  border: none;
  color: white;
}

.subtitle-first-banner {
  font-size: 20px;
  color: white;
  padding: 20px 0px;
}

.main-title-first-banner {
  font-size: 50px;
  color: white;
}

.content-text-banner-wrapper {
  position: absolute;
  z-index: 1;
  padding: 70px 70px;
}

.container-jumbo-tron {
  background-color: #95b9ff;
  // margin-left: -220px;
  margin-top: 80px;
  overflow: hidden;
  height: 500px;
  width: auto;
  display: flex;
  justify-content: flex-start;
  // background-image: url(/public/bicarakan-single-logo.svg);
  position: relative;
}

.jumbo-tron-logo-background {
  width: 600px;
  opacity: 10%;
  margin-top: -60px;
  position: relative;
  z-index: 0;
}

.jumbo-tron-logo-wrapper {
  position: relative;
  z-index: 0;
}

.woman-jumbotron {
  bottom: 0;
  justify-content: center;
  width: 100%;
  display: flex;
  align-items: flex-end;
}
</style>