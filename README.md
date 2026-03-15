<!DOCTYPE html>
<html lang="sq">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Alloyedge Jewelry</title>
<style>
    body {
        margin: 0;
        font-family: 'Arial', sans-serif;
        background: #fff0f5; /* pastel rozë */
        color: #333;
    }

    header {
        background: #cdeac0; /* pastel jeshile */
        text-align: center;
        padding: 50px 20px;
        transition: background 0.3s;
    }
    header h1 {
        margin: 0;
        font-size: 2rem;
        color: #ff69b4; /* rozë e theksuar */
    }

    section {
        padding: 30px 20px;
        text-align: center;
        transition: transform 0.3s;
    }
    section h2 {
        font-size: 1.5rem;
        margin-bottom: 20px;
        color: #6b8e23; /* jeshile e errët */
    }
    section p {
        font-size: 1rem;
        line-height: 1.5;
        max-width: 400px;
        margin: 0 auto 20px auto;
    }

    /* Koleksioni cards */
    .cards {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
        gap: 15px;
        margin-top: 20px;
    }
    .card {
        background: #ffe4e1; /* pastel rozë e lehtë */
        border-radius: 15px;
        padding: 20px;
        min-height: 150px;
        box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        transition: transform 0.3s, box-shadow 0.3s;
    }
    .card:hover {
        transform: translateY(-5px);
        box-shadow: 0 8px 12px rgba(0,0,0,0.2);
    }

    .btn-order {
        display: inline-block;
        padding: 15px 30px;
        background-color: #ff69b4; /* rozë butoni */
        color: white;
        font-weight: bold;
        text-decoration: none;
        border-radius: 25px;
        transition: background 0.3s, transform 0.3s;
    }
    .btn-order:hover {
        background-color: #ff1493;
        transform: scale(1.05);
    }

    footer {
        text-align: center;
        padding: 20px;
        background: #cdeac0; /* pastel jeshile */
        font-size: 0.9rem;
    }
</style>
</head>
<body>

<header>
    <h1>Alloyedge Jewelry</h1>
</header>

<section>
    <h2>Rreth Nesh</h2>
    <p>Alloyedge Jewelry prezanton bizhuteri moderne dhe elegante për femra. Bizhuteri që nxjerr në pah vetëbesimin, bukurinë dhe stilin tuaj unik.</p>
</section>

<section>
    <h2>Koleksioni Ynë</h2>
    <div class="cards">
        <div class="card">Varëse</div>
        <div class="card">Byzylykë</div>
        <div class="card">Vathë</div>
        <div class="card">Unaza</div>
    </div>
</section>

<section>
    <h2>Porosit Tani</h2>
    <a href="https://www.instagram.com/alloyedge.jewelry" class="btn-order" target="_blank">Order Now</a>
</section>

<footer>
    Instagram: @alloyedge.jewelry | TikTok: @alloyedge.jewelry | Facebook: @alloyedge | X: @alloyedge
</footer>

</body>
</html>
