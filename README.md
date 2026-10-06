# Bharat-spices-
E commerce 
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="description" content="BHARATH SPICES - Wholesale spices and dry fruits for retail shop holders.">
<title>BHARATH SPICES | Wholesale Spices & Dry Fruits</title>

<style>
*{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth}
body{
font-family:Arial,sans-serif;
background:#fff8e7;
color:#2b211b;
line-height:1.6
}
:root{
--red:#7a1f1f;
--gold:#d4a017;
--green:#356b3c;
--cream:#fff8e7;
--dark:#2b211b;
}

header{
position:sticky;
top:0;
z-index:1000;
background:#fffdf8;
border-bottom:1px solid #ead9b8;
display:flex;
align-items:center;
justify-content:space-between;
padding:10px 5%;
gap:20px
}

.logo{
width:65px;
height:65px;
border-radius:50%;
object-fit:cover;
border:2px solid var(--gold)
}

nav{
display:flex;
gap:20px;
align-items:center
}

nav a{
text-decoration:none;
color:var(--red);
font-weight:bold;
font-size:14px
}

.whatsapp{
background:var(--red);
color:white!important;
padding:12px 18px;
border-radius:30px
}

.hero{
min-height:650px;
padding:70px 7%;
display:grid;
grid-template-columns:1fr 1fr;
align-items:center;
gap:50px
}

.eyebrow{
color:var(--green);
font-size:13px;
font-weight:bold;
letter-spacing:2px;
text-transform:uppercase
}

h1{
font-family:Georgia,serif;
font-size:clamp(42px,6vw,72px);
line-height:1;
color:var(--red);
margin:15px 0
}

h2{
font-family:Georgia,serif;
font-size:clamp(30px,4vw,45px);
color:var(--red);
margin-bottom:15px
}

.hero p{
font-size:19px;
max-width:650px;
color:#66574b
}

.buttons{
display:flex;
gap:12px;
flex-wrap:wrap;
margin:25px 0
}

.btn{
display:inline-block;
padding:14px 22px;
border-radius:30px;
text-decoration:none;
font-weight:bold;
cursor:pointer;
border:0
}

.primary{
background:var(--red);
color:white
}

.secondary{
border:2px solid var(--red);
color:var(--red)
}

.hero-image{
height:480px;
border-radius:35px;
background:
linear-gradient(rgba(80,20,10,.2),rgba(212,160,23,.2)),
url("https://images.unsplash.com/photo-1596040033229-a9821ebd058d?auto=format&fit=crop&w=1000&q=85")
center/cover
}

.trust{
color:var(--green);
font-weight:bold;
font-size:14px
}

section{
padding:75px 7%
}

.heading{
max-width:750px;
margin:auto auto 35px;
text-align:center
}

.heading p{
color:#66574b
}

.tools{
max-width:1200px;
margin:0 auto 25px;
display:flex;
gap:10px;
flex-wrap:wrap
}

.search,.filter{
padding:14px 18px;
border:1px solid #ead9b8;
border-radius:30px;
background:white;
outline:none
}

.search{
flex:1;
min-width:220px
}

.filter{
color:var(--red);
font-weight:bold
}

.products{
max-width:1250px;
margin:auto;
display:grid;
grid-template-columns:repeat(4,1fr);
gap:20px
}

.card{
background:#fff;
border:1px solid #ead9b8;
border-radius:20px;
overflow:hidden;
box-shadow:0 8px 25px rgba(0,0,0,.06)
}

