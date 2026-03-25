<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jardinería LTC | Mantenimiento, Podas y Desbroces</title>
    <style>
        :root { --verde: #76b82a; --oscuro: #1a1a1a; }
        body { font-family: 'Segoe UI', sans-serif; margin: 0; text-align: center; color: var(--oscuro); line-height: 1.6; }
        header { 
            background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url('https://images.unsplash.com/photo-1558905619-171426efb452?auto=format&fit=crop&q=80&w=1500');
            background-size: cover; padding: 60px 20px; color: white;
        }
        .logo-tarjeta { max-width: 90%; width: 350px; border-radius: 10px; box-shadow: 0 10px 20px rgba(0,0,0,0.3); border: 3px solid white; }
        .servicios { display: flex; justify-content: center; gap: 20px; flex-wrap: wrap; padding: 40px 20px; background: #f4f4f4; }
        .card { background: white; padding: 20px; border-radius: 10px; box-shadow: 0 4px 6px rgba(0,0,0,0.1); width: 250px; border-top: 5px solid var(--verde); }
        .card h3 { color: var(--verde); margin-top: 0; }
        .contacto { padding: 50px 20px; }
        .btn-whatsapp { background: #25d366; color: white; padding: 18px 30px; text-decoration: none; border-radius: 50px; font-weight: bold; font-size: 1.2em; display: inline-block; }
    </style>
</head>
<body>

    <header>
        <img src="ltc.jpg" alt="Jardinería LTC" class="logo-tarjeta">
        <p style="font-size: 1.2em; margin-top: 15px;">Servicios profesionales de jardinería</p>
    </header>

    <section class="servicios">
        <div class="card"><h3>🌿 Mantenimiento</h3><p>Cuidado integral de jardines y zonas verdes.</p></div>
        <div class="card"><h3>✂️ Podas</h3><p>Especialistas en poda de árboles y setos.</p></div>
        <div class="card"><h3>🚜 Desbroces</h3><p>Limpieza de terrenos y fincas.</p></div>
    </section>

    <section class="contacto">
        <h2>¿Necesitas un presupuesto?</h2>
        <p style="font-size: 1.4em;"><strong>📞 629 44 20 13</strong></p>
        <a href="https://wa.me/34629442013" class="btn-whatsapp">Contactar por WhatsApp</a>
    </section>

    <footer style="padding: 20px; background: #eee;">&copy; 2024 Jardinería LTC</footer>

</body>
</html>
