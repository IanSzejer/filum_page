<template>
  <v-container>
    <v-card class="mx-auto my-12 W-card-style"
            max-width="40%">
      <v-card-text>
        <p class="text-h4 text--primary W-tittle">
          Somos Filum
        </p>
          <div class="W-link-div">
            <a href="https://www.w3schools.com">
              <img src="@/assets/instagram.jpg" class="image-style" alt="Instagram Logo"/>
              <label class="image-label">@Filum_3D</label>
            </a>
          </div>
        <div class="W-link-div">
          <a href="https://www.w3schools.com">
            <img src="@/assets/whattsap.png" class="image-style" alt="Whatsapp Logo"/>
            <label class="image-label">+54 11 2190-9692</label>
          </a>
        </div>
        <div class="W-link-div">
          <a href="https://www.w3schools.com">
            <img src="@/assets/mail.png" class="image-style" alt="Mail Logo"/>
            <label class="image-label">info@filum3d.com</label>
          </a>
        </div>
      </v-card-text>



    </v-card>
  </v-container>
</template>

<script>
  export default {
    name: 'HelloWorld',

  }
</script>

<style scoped>

.W-card-style{
  display: flex;
  justify-content: left;
}

.W-tittle{
  margin-left: 60px;

}

.W-link-div{
  display: flex;
  text-align: left;
  margin: 5px;

}

.image-style{
  max-width: 7%;
  vertical-align:middle;
  margin-left: 60px;
}


.image-label{
  padding-left: 5px;
  vertical-align:middle;
}
</style>