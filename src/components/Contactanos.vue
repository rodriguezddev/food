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
@media only screen and (min-width:861px){
.cocina img{
  width: 40%;
  padding: 4rem 4rem 0rem 0rem ;
}
.cocina{
    display: flex;
    justify-content: space-between;
    padding: 6rem ;
}
.cocina p{
    width: 90%;
    margin:0% 10% 5% 0%
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
  font-size: 2rem;
  background-color: #fffefecc;
  padding: 2rem ;
  margin: 15% 10% ;
}
.chef p{
  text-align: center;
  margin: 0rem 4rem 4rem 4rem;
  
}
.chef img{
  width: 100%;
}

}

@media only screen and (max-width:860px){
    .contact img{
    width:20%;
    padding: 5rem;
}
.cocina{
    display:flex;
    flex-direction: column;
    align-items: center;
    padding-top: 5rem;
    margin: 10% 50%;
}
.cajita h2{
    font-size: 2rem;
    text-align: center
}

.color{
    background-image: url(../assets/15.jpg);
    height: 100vh;
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center center;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.chef{ 
  display: flex;
  justify-content: center;
  color: #534f4f;
  background-color: #fffefecc;
  padding: 0rem 1rem;
  margin: 5% 2%;
}
.chef h3{
  text-align: center;
  font-size: 2rem;
  font-family: 'Gotu', sans-serif;
  margin:0rem;
}

.chef p{
  text-align: justify;
  padding: 0rem 1rem;
}
.chef img{
width: 25%;
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