/* =========================
   СБРОС СТИЛЕЙ
========================= */

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background: black;
    color: white;
    overflow-x: hidden;
}


/* =========================
   HEADER
========================= */

header {
    position: fixed;
    width: 100%;
    top: 0;
    left: 0;
    background: linear-gradient(90deg, black, purple, red);
    padding: 20px;
    z-index: 1000;
    box-shadow: 0 0 20px purple;
}

.logo {
    text-align: center;
    font-size: 40px;
    color: red;
    text-shadow: 0 0 10px purple;
}

nav {
    text-align: center;
    margin-top: 10px;
}

nav a {
    color: white;
    text-decoration: none;
    margin: 0 15px;
    font-size: 18px;
    transition: 0.3s;
}

nav a:hover {
    color: red;
    text-shadow: 0 0 10px purple;
}


/* =========================
   HERO
========================= */

.hero {
    height: 100vh;
    background: linear-gradient(black, purple, black);
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    padding-top: 100px;
    text-align: center;
}

.hero h2 {
    font-size: 50px;
    margin-bottom: 20px;
    color: red;
    text-shadow: 0 0 20px purple;
}

.hero p {
    font-size: 22px;
    margin-bottom: 30px;
}

.main-btn {
    padding: 15px 40px;
    font-size: 18px;
    border: none;
    border-radius: 30px;
    background: linear-gradient(90deg, red, purple);
    color: white;
    cursor: pointer;
    transition: 0.4s;
    box-shadow: 0 0 15px red;
}

.main-btn:hover {
    transform: scale(1.1);
    box-shadow: 0 0 30px purple;
}


/* =========================
   TOP INFO
========================= */

.top {
    text-align: center;
    padding: 20px;
    background: black;
    border-top: 1px solid purple;
    border-bottom: 1px solid red;
    font-size: 18px;
}


/* =========================
   PRODUCTS
========================= */

.products {
    padding: 100px 20px;
    background: black;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 30px;
}

.brand {
    width: 100%;
    text-align: center;
    font-size: 30px;
    margin: 40px 0;
    color: red;
    text-shadow: 0 0 10px purple;
}


/* =========================
   CARD
========================= */

.card {
    width: 250px;
    background: linear-gradient(180deg, #111, black);
    border-radius: 15px;
    padding: 20px;
    text-align: center;
    border: 1px solid purple;
    transition: 0.4s;
    box-shadow: 0 0 10px black;
}

.card:hover {
    transform: translateY(-10px);
    box-shadow: 0 0 25px red;
}

.card p {
    font-size: 18px;
    margin-bottom: 15px;
}


/* =========================
   BUY BUTTON
========================= */

.buy-btn {
    padding: 10px 25px;
    border: none;
    border-radius: 25px;
    background: linear-gradient(90deg, red, purple);
    color: white;
    font-size: 16px;
    cursor: pointer;
    transition: 0.4s;
    box-shadow: 0 0 10px purple;
}

.buy-btn:hover {
    transform: scale(1.1);
    box-shadow: 0 0 20px red;
}


/* =========================
   NO STOCK
========================= */

.no-stock {
    opacity: 0.5;
    border: 1px solid red;
}


/* =========================
   CONTACT
========================= */

.contact {
    text-align: center;
    padding: 100px 20px;
    background: linear-gradient(black, purple, black);
}

.contact h2 {
    font-size: 40px;
    margin-bottom: 20px;
    color: red;
}

.contact p {
    font-size: 20px;
    margin-bottom: 30px;
}

.contact-btn,
.tg-btn {
    padding: 15px 40px;
    background: linear-gradient(90deg, red, purple);
    color: white;
    text-decoration: none;
    border-radius: 30px;
    font-size: 18px;
    transition: 0.4s;
    box-shadow: 0 0 20px purple;
}

.contact-btn:hover,
.tg-btn:hover {
    transform: scale(1.1);
    box-shadow: 0 0 30px red;
}


/* =========================
   FOOTER
========================= */

footer {
    text-align: center;
    padding: 20px;
    background: black;
    border-top: 1px solid purple;
    color: gray;
}


/* =========================
   АДАПТАЦИЯ ПОД ТЕЛЕФОН
========================= */

@media (max-width: 768px) {

    .hero h2 {
        font-size: 30px;
    }

    nav a {
        display: block;
        margin: 10px;
    }

    .products {
        flex-direction: column;
        align-items: center;
    }

    .card {
        width: 90%;
    }

}
