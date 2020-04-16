<template>
  <div id="app">
    <div id="nav">
      <router-link to="/" class="ruta">FoodWorld</router-link> |
      <router-link to="/about" class="ruta">Agradecimientos</router-link>
    </div>
    <div class="view">
    <transition name="slide-fade" mode="out-in">
        <router-view/>
    </transition>
    </div>
  </div>
</template>

<style scoped>

@media only screen and (min-width:561px){
    .fade-enter-active, .fade-leave-active{
        transition: opacity .5s
    }
    .fade-enter, .fade-leave-to{
        opacity: 0;
    }
    .slide-fade-enter-active {
        transition: all .3s ease;
    }
    .slide-fade-enter-active{
        transition:all .3s cubic-bezier(1.0,0.5,0.8,1.0);
    }
    .slide-fade-enter, .slide-fade-leave-to{
        transform: translateY(80px);
        opacity: 0;
    }
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #ffffff;
}

#nav{
    overflow: hidden;
    position: fixed;
    top: 0;
    width: 100%;
    z-index:1;
}
.view{
    min-height: 100vh;
}

.ruta {
    color: rgb(255, 255, 255);
    text-decoration: none;
    padding: 2.5rem 1.5rem;
    font-size: 2rem;
    
}
.ruta:last-of-type{
    margin-right: 0;
}
#nav{
    text-align: center;
    background-color: rgb(17, 16, 17);
    padding: 1.5rem; 
    margin: 0;
}
.ruta{
    text-decoration: none;
}
.ruta:last-of-type:hover{
    border-top-right-radius: 2rem; 
    border-bottom-right-radius:2rem;
}
.ruta:first-of-type:hover{
    border-top-left-radius:2rem;
    border-bottom-left-radius:2rem
}
.ruta:hover{
    color: rgb(134, 128, 128);
    padding: 2.5rem 1.5rem;  
}
}
@media only screen and (max-width:560px){
    .fade-enter-active, .fade-leave-active{
        transition: opacity .5s
    }
    .fade-enter, .fade-leave-to{
        opacity: 0;
    }
    .slide-fade-enter-active {
        transition: all .3s ease;
    }
    .slide-fade-enter-active{
        transition:all .3s cubic-bezier(1.0,0.5,0.8,1.0);
    }
    .slide-fade-enter, .slide-fade-leave-to{
        transform: translateY(80px);
        opacity: 0;
    }
 #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  color: #ffffff;
}

#nav{
    overflow: hidden;
    position: fixed;
    top: 0;
    width: 100%;
    z-index:1;
}
.ruta {
    color: rgb(255, 255, 255);
    text-decoration: none;
    padding: 2.5rem 1.5rem;
    font-size: 1.5rem;
    
}
.ruta:last-of-type{
    margin-right: 0;
}
#nav{
    text-align: center;
    background-color: rgb(17, 16, 17);
    padding: 1.5rem; 
    margin: 0;
}
.ruta{
    text-decoration: none;
}
.ruta:last-of-type:hover{
    border-top-right-radius: 2rem; 
    border-bottom-right-radius:2rem;
}
.ruta:first-of-type:hover{
    border-top-left-radius:2rem;
    border-bottom-left-radius:2rem
}
.ruta:hover{
    color: rgb(134, 128, 128);
    padding: 2.5rem 1.5rem;  
} 
}
</style>