.photo{
height:180px;
background:
linear-gradient(135deg,#ead9b8,#fff1cf);
display:flex;
align-items:center;
justify-content:center;
text-align:center;
color:var(--red);
font-weight:bold;
font-size:13px
}

.card-body{
padding:18px
}

.category{
color:var(--green);
font-size:11px;
font-weight:bold;
text-transform:uppercase
}

.card h3{
color:var(--red);
font-family:Georgia,serif;
font-size:20px;
margin:5px 0
}

.card p{
font-size:13px;
color:#66574b;
min-height:50px
}

.price{
color:var(--green);
font-size:18px;
font-weight:bold;
margin-top:8px
}

.sheet{
font-size:11px;
color:#776657;
font-weight:bold
}

.qty{
display:flex;
align-items:center;
justify-content:center;
gap:12px;
margin:12px 0
}

.qty button{
width:32px;
height:32px;
border-radius:50%;
border:1px solid #ead9b8;
background:white;
color:var(--red);
font-size:18px;
cursor:pointer
}

.add{
width:100%;
padding:11px;
border:0;
border-radius:25px;
background:var(--red);
color:white;
font-weight:bold;
cursor:pointer
}

.band{
background:#fff1d3
}

.columns{
max-width:1100px;
margin:auto;
display:grid;
grid-template-columns:1fr 1fr;
gap:40px;
align-items:center
}

.box{
background:white;
padding:30px;
border-radius:22px;
border:1px solid #ead9b8
}

.check{
display:block;
margin:12px 0;
color:var(--green);
font-weight:bold
}

.features{
max-width:1200px;
margin:auto;
display:grid;
grid-template-columns:repeat(4,1fr);
gap:20px
}

.feature{
background:white;
padding:25px;
border-radius:20px;
border-top:4px solid var(--gold)
}

.feature h3{
color:var(--red)
}

.final{
background:var(--red);
text-align:center;
color:white
}

.final h2{
color:white
}

.final p{
color:#f8e8cf;
max-width:700px;
margin:0 auto 25px
}

.final .btn{
background:var(--gold);
color:#21180f
}

footer{
background:#241613;
color:#eadcc2;
text-align:center;
padding:30px;
font-size:13px
}

.cart-button{
position:fixed;
right:18px;
bottom:18px;
z-index:100;
background:var(--red);
color:white;
border:0;
padding:15px 20px;
border-radius:30px;
font-weight:bold;
cursor:pointer;
box-shadow:0 8px 25px rgba(0,0,0,.3)
}

.badge{
background:var(--gold);
color:#222;
border-radius:20px;
padding:3px 7px;
margin-left:5px
}

.modal{
display:none;
position:fixed;
inset:0;
background:rgba(0,0,0,.7);
z-index:2000;
align-items:flex-end;
justify-content:center
}

.modal.open{
display:flex
}

.modal-box{
background:var(--cream);
width:min(700px,100%);
max-height:85vh;
overflow:auto;
padding:30px;
border-radius:25px 25px 0 0
}

.close{
float:right;
border:0;
background:none;
font-size:25px;
color:var(--red);
cursor:pointer
}

.cart-row{
display:flex;
justify-content:space-between;
padding:13px 0;
border-bottom:1px solid #ead9b8
}

@media(max-width:1000px){
.products{grid-template-columns:repeat(3,1fr)}
.features{grid-template-columns:repeat(2,1fr)}
nav{display:none}
}

@media(max-width:750px){
.hero{
grid-template-columns:1fr;
padding:50px 5%
}
.hero-image{height:350px}
.columns{grid-template-columns:1fr}
section{padding:55px 5%}
}

@media(max-width:600px){
.products{grid-template-columns:repeat(2,1fr);gap:12px}
.photo{height:150px}
.card h3{font-size:17px}
.card p{font-size:12px}
.features{grid-template-columns:1fr}
}

@media(max-width:430px){
.products{grid-template-columns:1fr}
.logo{width:55px;height:55px}
}
</style>
</head>

<body>

<header>
<a href="#home">
<img
class="logo"
src="https://via.placeholder.com/150/FFF8E7/7A1F1F?text=BHARATH+SPICES"
alt="BHARATH SPICES">
</a>

<nav>
<a href="#home">Home</a>
<a href="#products">Products</a>
<a href="#wholesale">Wholesale</a>
<a href="#delivery">Delivery</a>
<a href="#about">About</a>
<a href="#contact">Contact</a>
<a class="whatsapp"
href="https://wa.me/917032978091?text=Hello%20BHARATH%20SPICES%2C%20I%20am%20a%20shop%20owner%20and%20want%20to%20enquire%20about%20bulk%20supply."
target="_blank">
WhatsApp
</a>
</nav>
</header>

<section class="hero" id="home">

<div>
<div class="eyebrow">
BHARATH SPICES · Sri Mylaralingeshwara Traders
</div>

<h1>Quality Spices & Dry Fruits for Your Business</h1>

<p>
Reliable wholesale supply for retail shop holders,
with convenient local delivery.
</p>

<div class="buttons">
<a class="btn primary" href="#products">View Products</a>

<a class="btn secondary"
href="https://wa.me/917032978091?text=Hello%20BHARATH%20SPICES%2C%20I%20am%20a%20shop%20owner%20and%20want%20to%20enquire%20about%20bulk%20supply."
target="_blank">
WhatsApp Enquiry
</a>
</div>

<div class="trust">
Quality Products • Reliable Supply • Local Delivery
</div>
</div>

<div class="hero-image"></div>

</section>

<section id="products">

<div class="heading">
<div class="eyebrow">Wholesale Catalogue</div>
<h2>Spices, Dry Fruits & Combos</h2>
<p>
Bulk supply for retail shop holders.
Orders are handled by sheet, not individual packs.
</p>
</div>

<div class="tools">
<input
id="search"
class="search"
type="search"
placeholder="Search products..."
oninput="filterProducts()">

<select id="filter" class="filter" onchange="filterProducts()">
<option value="all">All Products</option>
<option value="spices">Spices</option>
<option value="dry fruits">Dry Fruits</option>
<option value="combos">Combos</option>
</select>
</div>

<div class="products" id="productsGrid"></div>

</section>

<section class="band" id="wholesale">

<div class="columns">

<div>
<div class="eyebrow">For Retail Shop Holders</div>
<h2>Wholesale Supply for Your Shop</h2>

<p>
BHARATH SPICES is focused on connecting shop holders
with affordable bulk supplies of spices, dry fruits
and useful food combos.
</p>

<br>

<a class="btn primary"
href="https://wa.me/917032978091?text=Hello%20BHARATH%20SPICES%2C%20I%20am%20a%20shop%20owner%20and%20want%20to%20enquire%20about%20bulk%20supply."
target="_blank">
Enquire Now
</a>
</div>

<div class="box">
<h3 style="color:#7a1f1f">Why Shop Holders Choose Us</h3>

<span class="check">✓ Bulk sheet supply</span>
<span class="check">✓ Quality products</span>
<span class="check">✓ Affordable wholesale focus</span>
<span class="check">✓ Local delivery</span>
<span class="check">✓ Easy WhatsApp ordering</span>
</div>

</div>
</section>

<section id="delivery">

<div class="columns">

<div>
<div class="eyebrow">Delivery</div>
<h2>Local Delivery Made Easy</h2>

<p>
Bulk orders can be delivered locally.
Contact us on WhatsApp to confirm availability
for your area and order.
</p>

<br>

<a class="btn primary"
href="https://wa.me/917032978091?text=Hello%20BHARATH%20SPICES%2C%20please%20let%20me%20know%20about%20local%20delivery%20availability."
target="_blank">
Ask About Delivery
</a>
</div>

<div class="box">
<h3 style="color:#356b3c">LOCAL DELIVERY</h3>
<p>
Contact us to confirm delivery availability,
bulk quantity and order details.
</p>
</div>

</div>
</section>

<section class="band" id="about">

<div class="heading">
<div class="eyebrow">About BHARATH SPICES</div>
<h2>Built Around Shop Holders</h2>
<p>
Sri Mylaralingeshwara Traders operates under the
BHARATH SPICES name with a focus on wholesale supply
for retail shop holders.
</p>
</div>

<div class="features">

<div class="feature">
<h3>Quality</h3>
<p>Quality-focused spices and dry fruits.</p>
</div>

<div class="feature">
<h3>Wholesale</h3>
<p>Bulk supply designed for shop requirements.</p>
</div>

<div class="feature">
<h3>Affordable</h3>
<p>Wholesale-focused pricing for business buyers.</p>
</div>

<div class="feature">
<h3>Delivery</h3>
<p>Convenient local delivery for bulk orders.</p>
</div>

</div>
</section>

<section class="final" id="contact">

<div class="eyebrow" style="color:#f5d87b">
CONTACT BHARATH SPICES
</div>

<h2>Ready to Stock Your Shop?</h2>

<p>
Send us your bulk requirement on WhatsApp.
We'll discuss product availability, quantity,
pricing and delivery.
</p>

<a class="btn"
href="https://wa.me/917032978091?text=Hello%20BHARATH%20SPICES%2C%20I%20am%20a%20shop%20owner%20and%20want%20to%20enquire%20about%20bulk%20supply."
target="_blank">
💬 WhatsApp 7032978091
</a>

</section>

<footer>
<strong>BHARATH SPICES</strong><br>
Sri Mylaralingeshwara Traders<br><br>
Quality Spices. Trusted Supply. Local Delivery.
</footer>

<button class="cart-button" onclick="openCart()">
🛒 Bulk Enquiry
<span class="badge" id="cartCount">0</span>
</button>

<div class="modal" id="modal">

<div class="modal-box">

<button class="close" onclick="closeCart()">×</button>

<div class="eyebrow">Bulk Order</div>
<h2>Your Enquiry</h2>

<div id="cartItems"></div>

<br>

<button class="btn primary"
style="width:100%"
onclick="sendWhatsApp()">
Send Enquiry on WhatsApp
</button>

</div>
</div>

<script>

const products = [

{
name:"Cardamom / Elaichi",
category:"Spices",
price:50,
description:"Aromatic cardamom for tea, sweets and cooking."
},

{
name:"Cumin / Jeera",
category:"Spices",
price:50,
description:"Fragrant cumin seeds for Indian cooking."
},

{
name:"Coriander Seeds",
category:"Spices",
price:50,
description:"Whole coriander seeds with a warm aroma."
},

{
name:"Fennel / Saunf",
category:"Spices",
price:50,
description:"Aromatic fennel seeds."
},

{
name:"Mustard Seeds",
category:"Spices",
price:50,
description:"Classic mustard seeds for cooking and pickles."
},

{
name:"Fenugreek / Methi",
category:"Spices",
price:50,
description:"Traditional fenugreek seeds."
},

{
name:"Black Pepper",
category:"Spices",
price:50,
description:"Bold aromatic peppercorns."
},

{
name:"Cloves / Laung",
category:"Spices",
price:50,
description:"Aromatic cloves for biryani and masala."
},

{
name:"Cinnamon / Dalchini",
category:"Spices",
price:50,
description:"Fragrant cinnamon for cooking and sweets."
},

{
name:"Star Anise",
category:"Spices",
price:50,
description:"Sweet-spiced whole spice."
},

{
name:"Bay Leaves / Biryani Leaves",
category:"Spices",
price:50,
description:"Aromatic leaves for rice dishes."
},

{
name:"Dry Red Chilli",
category:"Spices",
price:50,
description:"Dried chilli for heat and colour."
},

{
name:"Turmeric / Haldi",
category:"Spices",
price:50,
description:"Everyday turmeric spice."
},

{
name:"Chilli Powder",
category:"Spices",
price:50,
description:"Versatile chilli powder."
},

{
name:"Coriander Powder",
category:"Spices",
price:50,
description:"Ground coriander for curries."
},

{
name:"Garam Masala",
category:"Spices",
price:50,
description:"Warming Indian spice blend."
},

{
name:"Biryani Masala",
category:"Spices",
price:50,
description:"Aromatic blend for biryani."
},

{
name:"Biriyani Combo",
category:"Combos",
price:65,
description:"Combo for biriyani preparation."
},

{
name:"Pulav Combo",
category:"Combos",
price:65,
description:"Combo for pulav preparation."
},

{
name:"Almonds",
category:"Dry Fruits",
price:60,
description:"Quality almonds for shops and recipes."
},

{
name:"Cashews",
category:"Dry Fruits",
price:60,
description:"Crunchy cashews for snacks and cooking."
},

{
name:"Dry Dates",
category:"Dry Fruits",
price:60,
description:"Naturally sweet dried dates."
},

{
name:"Dry Grapes / Raisins",
category:"Dry Fruits",
price:60,
description:"Sweet dried grapes."
},

{
name:"Cashew & Grapes Combo",
category:"Dry Fruits",
price:60,
description:"Popular cashew and dry grapes combination."
}

];

let cart = {};

function renderProducts(list=products){

const grid=document.getElementById("productsGrid");

grid.innerHTML=list.map((p,index)=>`

<div class="card">

<div class="photo">
PRODUCT PHOTO<br>
<small>Original photo can be added later</small>
</div>

<div class="card-body">

<div class="category">${p.category}</div>

<h3>${p.name}</h3>

<p>${p.description}</p>

<div class="price">₹${p.price} / sheet</div>

<div class="sheet">1 sheet = 10 packs</div>

<div class="qty">

<button onclick="changeQty(${index},-1)">−</button>

<span id="qty-${index}">1</span>

<button onclick="changeQty(${index},1)">+</button>

</div>

<button class="add" onclick="addProduct(${index})">
Add to Bulk Enquiry
</button>

</div>
</div>

`).join("");

}

function changeQty(index,value){

const element=document.getElementById("qty-"+index);

let qty=parseInt(element.innerText)+value;

if(qty<1) qty=1;

element.innerText=qty;

}

function addProduct(index){

const qty=parseInt(
document.getElementById("qty-"+index).innerText
);

const product=products[index];

if(cart[product.name]){
cart[product.name]+=qty;
}else{
cart[product.name]=qty;
}

updateCart();

openCart();

}

function updateCart(){

let total=0;

Object.values(cart).forEach(qty=>total+=qty);

document.getElementById("cartCount").innerText=total;

}

function openCart(){

const modal=document.getElementById("modal");

modal.classList.add("open");

const container=document.getElementById("cartItems");

const names=Object.keys(cart);

if(names.length===0){

container.innerHTML=
"<p>Your enquiry is empty. Add products from the catalogue.</p>";

return;

}

container.innerHTML=names.map(name=>{

const product=products.find(p=>p.name===name);
const qty=cart[name];
const amount=product.price*qty;

return `

<div class="cart-row">

<div>
<strong>${name}</strong><br>
${qty} sheet(s)
</div>

<strong>₹${amount}</strong>

</div>

`;

}).join("");

}

function closeCart(){

document.getElementById("modal")
.classList.remove("open");

}

function sendWhatsApp(){

const names=Object.keys(cart);

if(names.length===0){

alert("Please add products first.");

return;

}

let message=
"Hello BHARATH SPICES / Sri Mylaralingeshwara Traders,%0A%0A"+
"I am a shop owner and would like to enquire about bulk supply.%0A%0A"+
"Bulk requirement:%0A";

let total=0;

names.forEach(name=>{

const product=products.find(p=>p.name===name);
const qty=cart[name];
const amount=product.price*qty;

total+=amount;

message+=
"- "+name+
" — "+qty+
" sheet(s) — ₹"+amount+
"%0A";

});

message+=
"%0AEstimated product total: ₹"+total+
"%0A%0APlease confirm availability and delivery details.";

window.open(
"https://wa.me/917032978091?text="+message,
"_blank"
);

}

function filterProducts(){

const search=
document.getElementById("search")
.value
.toLowerCase();

const category=
document.getElementById("filter")
.value
.toLowerCase();

const filtered=products.filter(p=>{

const matchesSearch=
p.name.toLowerCase().includes(search) ||
p.description.toLowerCase().includes(search);

const matchesCategory=
category==="all" ||
p.category.toLowerCase()===category;

return matchesSearch && matchesCategory;

});

renderProducts(filtered);

}

renderProducts();

</script>

</body>
</html>
