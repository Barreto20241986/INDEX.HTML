#index.html<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hotel Minimalista</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; text-align: center; }
        header { background: #333; color: white; padding: 20px; font-size: 24px; }
        section { padding: 20px; }
        .gallery img { width: 100%; max-width: 300px; margin: 10px; }
        .map iframe { width: 100%; height: 300px; border: none; }
        form input, form button { padding: 10px; margin: 5px; }
    </style>
</head>
<body>
    <header>Hotel Minimalista</header>
    
    <section>
        <h2>Sobre Nós</h2>
        <p>Bem-vindo ao nosso hotel! Conforto e tranquilidade esperam por você.</p>
    </section>
    
    <section class="gallery">
        <h2>Galeria de Fotos</h2>
        <img src="foto1.jpg" alt="Foto do Hotel">
        <img src="foto2.jpg" alt="Foto do Quarto">
    </section>
    
    <section>
        <h2>Reserva</h2>
        <form>
            <input type="text" placeholder="Seu Nome" required>
            <input type="email" placeholder="Seu Email" required>
            <input type="date" required>
            <button type="submit">Reservar</button>
        </form>
    </section>
    
    <section class="map">
        <h2>Localização</h2>
        <iframe src="https://www.google.com/maps/embed?..." width="600" height="450"></iframe>
    </section>
</body>
</html>