<!DOCTYPE html><html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hotel Santa Luz</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Hotel Santa Luz</h1>
        <nav>
            <ul>
                <li><a href="#sobre">Sobre Nós</a></li>
                <li><a href="#fotos">Fotos</a></li>
                <li><a href="#depoimentos">Depoimentos</a></li>
                <li><a href="#reserva">Reserva</a></li>
                <li><a href="#contato">Contato</a></li>
            </ul>
        </nav>
    </header><section id="sobre">
    <h2>Sobre Nós</h2>
    <p>O Hotel Santa Luz oferece hospedagem confortável em Aparecida-SP, a poucos minutos do Santuário Nacional.</p>
    <ul>
        <li>3 minutos do Santuário Nacional</li>
        <li>3 minutos da Igreja Antiga</li>
        <li>1 minuto da rodoviária e feira</li>
    </ul>
</section>

<section id="fotos">
    <h2>Galeria de Fotos</h2>
    <div class="carousel">
        <img src="foto1.jpg" alt="Foto do hotel">
        <img src="foto2.jpg" alt="Foto do quarto">
    </div>
</section>

<section id="depoimentos">
    <h2>Depoimentos</h2>
    <blockquote>"Hotel muito bom, fomos de excursão da cidade de Varginha. Quartos limpinhos e comida gostosa!"</blockquote>
    <blockquote>"Muito aconchegante, próximo da igreja e das lojas. Atendimento excelente!"</blockquote>
</section>

<section id="reserva">
    <h2>Calendário de Reservas</h2>
    <p>Selecione as datas desejadas e compartilhe no WhatsApp.</p>
    <input type="date"> <button onclick="compartilharReserva()">Compartilhar no WhatsApp</button>
</section>

<section id="contato">
    <h2>Contato</h2>
    <p>Email: hotelsantaluz@gmail.com</p>
    <p>Telefone: (12) 99618-0635 | (12) 98148-0525</p>
</section>

<footer>
    <a href="https://wa.me/message/YUBI7UX65V5DH1" class="whatsapp-button">WhatsApp</a>
    <a href="https://www.facebook.com/share/1HhbHjHCXW/">Facebook</a>
    <a href="https://www.instagram.com/hotel_santaluz?igsh=enJxYjM4Z2l5b3p0">Instagram</a>
</footer>

<script>
    function compartilharReserva() {
        const data = document.querySelector('input[type=date]').value;
        if (data) {
            const link = `https://wa.me/message/YUBI7UX65V5DH1?text=Quero%20reservar%20para%20${data}`;
            window.open(link, '_blank');
        } else {
            alert('Escolha uma data antes de compartilhar!');
        }
    }
</script>

</body>
</html>