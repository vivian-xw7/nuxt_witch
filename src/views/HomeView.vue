<!-- eslint-disable vue/no-parsing-error -->
<template>
    <div class="home">
      <div class="container px-20 pt-32 pb-20">
        <div class="row">
          <div
            class="col w-full lg:w-1/2 flex flex-col justify-center mb-12 lg:mb-0 text-center lg:text-left"
          >
            <div class="hero-banner__text-wrapper">

            </div>
          </div>
          <div
            class="col w-full lg:w-1/2 flex flex-col justify-center items-center"
          >

          </div>
        </div>
      </div>
    </div>
  </template>
  
  <script>

  </script>
  
  <style scoped>
  .hero-banner__image-wrapper {
    position: relative;
  
    &::before {
      content: "";
      display: block;
      padding-top: 115%;
    }
  
    .hero-banner__image {
      position: absolute;
      top: 0;
      left: 0;
      bottom: 0;
      right: 0;
      background-image: no-repeat;
  
      img {
        height: 100%;
        width: 100%;
        object-fit: cover;
      }
    }
  }
  </style>
  