<template>
    <div>
        <TopNav></TopNav>

        <div class="container">

            <div class="main">

                <div class="Produkt">
                    <img src="../components/img/zegarek.jpg" alt="koszulka">
                    <p>200 PLN</p>
                    <button>Kup teraz</button>
                </div>

                <div class="Produkt">
                    <img src="../components/img/zegarek.jpg" alt="koszulka">
                    <p>200 PLN</p>
                    <button>Kup teraz</button>
                </div>

                <div class="Produkt">
                    <img src="../components/img/zegarek.jpg" alt="koszulka">
                    <p>200 PLN</p>
                    <button>Kup teraz</button>
                </div>

                <div class="Produkt">
                    <img src="../components/img/zegarek.jpg" alt="koszulka">
                    <p>200 PLN</p>
                    <button>Kup teraz</button>
                </div>

                <div class="Produkt">
                    <img src="../components/img/zegarek.jpg" alt="koszulka">
                    <p>200 PLN</p>
                    <button>Kup teraz</button>
                </div>

                <div class="Produkt">
                    <img src="../components/img/zegarek.jpg" alt="koszulka">
                    <p>200 PLN</p>
                    <button>Kup teraz</button>
                </div>

                <div class="Produkt">
                    <img src="../components/img/zegarek.jpg" alt="koszulka">
                    <p>200 PLN</p>
                    <button>Kup teraz</button>
                </div>

                <div class="Produkt">
                    <img src="../components/img/zegarek.jpg" alt="koszulka">
                    <p>200 PLN</p>
                    <button>Kup teraz</button>
                </div>

            </div>

            <div class="fotter">

                <div class="kolumna">
                    <h4>O firmie</h4>
                    <ul>
                        <li><a href="#">Historia</a></li>
                        <li><a href="#">Nasza misja</a></li>
                        <li><a href="#">Zespół</a></li>
                    </ul>
                </div>

                <div class="kolumna">
                    <h4>Kontakt</h4>
                    <ul>
                        <li><a href="#">Telefon</a></li>
                        <li><a href="#">Adres e-mail</a></li>
                        <li><a href="#">Formularz kontaktowy</a></li>
                    </ul>
                </div>

                <div class="kolumna">
                    <h4>Informacje</h4>
                    <ul>
                        <li><a href="#">Polityka prywatności</a></li>
                        <li><a href="#">Regulamin</a></li>
                        <li><a href="#">FAQ</a></li>
                    </ul>
                </div>

                <div class="kolumna">
                    <h4>Reklamacje</h4>
                    <ul>
                        <li><a href="#">Jak złożyc reklamację</a></li>
                        <li><a href="#">Status reklamcji</a></li>
                    </ul>
                </div>

            </div>

            <div class="kolumna2">
                <div class="kolumna3">
                    <hr>
                    <p class="text">&copy; 2023 Firma XYZ Sp. z.o.o. Wszelkie prawa zastrzeżone.</p> 
                </div>
            </div>

        </div>
    </div>
    




    

</template>

<script>

    import TopNav from '../components/TopNav.vue';


    export default {
        name: "meskie",
        components: {TopNav}
    }

</script>

<style scoped>

    .main
    {
        background-color: bisque;
        width: 100%;
        align-items: center;
        
    }
    .Produkt img
    {
    width: 180px;
    height: auto;
    margin-bottom: 10px;
    padding-top: 15px;
    }
    .Produkt p
    {
        font-size: 1.2rem;
    font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
    font-weight: bold;
    margin-bottom: 10px;
    }
    .Produkt button
    {
    background-color: #0e1102;
    color: white;
    border: none;
    padding: 10px 20px;
    border-radius: 5px;
    font-size: 1.2rem;
    cursor: pointer;
    transition: background-color 0.3s ease;
    margin-bottom: 15px;
    }
    .Produkt button:hover
    {
        background-color: #ade921;
    }
    .Produkt
    {
    margin-left: 150px;
    display: inline-block;
    }
    .fotter
    {
        background-color: black;
        display: flex;
        text-align: center;
        clear: both;
        grid-template-columns: 64px min-content 1fr min-content min-content min-content min-content 1fr min-content 64px;
        grid-template-rows: 1fr;
        padding: 40px 0;
        justify-content: center;
    }
    .container h4
    {
        margin-bottom: 20px;
        font-weight: bold;
        color: #333333;
    }
    .container ul
    {
        margin: 0;
        padding: 0;
        list-style: none;
    }
    .container ul li a
    {
        display: block;
        margin-bottom: 10px;
        color: #666666;
    }
    .container ul li:hover
    {
        color: #333333;
    }
    .container hr
    {
        margin-top: 40px;
        margin-bottom: 20px;
        border-top: 1px solid #dddddd;
    }
    .container p
    {
        margin-bottom: 0;
        color: #666666;
    }
    .kolumna
    {
        float: left;
        text-align: center;
        padding-left: 40px;
        display: block;
        width: 25%;
    }
    .kolumna3
    {
        clear: both;
        text-align: center;
        background-color: black;
        width: 100%;
    }
    .kolumna2
    {
        display: flex;
        justify-content: center;
        align-items: center;
    }
    @media screen and (min-width: 1024px) 
    {
    .fotter 
    {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 20px;
    background-color: black;
    color: white;
    font-weight: bold;
    text-align: center;
    padding: 20px;
    }
    .fotter h4 
    {
    font-size: 18px;
    margin-bottom: 10px;
    }
    .fotter ul 
    {
    list-style: none;
    margin: 0;
    padding: 0;
    font-size: 16px;
    }
    .fotter ul li 
    {
    margin-bottom: 10px;
    }
    }
    .Produkt 
    {
    margin-left: 50px;
    margin-right: 50px;
    }
    .Produkt img 
    {
    width: 100%;
    max-width: 300px;
    height: auto;
    }

@media screen and (max-width: 640px) 
{
    .fotter 
    {
    display: flex;
    flex-direction: column;
    background-color: black;
    color: white;
    text-align: center;
    padding: 20px;
    }
    .fotter h4 
    {
    font-size: 18px;
    margin-bottom: 10px;
    }
    .fotter ul 
    {
    list-style: none;
    margin: 0;
    padding: 0;
    font-size: 16px;
    }
    .fotter ul li 
    {
    margin-bottom: 10px;
    }
    .Produkt 
    {
    margin-left: 0;
    margin-right: 0;
    }
    .Produkt img 
    {
    width: 100%;
    max-width: 300px;
    height: auto;
    }
    }

</style>