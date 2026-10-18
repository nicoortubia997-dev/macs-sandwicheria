%%html
<link href="https://fonts.googleapis.com/css2?family=Kaushan+Script&family=Oswald:wght@500&family=Stardos+Stencil:wght@700&family=Playfair+Display:wght@700&family=Pacifico&display=swap" rel="stylesheet">

<style>
:root { --fondo:#1a1a1d; --crema:#f5f1e8; --gris:#8a8a8f; }

.sitio { background:var(--fondo); color:var(--crema); font-family:'Oswald',sans-serif; border-radius:10px; overflow:hidden; }
.sitio h1,.sitio h2,.sitio h3,.sitio p,.sitio li { color:var(--crema); }

/* PORTADA tipo mural */
.portada { position:relative; height:480px; overflow:hidden; border-bottom:2px solid var(--crema); }
.portada span { position:absolute; color:var(--crema); white-space:nowrap; }
.sello  { font-family:'Stardos Stencil',serif; letter-spacing:3px; }
.cafe   { font-family:'Kaushan Script',cursive; }
.palos  { font-family:'Oswald',sans-serif; }
.serif  { font-family:'Playfair Display',serif; }
.pincel { font-family:'Pacifico',cursive; }
.dibujo { filter:grayscale(1) brightness(2.2); opacity:.85; }

/* Título al centro de la portada */
.titulo { position:absolute; top:50%; left:50%; transform:translate(-50%,-50%); text-align:center; background:rgba(26,26,29,.88); border:2px solid var(--crema); border-radius:14px; padding:18px 26px; }
.titulo h1 { font-family:'Stardos Stencil',serif; font-size:44px; letter-spacing:3px; margin:0; }
.titulo h2 { font-family:'Kaushan Script',cursive; font-size:30px; margin:6px 0 0; font-weight:normal; }

/* CONTENIDO */
.contenido { padding:24px; }
.contenido h3 { font-family:'Kaushan Script',cursive; font-size:32px; margin:0 0 8px; font-weight:normal; }
.contenido p  { font-family:'Playfair Display',serif; font-size:18px; line-height:1.5; }
.envio { display:inline-block; border:2px solid var(--crema); border-radius:30px; padding:6px 18px; font-size:20px; margin-bottom:14px; }

.carta { display:grid; grid-template-columns:repeat(auto-fit,minmax(260px,1fr)); gap:14px; margin-top:12px; }
.tarjeta { border:2px solid var(--crema); border-radius:12px; padding:14px; }
.tarjeta h4 { font-family:'Stardos Stencil',serif; font-size:22px; letter-spacing:2px; margin:0 0 6px; color:var(--crema); }
.tarjeta p  { font-size:15px; margin:0; color:var(--gris); }
</style>

<div class="sitio">

  <div class="portada">
    <span class="cafe"   style="top:5%;  left:5%;  font-size:44px; transform:rotate(-8deg);">Coffee</span>
    <span class="sello"  style="top:4%;  left:38%; font-size:34px; transform:rotate(-3deg);">WELCOME</span>
    <span class="palos"  style="top:8%;  left:78%; font-size:22px; transform:rotate(6deg);">espresso</span>
    <span class="pincel" style="top:20%; left:60%; font-size:26px; transform:rotate(-5deg);">Time house</span>
    <span class="palos"  style="top:24%; left:6%;  font-size:48px;">COCOA</span>
    <span class="serif"  style="top:78%; left:6%;  font-size:24px; transform:rotate(4deg);">good morning</span>
    <span class="cafe"   style="top:84%; left:62%; font-size:30px; transform:rotate(-6deg);">Home Made</span>
    <span class="sello"  style="top:88%; left:36%; font-size:24px; transform:rotate(-8deg);">PREMIUM</span>
    <span class="palos"  style="top:70%; left:80%; font-size:24px; letter-spacing:4px;">BEANS</span>
    <span class="dibujo" style="top:8%;  left:22%; font-size:44px;">☕</span>
    <span class="dibujo" style="top:55%; left:8%;  font-size:42px; transform:rotate(-15deg);">🥐</span>
    <span class="dibujo" style="top:60%; left:84%; font-size:42px; transform:rotate(20deg);">🥐</span>
    <span class="dibujo" style="top:80%; left:22%; font-size:44px;">☕</span>

    <div class="titulo">
      <h1>CONFITERÍA ONCE</h1>
      <h2>El Sabor del Encuentro</h2>
    </div>
  </div>

  <div class="contenido">
    <h3>Rico, bonito y barato</h3>
    <div class="envio">Envío a domicilio sin cargo</div>
    <p>Pedinos la carta, hacé tu pedido de forma rápida y segura. No te quedes sin tu menú del día. Envío a toda Salta capital.</p>
    <p>Todas nuestras comidas, salsas y panes son caseros, no tenemos nada artificial. Confitería Once, tu casa está acá.</p>

    <h3 style="margin-top:22px;">Nuestra carta sector Hamburguesa</h3>
    <div class="carta">
      <div class="tarjeta"><h4>Hamburguesa BYPAT</h4><p>Pan de papa, queso muzzarela, panceta ahumada, salsa tártara, alioli, barbacoa y ketchup.</p></div>
      <div class="tarjeta"><h4>Hamburguesa BIG ONCE</h4><p>Pan de papa, queso cheddar, lechuga, pepinillos y salsa big once.</p></div>
      <div class="tarjeta"><h4>Hamburguesa TRIPLE MONSTRUOSA</h4><p>Pan de papa, triple medallón de 110 g, triple cheddar, triple panceta, ketchup, cebolla morada, huevo a caballo, alioli y barbacoa.</p></div>
      <div class="tarjeta"><h4>Hamburguesa MEXICANA</h4><p>Pan de papa, queso cheddar, guacamole, lechuga, nachos y salsa de ají.</p></div>
      <div class="tarjeta"><h4>Hamburguesa BLUE</h4><p>Pan de papa, queso azul, champiñones, panceta ahumada, rúcula y salsa alioli.</p></div>
      <div class="tarjeta"><h4>Hamburguesa GRIGA</h4><p>Pan de papa, cheddar, panceta ahumada, cebolla morada, cebolla caramelizada y barbacoa.</p></div>
      <div class="tarjeta"><h4>Hamburguesa CLÁSICA</h4><p>Pan de papa, lechuga, tomate, muzzarela, jamón, huevo a caballo y salsa César.</p></div>

    <h3 style="margin-top:30px;">sector lomitos</h3>
    <div class="carta">
      <div class="tarjeta"><h4> lomito clasico</h4></p>pan de papa, lechuga, queso muzzarela, jamon, huevo a caballo, salsa cesar.</p></div>
      <div class="tarjeta"><h4> lomito americano</h4></p>pan de papa, cheddar, panceta ahumada, cebolla caramelizada, barbacoa.</p></div>
      <div class="tarjeta"><h4> lomito blue</h4></p>pan de papa queso azul, champiñones, panceta ahumada, rucula, salsa alioli.</p></div>
    </div>

    <h3 style="margin-top:22px;">pizzas</h3>
      <div class="tarjeta"><h4>pizza muzza</h4></p>queso muzzarela, ajie dulce, aceituna.</p></div>
      <div class="tarjeta"><h4>pizza napo</h4></p>queso muzzarela, tomate, ajie dulce, aceituna, aceite de olivar.</p></div>
      <div class="tarjeta"><h4>pizza clasica especial</h4></p>queso muzzarela, jamon, ajie dulce, aceitunas.</p></div>
      <div class="tarjeta"><h4>pizza gringa</h4></p>queso muzzarela, cheddar, panceta ahumada, cebolla morada, cebolla caramelizada, salsa barbacoa.</p></div>
      <div class="tarjeta"><h4>pizza blue</h4></p>queso muzzarela, queso azul, cebolla morada, champiñones, panceta ahumada, rucula, salsa alioli.</p></div>
      <div class="tarjeta"><h4>pizza mexicana</h4></p>queso muzzarela, cheddar, guacamole, lechuga, nachos, mauonesa de aji.</p></div>
    </div>
