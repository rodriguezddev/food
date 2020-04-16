<template>
    <div>
        <footer class="social">
        <div class="mundo">
            <ul>
                <li><span class="iconify" data-icon="foundation:social-facebook" data-inline="false"></span>
                <p>Food World</p>
                </li>
                <li><span class="iconify" data-icon="foundation:social-instagram" data-inline="false"></span>
                <p>@FoodWorld</p>
                </li>
                <li><span class="iconify" data-icon="foundation:social-google-plus" data-inline="false"></span>
                <p>FW@gmail.com</p>
                </li>
            </ul>
            <div class="lado">
                <h2>FoodWorld</h2>
                <p>El buen sabor del mundo</p>
            </div>
        </div>
            <div class="pie">
                <p>Daniela Rodriguez &copy;</p>
            </div>
        </footer>
    </div>
</template>

<script>
export default {
    name: 'Footer'
}
</script>
<style >
@media only screen and (min-width:561px){
.social ul li{
    list-style: none;
    color: rgb(141, 137, 137);
    display: flex;
    justify-content: space-between;
}
.social ul {
    display: flex;
    justify-content: space-between;
    padding-top: 2rem;
}

.mundo{
    display: flex;
    justify-content: space-between;
}
.mundo h2{
    font-size: 3rem;
}
.lado{
    margin-right: 3rem;
}
.iconify{
    text-align: center;
    color: rgb(141, 137, 137);
    font-size: 4rem
}
.pie{
  background-color: #ffffff;
  margin: 0rem; 
  padding: 1rem 0rem;
}
.pie p{
  text-align: center;
  margin: 0;
  color:black;
}
}
@media only screen and (max-width:560px){
    .social ul li{
    margin: 0rem 1rem;
    list-style: none;
    color: rgb(141, 137, 137);
    display: flex;
    align-items: center;
    flex-direction: column; 
    text-align: center;
    
}
.social ul li p{
    font-size: 1rem;

}
.social ul {
    display: flex;
    justify-content: space-between;
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
    color: rgb(141, 137, 137);
    font-size: 4rem;
}
.pie{
  background-color: #ffffff;
  padding: 1rem 0rem;
}
.pie p{
  text-align: center;
  margin: 0;
  color:black;
}
}
</style>