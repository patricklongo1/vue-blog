<template>
  <div>
    <v-card
    flat
    id="theme-background"
    >
      <v-img
        class="white--text align-end bottom-gradient"
        height="200px"
      >
        <v-card-title class="text-center font-weight-black">
            Alana Nicole
        </v-card-title>
      </v-img>
    <v-card-text class="white--text body-3 px-3 text-center">
      Olá! Me chamo Alana, Nasci em 30 de Abril de 2019. Moro em Diadema com meus Pais
      Patrick (Papai), e Luiza (Mamãe) :)
    </v-card-text>
    <v-card-actions>
      <v-btn 
        block
        class="instagram d-flex pa-2 d-flex justify-center mb-6 white--text"
        href="https://www.instagram.com/alana.nicole.longo/?hl=pt-br"
        data-size="large"
        target="_blank"
      >
        <v-icon class="ma-3" color="white">mdi-instagram</v-icon>
          Alana Nicole  
      </v-btn>
    </v-card-actions>

    <v-divider></v-divider>
  </v-card>
  </div>
</template>

<style>
  .bottom-gradient {
    background: linear-gradient(rgba(0, 0, 0, 0), rgba(0, 0, 0, 0.8)),
      url("../assets/alana.jpg") no-repeat;
    background-size: cover;
  }

  #theme-background {
    background-color: #1E2227;
  }

  .instagram{ width:100%; height:100%;
    background: #f09433; 
    background: -moz-linear-gradient(45deg, #f09433 0%, #e6683c 25%, #dc2743 50%, #cc2366 75%, #bc1888 100%); 
    background: -webkit-linear-gradient(45deg, #f09433 0%,#e6683c 25%,#dc2743 50%,#cc2366 75%,#bc1888 100%); 
    background: linear-gradient(45deg, #f09433 0%,#e6683c 25%,#dc2743 50%,#cc2366 75%,#bc1888 100%); 
    filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#f09433', endColorstr='#bc1888',GradientType=1 );
  }
</style>