const newLocal='Menuppal'
<template>
  <div id="nav">
     
    <b-nav class="navbar navbar-expand-lg navbar-light bg-light">
      <b-div class="container-fluid">
        <a class="navbar-brand" href="#">SIG735</a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarToggler42"
          aria-controls=""
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarToggler42">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
           
            <b-li class="nav-item">
             <b-a class="nav-link active" href="#">
                    <router-link  to="/" class="nav-item nav-link">
             
               Inicio
            
                </router-link>

              </b-a>
            </b-li>
            <b-li>
              <span v-if="isLoggedIn">
                      <a @click="logout">Logout</a>
              </span>
               <span v-else>
                    <router-link to="/Login">Ingreso</router-link>
              </span>
            </b-li>
            <!--
            <li class="nav-item">
             <a class="nav-link active" href="#">
                    <router-link  to="/Inicio" class="nav-item nav-link">
             
               Login
            
                </router-link>

              </a>
            </li>
           -->
            <b-li class="nav-item">
              <a class="nav-link active" href="#">
                    <router-link  to="/Usuarios" class="nav-item nav-link">
             
               Usuarios
            
                    </router-link>

              </a>
            </b-li>
            
            <b-li class="nav-item">
                 <a class="nav-link active" href="#">
                    <router-link  to="/Categorias" class="nav-item nav-link">
             
               Categorias
            
                </router-link>
                </a>
                </b-li> 
            
            <b-li class="nav-item">
              <a class="nav-link active" href="#">
                    <router-link  to="/Productos" class="nav-item nav-link">
             
               Productos
            
                </router-link>
                </a>
            </b-li>
          
              <b-li class="nav-item">
              <a class="nav-link active" href="#">
                    <router-link  to="/Tercero" class="nav-item nav-link">
             
               Tercero
            
                </router-link>
                </a>
            </b-li>
              <a class="nav-link active" href="#">
                    <router-link  to="/Ventas" class="nav-item nav-link">
             
               Documentos
            
                </router-link>
                </a>
            <b-li class="nav-item">
            <a class="nav-link active" href="#">
                    <router-link  to="/Carrito" class="nav-item nav-link">
             
               ...
            
                </router-link>
                </a>
            </b-li>

          <b-form class="d-flex">
            <input
              class="form-control me-2"
              type="search"
              placeholder="Buscar.."
              aria-label="Search"
            />
            <button class="btn btn-outline-success" type="submit">
            <li class="nav-item">
            <a class="nav-link active" href="#">
                    <router-link  to="/Compras" class="nav-item nav-link">

               Compras
            
                </router-link>
                </a>
            </li>
          </ul>

          <b-form class="d-flex">
            <input
              class="form-control me-2"
              type="search"
              placeholder="Buscar.."
              aria-label="Search"
            />
            <button class="btn btn-outline-success" type="submit">              
              Buscar
            </button>
          </b-form>
        </div>
      </b-div>
    </b-nav>
      
  </div>
 
</template>
<script>
import { mapActions } from "vuex";
export default {
  name: "Menuppal",
  props: {
    msg: String,
  },
  computed : {
      isLoggedIn : function(){ return this.$store.getters.isAuthenticated}
    },
    methods: {

      ...mapActions(["LogOut"]),
      async logout (){
          await this.$store.commit('LogOut')
       // await this.$store.dispatch('LogOut')
        this.$router.push('/Login')
      }
       
    
  
    },
    
};
</script > 
<style scoped>
h3 {
  margin: 40px 0 0;
}

h1 {
  margin: 40px 0 0;
}
</style> 