
          <!DOCTYPE html><html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hotel Santa Luz</title>
    <link rel="stylesheet" href="styles.css">
    <script src="script.js" defer></script>
</head>
<body>
    <header>
        <h1>Hotel Santa Luz</h1>
        <p>Conforto e comodidade em Aparecida-SP</p>
    </header><nav>
    <ul>
        <li><a href="#sobre">Sobre Nós</a></li>
        <li><a href="#fotos">Fotos</a></li>
        <li><a href="#reserva">Reserva</a></li>
        <li><a href="#localizacao">Localização</a></li>
        <li><a href="#depoimentos">Depoimentos</a></li>
    </ul>
</nav>

<section id="sobre">
    <h2>Sobre Nós</h2>
    <p>O Hotel Santa Luz oferece hospedagem confortável e bem localizada...</p>
</section>

<section id="fotos">
    <h2>Galeria de Fotos</h2>
    <div class="carousel">
        <img src="imagem1.jpg" alt="Hotel">
        <img src="imagem2.jpg" alt="Quarto">
        <img src="imagem3.jpg" alt="Restaurante">
    </div>
</section>

<section id="reserva">
    <h2>Reserva</h2>
    <form>
        <label for="checkin">Check-in:</label>
        <input type="date" id="checkin" name="checkin">
        
        <label for="checkout">Check-out:</label>
        <input type="date" id="checkout" name="checkout">
        
        <button type="button" onclick="compartilharWhatsApp()">Enviar Reserva</button>
    </form>
</section>

<section id="localizacao">
    <h2>Localização</h2>
    <iframe src="https://www.google.com/maps/embed?..." width="600" height="450"></iframe>
</section>

<section id="depoimentos">
    <h2>O que dizem sobre nós</h2>
    <p>"Hotel muito bom, fomos de excursão..." - Cliente Satisfeito</p>
    <p>"Muito aconchegante, próximo da igreja..." - Outra avaliação</p>
</section>

<footer>
    <a href="https://wa.me/message/YUBI7UX65V5DH1" target="_blank">WhatsApp</a>
    <a href="https://www.facebook.com/share/1HhbHjHCXW/" target="_blank">Facebook</a>
    <a href="https://www.instagram.com/hotel_santaluz?igsh=enJxYjM4Z2l5b3p0" target="_blank">Instagram</a>
</footer>

</body>
</html>