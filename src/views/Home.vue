<template>
  <div>
    <NavBar />
      <v-content>
        <v-container fill-height>
          <v-row>
            <v-col md="4">
              <SideBar />
            </v-col>
            <v-col md="8">
              Content
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