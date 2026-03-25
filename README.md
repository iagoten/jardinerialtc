<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jardinería LTC | Mantenimiento y Podas</title>
    <style>
        :root { --verde: #76b82a; --oscuro: #2c3e50; }
        body { font-family: 'Helvetica Neue', Arial, sans-serif; margin: 0; text-align: center; color: var(--oscuro); background-color: #fdfdfd; }
        
        header { 
            background: white; 
            padding: 40px 20px; 
            border-bottom: 5px solid var(--verde);
        }

        /* Esto hace que tu tarjeta se vea genial como logo */
        .logo-img { 
            max-width: 400px; 
            width: 100%; 
            border-radius: 8px; 
            box-shadow: 0 4px 15px rgba(0,0,0,0.1); 
        }

        .hero {
            background: linear-gradient(rgba(0,0,0,0.4), rgba(0,0,0,0.4)), url('https://images.unsplash.com/photo-1592419044706-39796d40f98c?q=80&w=1500');
            background-size: cover;
            background-position: center;
            color: white;
            padding: 60px 20px;
            margin-bottom: 30px;
        }

        .servicios { display: flex; justify-content: center; gap: 20px; flex-wrap: wrap; padding: 20px; }
        .card { 
            background: white; border: 1px solid #eee; padding: 25px; border-radius: 12px; 
            width: 280px; transition: 0.3s; box-shadow: 0 2px 5px rgba(0,0,0,0.05);
        }
        .card:hover { transform: translateY(-5px); box-shadow: 0 10px 20px rgba(0,0,0,0.1); }
        .card h3 { color: var(--verde); margin-top: 0; font-size: 1.5em; }

        .btn-whatsapp { 
            background: #25d366; color: white; padding: 20px 40px; 
            text-decoration: none; border-radius: 50px; font-weight: bold; 
            display: inline-block; font-size: 1.3em; margin-top: 20px;
            box-shadow: 0 5px 15px rgba(37, 211, 102, 0.4);
        }
    </style>
</head>
<body>

    <header>
        <img src="ltc.jpg" alt="Jardinería LTC Logo" class="logo-img">
    </header>

    <div class="hero">
        <h2 style="font-size: 2.5em; margin: 0;">Profesionales del Jardín</h2>
        <p style="font-size: 1.2em;">Calidad, seriedad y los mejores precios</p>
    </div>

    <section class="servicios">
        <div class="card"><h3>🌿 Mantenimiento</h3><p>Cuidado de césped, abonado y limpieza general.</p></div>
        <div class="card"><h3>✂️ Podas</h3><p>Especialistas en recorte de setos y poda ornamental.</p></div>
        <div class="card"><h3>🚜 Desbroces</h3><p>Limpieza profunda de parcelas y fincas rústicas.</p></div>
    </section>

    <section style="padding: 60px 20px; background: #f9f9f9;">
        <h2>¿Hablamos de tu jardín?</h2>
        <p>Llama directamente al <strong>629 44 20 13</strong> o escríbenos:</p>
        <a href="https://wa.me/34629442013" class="btn-whatsapp">Pedir presupuesto GRATIS</a>
    </section>

    <footer style="padding: 30px; color: #999;">&copy; 2024 Jardinería LTC</footer>

</body>
</html>
