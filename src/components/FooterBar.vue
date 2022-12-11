<template>
  <v-footer color="#eee8dd" padless outlined class="mt-3 footer" >
    <v-card-text class="flex text-center text">
      <div class="W-ubication-div">
        <img src="@/assets/location.png" class="W-ubication-logo" alt="Instagram Logo"/>
        <label class="W-ubication-label"> Vicente Lopez, BsAs</label>
      </div>
      {{new Date().getFullYear()}} - Filum
    </v-card-text>
  </v-footer>
</template>

<script>
export default {
  name: "FooterBar"
}
</script>

<style scoped>
.text{
  font-weight: bold;
  font-size: 15px;
}
.footer{
  position: absolute;
  left: 0;
  bottom: 0;
  right: 0;
}

.W-ubication-label{
  text-align: center;
}

.W-ubication-div{
  display: flex;
  justify-content: center;
}

.W-ubication-logo{

  width: 20px;
}
</style>