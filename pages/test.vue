<template>
  <div class="bg-secondary">
    <div>
      <b-row  style="height: 100vh">
        <b-col  cols="12" md="6" sm="12">
          
        </b-col>
        <b-col  cols="12" md="6" sm="12">
          <div style="position: absolute; right: 3rem; z-index: 100">
            <img style="width: 3rem;" class="mx-2" src="/TWITTER.svg"></img>
            <img style="width: 3rem;" class="mx-2" src="/IG.svg"></img>
            <img style="width: 3rem;" class="mx-2" src="/OPENSEA.svg"></img>
            <img style="max-width: 2rem;" class="mx-2" src="/etherscan-logo.svg"></img>
            
          </div>
        </b-col>
      </b-row>
    </div>
    <b-container class="pt-3 m-0" fluid>
      <div>
        <b-card-group columns>
            <b-card
            img-src="/images/gallery/7818.png"
            img-alt="Image"
            class="border-0"
            overlay
          ></b-card>
            <b-card
            img-src="/images/gallery/7846.png"
            img-alt="Image"
            class="border-0"
            overlay
          ></b-card>
          <b-card
            img-src="/images/gallery/7812.png"
            img-alt="Image"
            class="border-0"
            overlay
          ></b-card>
          
          
          <b-card
            img-src="/images/gallery/7811.png"
            img-alt="Image"
            class="border-0"
            overlay
          ></b-card>
          <b-card
            img-src="/images/gallery/8061.png"
            img-alt="Image"
            class="border-0"
            overlay
          ></b-card>
          <b-card
            img-src="/images/gallery/4741.png"
            img-alt="Image"
            class="border-0"
            overlay
          ></b-card>
          <b-card
            img-src="/images/gallery/4040.png"
            img-alt="Image"
            class="border-0"
            overlay
          ></b-card>
          <b-card
            img-src="/images/gallery/1356.png"
            img-alt="Image"
            class="border-0"
            overlay
          ></b-card>
          <b-card
            img-src="/images/gallery/88.png"
            img-alt="Image"
            class="border-0"
            overlay
          ></b-card>
          <b-card
            img-src="/images/gallery/36.png"
            img-alt="Image"
            class="border-0"
            overlay
          ></b-card>
          <b-card
            img-src="/images/gallery/5109.png"
            img-alt="Image"
            class="border-0"
            overlay
          ></b-card>
          <b-card
            img-src="/images/gallery/5211.png"
            img-alt="Image"
            class="border-0"
            overlay
          ></b-card>
          <b-card
            img-src="/images/gallery/5406.png"
            img-alt="Image"
            class="border-0"
            overlay
          ></b-card>
          <b-card
            img-src="/images/gallery/5812.png"
            img-alt="Image"
            class="border-0"
            overlay
          ></b-card>
          <b-card
            img-src="/images/gallery/7596.png"
            img-alt="Image"
            class="border-0"
            overlay
          ></b-card>
          <b-card
            img-src="/images/gallery/7779.png"
            img-alt="Image"
            class="border-0"
            overlay
          ></b-card>
          <b-card
            img-src="/images/gallery/7798.png"
            img-alt="Image"
            class="border-0"
            overlay
          ></b-card>
          <b-card
            img-src="/images/gallery/7808.png"
            img-alt="Image"
            class="border-0"
            overlay
          ></b-card>
        </b-card-group>
      </div>
    </b-container>

    <b-container fluid class="py-5">
      <b-row align-v="center" style="height: 55vh">
        <b-col  cols="12" md="6" sm="12">
            <h2 class="text-center">MGMS</h2>
            <p class="px-5">
                Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
            </p>
        </b-col>
        <b-col class="bg-secondary" cols="12" md="6" sm="12">
            <div>
                <b-img src="https://picsum.photos/1024/400/?image=41" fluid alt="Responsive image"></b-img>
            </div>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid class="bg-dark">
         <b-row align-h="between" class="px-4">
        <b-col cols="auto" class="mr-auto p-3">
          <div class="terms" style="text-decoration: underline">
            <nuxt-link to="/terms" class="text-white"
              >THE HEIST TERMS & CONDITIONS</nuxt-link
            >
          </div>
          <div class="terms">2022 THE HEIST ™</div>
        </b-col>
        <b-col cols="auto" class="ml-auto p-3"
          ><img style="height: 36px" src="/Mel-Signature.svg"
        /></b-col>
      </b-row>

    </b-container>
  </div>
</template>
<script>
export default {
    head () {
    return {
      bodyAttrs: {
        class: 'reset-body'
      }
    }
  }
};
</script>
<style scoped>

.reset-body {
  margin: 0
}

.terms {
    font-family: "Champange";
    font-size: 16px;
  }
</style>
