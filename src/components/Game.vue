<template>
  <div>
    <header class="header">
      <div  class="msg">
          <h1>Almost before we knew it, we had left the ground.</h1>
      </div>
    </header>
    <section data-aos="fade-right"
     data-aos-offset="300"
     data-aos-easing="ease-in-sine" class="food">
        <img src="../assets/8.jpg" alt="">
        <div class="caja">
            <h2>lorem ipsum</h2>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Magnam sapiente iste aliquam blanditiis quam
            illum sequi numquam amet maiores aperiam vero sint natus impedit, est deserunt sed. Nostrum, quas nihil!</p>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ipsa accusamus officia error. Rem voluptatibus corrupti cupiditate?
            Officia nulla dolorem deleniti nisi? Quaerat soluta optio quas officiis nemo corporis enim distinctio?</p>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Error omnis doloribus animi repellendus optio cum odio!
            Iure ab assumenda, pariatur doloribus velit fugiat quas itaque sint quia autem eveniet reprehenderit?</p>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Eum aut molestias, ratione in labore nam deserunt
             iure! Natus, laborum placeat in totam cumque quibusdam culpa dicta quaerat dolor sequi reiciendis.</p>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Explicabo vitae voluptates officia tempora 
            odit in atque mollitia amet dolore ea natus praesentium suscipit a, quos iste distinctio eos ex pariatur!</p>
        </div>
    </section>
    <section class="cartas">
        <div class="display">
        <div data-aos="zoom-in-down">
            <div class="menu">
                <img src="../assets/13.jpg" alt="">
                <div>
                  <h3>Carta 1</h3>
                  <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit</p>
                </div>
            </div>
          </div>
          <div data-aos="zoom-in-down">
            <div class="menu">
                <img src="../assets/14.jpg" alt="">
                <div>
                  <h3>Carta 2</h3>
                  <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit</p>
                </div>
            </div>
          </div>
          <div data-aos="zoom-in-down">
            <div class="menu">
                <img src="../assets/15.jpg" alt="">
                <div>
                  <h3>Carta 2</h3>
                  <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit</p>
                </div>
            </div>
          </div>
        </div>
    </section>
    <section data-aos="fade-up"
     data-aos-anchor-placement="top-center"
     class="final">
      <div>
        <h2>Lorem Ipsum</h2>
        <div class="parrafo">
        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ipsa dolorem expedita delectus cumq
         architecto unde incidunt nihil qui! Corporis tenetur beatae iure cum nulla dolorum velit nam dolor vel sunt.</p>
        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Modi consequuntur exercitationem, consectetur necessitatibus pariatur
         asperiores non dignissimos neque quam nobis sunt quod voluptas alias rem quis, atque in dolore suscipit!</p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Beatae autem, quo, hic ipsam cum blanditiis error maiores numquam
         officiis architecto totam suscipit, voluptas nesciunt nisi nam eligendi repellat fugit similique?</p>
        </div>
      </div>
        <img src="../assets/2.jpg" alt="">
    </section>
  </div>
</template>

<script>
export default {
  name: 'Game',

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
@media only screen and (min-width:561px){
  .header{
    background-image: url(../assets/1.jpg);
    height: 100vh;
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center center;
    top: 0%;
    
  }

h1{
  color: #ffffff;
  text-shadow: 1px 1px 0px #0f0f0f, 0 0 1em #0f0f0f, 0 0 0.2em #0f0f0f;
  font-size: 8rem;
  font-family: 'Roboto', sans-serif;
}
h2{
  font-size: 8rem;
  font-family: 'Gotu', sans-serif;
  margin: 0rem;
  padding: 0rem;
}
p{
  font-size: 1.8rem;
  font-family: 'Gotu', sans-serif;
  line-height: 2rem;
  text-align: justify;
}
.caja{
  padding:2rem 7rem 0rem 0rem;
}
.caja h2{
  text-align: center
}
.msg {
  padding: 5rem;
}
.msg h1{
  margin: 2rem 35rem 5rem 5rem;
}
.food{
  display: flex;
  justify-content: space-between;
}
.food img{
  height: 70rem;
  padding: 7rem;
}

.cartas{
    background-image: url(../assets/12.jpg);
    height: 100vh;
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center center;
    background-attachment: fixed;
}

.display{
  padding: 3rem 7rem;
  display: flex;
  justify-content: space-between;
  font-family: 'Gotu', sans-serif;
  color: #534f4f;
}
.menu{
  text-align: center;
  font-size: 2rem;
  background-color: #fffefecc;
  padding: 2rem;
  margin: 3rem;
}
.menu h3::after{
  content: ''; /*preguntar como se pone en el centro*/
        display: block;
        height: 0.3rem;
        width: 8rem;
        background-color: #534f4f;
        margin-left: 10rem;
}
.menu p{
  text-align: center;
  margin: 0rem 4rem 4rem 4rem;
  
}
.menu img{
  height: 20rem;
}
.final{
  display: flex;
  justify-content: space-between;
  text-align: center;
  
}
.final img{
  height: 70rem;
  padding: 7rem;
}
.parrafo{
  margin: 0rem 20rem;
}
.parrafo p{
  text-align: center;
}

}
@media only screen and (max-width:560px){
  .header{
    background-image: url(../assets/1.jpg);
    height: 100vh;
    background-attachment: fixed;
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center center;
    top: 0%;
    
  }

h1{
  color: #ffffff;
  text-shadow: 1px 1px 0px #0f0f0f, 0 0 1em #0f0f0f, 0 0 0.2em #0f0f0f;
  font-size: 4rem;
  font-family: 'Roboto', sans-serif;
}
h2{
  font-size: 4rem;
  font-family: 'Gotu', sans-serif;
  margin: 0rem;
  padding: 0rem;
}
p{
  font-size: 1.5rem;
  font-family: 'Gotu', sans-serif;
  line-height: 1.7rem;
  text-align: justify;
}
.caja{
  padding:2rem 4rem 0rem 0rem;
}
.caja h2{
  text-align: center
}
.msg {
  padding: 3rem;
}
.msg h1{
  padding-top: 8rem;
}
.food{
  display:flex;
  flex-direction: column;
  align-items: center;
}
.food p{ 
  padding-left: 3rem;
}

.food img{
  height: 40rem;
  padding-top: 4rem;
}
.cartas{
    background-image: url(../assets/12.jpg);
    height: 100vh;
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center center;
}
.display{
  padding-top:3rem;
}
.menu{
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.menu{
  color: #534f4f;
  background-color: #fffefecc;
  padding: 0rem 1rem;
  margin: 2rem 1rem;
}
.menu h3{
  text-align: center;
  font-size: 3rem;
  font-family: 'Gotu', sans-serif;
  margin:0rem;
}

.menu p{
  text-align: justify;
  padding: 0rem 1rem;
}
.menu img{
  height: 10rem;
}
.final{
  display:flex;
  flex-direction: column;
  align-items: center;
}
.final h2{
  text-align: center;
  font-size: 3rem;
  padding: 2rem 0rem 1rem 2rem;
  margin: 0;
}
.final img{
  height: 40rem
}
.parrafo{
  margin: 2rem 4rem;
}
.parrafo p{
  text-align: center;
}

}
</style>
