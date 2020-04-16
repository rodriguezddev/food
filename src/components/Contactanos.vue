<template>
<div>
    <header class="cocina">     
        <img src="../assets/6.jpg" alt="">
            <div>
                <h2>Agradecimientos</h2>
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Voluptate laboriosam est cum voluptates nobis temporibus molestiae. Dolor, provident ex
                 reiciendis nemo doloribus quae recusandae perferendis asperiores cum. Similique, reprehenderit doloribus?</p>
                <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Harum, praesentium tempora. Ab voluptas quo excepturi exercitationem commodi qui dolor
                 quidem consequuntur! Dicta officia provident alias eum tempora? Nostrum, aut dolorem.</p>
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Pariatur architecto id, explicabo reprehenderit eveniet minima culpa. Tempore fugiat 
                error dicta quaerat minima, atque voluptatem deserunt, ratione voluptatum omnis perferendis aut.</p>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quas officia sit saepe possimus neque explicabo exercitationem ad dolorem, magnam voluptatum
                 totam amet sequi aliquid debitis ipsa perferendis molestias perspiciatis itaque.</p>
            </div>
    </header>
    <section class="color">
            <div class="display">
            <div data-aos="zoom-in-down">
                <div class="chef">
                    <img src="../assets/chef1.jpg" alt="">
                    <div>
                    <h3>Chef 1</h3>
                    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit</p>
                    </div>
                </div>
            </div>
            <div data-aos="zoom-in-down">
                <div class="chef">
                    <img src="../assets/chef2.jpg" alt="">
                    <div>
                    <h3>Chef 2</h3>
                    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit</p>
                    </div>
                </div>
            </div>
            <div data-aos="zoom-in-down">
                <div class="chef">
                    <img src="../assets/chef3.jpg" alt="">
                    <div>
                    <h3>Chef 3</h3>
                    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit</p>
                    </div>
                </div>
            </div>
            </div>
    </section>
    </div>
</template>

<script>
export default {
    name: 'Contactanos'
}
</script>

<style>
@media only screen and (min-width:561px){
.cocina img{
  height: 60rem;
  padding: 5rem;
}
.cocina{
    display: flex;
    justify-content: space-between;
    padding: 6rem ;
}

.color{
    background-image: url(../assets/15.jpg);
    height: 100vh;
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center center;
    background-attachment: fixed;
}
.chef{
   -webkit-box-shadow: -29px -9px 32px -11px rgba(0,0,0,0.75);
-moz-box-shadow: -29px -9px 32px -11px rgba(0,0,0,0.75);
box-shadow: -29px -9px 32px -11px rgba(0,0,0,0.75);
}
.chef{
  text-align: center;
  font-size: 4rem;
  background-color: #fffefecc;
  padding: 2rem;
  margin: 0rem 4rem;
}
.chef h3::after{
  content: ''; /*preguntar como se pone en el centro*/
        display: block;
        height: 0.3rem;
        width: 8rem;
        background-color: #534f4f;
        margin-left: 10rem;
}
.chef p{
  text-align: center;
  margin: 0rem 4rem 4rem 4rem;
}
.chef img{
  height:20rem;
}

}

@media only screen and (max-width:560px){
    .contact img{
    height: 40rem;
    padding-top: 5rem;
}
.cocina{
    display:flex;
  flex-direction: column;
  align-items: center;
    padding-top: 5rem;
}
.cajita h2{
    font-size: 2rem;
    text-align: center
}
.cajita p{
    margin: 1rem 3rem;
}
.color{
    background-image: url(../assets/15.jpg);
    height: 100vh;
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center center;
}
.display{
    padding: 1rem;
}
.chef{
-webkit-box-shadow: -29px -9px 32px -11px rgba(0,0,0,0.75);
-moz-box-shadow: -29px -9px 32px -11px rgba(0,0,0,0.75);
box-shadow: -29px -9px 32px -11px rgba(0,0,0,0.75);
}
.display{
  padding-top:3rem;
}
.chef{
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.chef{
  color: #534f4f;
  background-color: #fffefecc;
  padding: 0rem 1rem;
  margin: 2rem 1rem;
}
.chef h3{
  text-align: center;
  font-size: 3rem;
  font-family: 'Gotu', sans-serif;
  margin:0rem;
}

.chef p{
  text-align: justify;
  padding: 0rem 1rem;
}
.chef img{  
  height: 10rem;
}
.social ul li{
    margin: 0rem 1rem;
    list-style: none;
    color: rgb(141, 137, 137);
    display: flex;
    justify-content: space-between;
    flex-direction: column;
    
}
.social ul li p{
    font-size: 0.5rem;
}
.social ul {
    display: flex;
    justify-content: space-between;
    padding-top: 1rem;
}
.mundo{
    display: flex;
    justify-content: space-between;
    flex-direction: column-reverse;
}
.mundo h2{
    font-size: 2rem;
}
.lado{
    text-align: center;
}
.lado p{
    text-align: center;
    font-size: 1rem;
}
.iconify{
    text-align: center;
    color: rgb(141, 137, 137);
    font-size: 3rem
}
}
</style>