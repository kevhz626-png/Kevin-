# Kevin-<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Guitars Nitro</title>

<style>
    *{
        margin:0;
        padding:0;
        box-sizing:border-box;
        font-family: Arial, sans-serif;
    }

    body{
        background:#111;
        color:white;
    }

    header{
        background:#000;
        padding:20px;
        display:flex;
        justify-content:space-between;
        align-items:center;
        border-bottom:2px solid #ff9800;
    }

    header h1{
        color:#ff9800;
        letter-spacing:2px;
    }

    nav a{
        color:white;
        text-decoration:none;
        margin-left:20px;
        transition:0.3s;
    }

    nav a:hover{
        color:#ff9800;
    }

    .hero{
        height:70vh;
        background:url('https://images.unsplash.com/photo-1510915361894-db8b60106cb1?q=80&w=1600&auto=format&fit=crop') center/cover;
        display:flex;
        justify-content:center;
        align-items:center;
        text-align:center;
        padding:20px;
    }

    .hero-text{
        background:rgba(0,0,0,0.6);
        padding:30px;
        border-radius:15px;
    }

    .hero-text h2{
        font-size:50px;
        margin-bottom:15px;
        color:#ff9800;
    }

    .hero-text p{
        font-size:20px;
    }

    .container{
        padding:50px 8%;
    }

    .section-title{
        text-align:center;
        margin-bottom:40px;
        font-size:35px;
        color:#ff9800;
    }

    .products{
        display:grid;
        grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
        gap:30px;
    }

    .card{
        background:#1b1b1b;
        border-radius:15px;
        overflow:hidden;
        transition:0.3s;
        border:1px solid #333;
    }

    .card:hover{
        transform:translateY(-8px);
        box-shadow:0 0 15px rgba(255,152,0,0.5);
    }

    .card img{
        width:100%;
        height:250px;
        object-fit:cover;
    }

    .card-content{
        padding:20px;
    }

    .card-content h3{
        margin-bottom:10px;
        color:#ff9800;
    }

    .price{
        font-size:22px;
        margin:10px 0;
    }

    .not-sale{
        color:#ff4d4d;
        font-weight:bold;
    }

    button{
        width:100%;
        padding:12px;
        border:none;
        background:#ff9800;
        color:black;
        font-weight:bold;
        border-radius:8px;
        cursor:pointer;
        transition:0.3s;
    }

    button:hover{
        background:white;
    }

    footer{
        background:#000;
        text-align:center;
        padding:20px;
        margin-top:40px;
        border-top:2px solid #ff9800;
    }
</style>
</head>

<body>

<header>
    <h1>🎸 Guitar Zone</h1>

    <nav>
        <a href="#">Inicio</a>
        <a href="#">Guitarras</a>
        <a href="#">Modelos</a>
        <a href="#">Contacto</a>
    </nav>
</header>

<section class="hero">
    <div class="hero-text">
        <h2>El sonido que cambia todo</h2>
        <p>Explora guitarras increíbles con un diseño moderno y elegante.</p>
    </div>
</section>

<section class="container">

    <h2 class="section-title">Modelos Destacados</h2>

    <div class="products">

        <div class="card">
            <img src="https://images.unsplash.com/photo-1525201548942-d8732f6617a0?q=80&w=1200&auto=format&fit=crop">
            
            <div class="card-content">
                <h3>Fender Stratocaster</h3>
                <p>Sonido clásico y diseño legendario.</p>
                <div class="price">$24,999 MXN</div>
                <p class="not-sale">No disponible para venta</p>
                <button>Ver modelo</button>
            </div>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1511379938547-c1f69419868d?q=80&w=1200&auto=format&fit=crop">
            
            <div class="card-content">
                <h3>Gibson Les Paul</h3>
                <p>Potencia y elegancia en cada nota.</p>
                <div class="price">$39,500 MXN</div>
                <p class="not-sale">No disponible para venta</p>
                <button>Ver modelo</button>
            </div>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1516280440614-37939bbacd81?q=80&w=1200&auto=format&fit=crop">
            
            <div class="card-content">
                <h3>Ibanez RG</h3>
                <p>Perfecta para riffs rápidos y metal.</p>
                <div class="price">$18,700 MXN</div>
                <p class="not-sale">No disponible para venta</p>
                <button>Ver modelo</button>
            </div>
        </div>

    </div>

</section>

<footer>
    <p>🎶 Guitar Zone | Página de demostración | 2026</p>
</footer>

</body>
</html>
