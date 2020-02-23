<template>
  <div class="background" id="home">
    <NavBar />
      <v-content class="content">
        <v-container fill-height >
          <v-row>
            <v-col md="3">
              <SideBar />
            </v-col>
            <v-col md="8">
              <router-view></router-view>
            </v-col>
        </v-row>
      </v-container>
    </v-content>
  </div>
</template>

<script>
import NavBar from '../components/NavBar'
import SideBar from '../components/SideBar'

export default {
  name: "Home",
  components: {
    NavBar,
    SideBar
  }
}
</script>

<style>
  .background {
    background: #1E2227;
    min-height: 150%;
  }

  .content {
    margin-top: 70px;
  }
</style>