# index.html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Till Hanging Chibi Tutorial</title>
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.css"/>
<style>
body{ margin:0; background:#eef8f7; font-family:Arial,sans-serif; }
h1{ text-align:center; color:#0d8b87; padding:15px; }
.swiper{ width:100%; height:auto; padding-bottom:40px; }
.swiper-slide{ display:flex; justify-content:center; align-items:center; }
.swiper-slide img{ width:95%; max-width:700px; border-radius:15px; box-shadow:0 5px 15px rgba(0,0,0,.2); }
.swiper-button-prev, .swiper-button-next { color: #0d8b87; }
</style>
</head>
<body>
<h1>Till Hanging Chibi Tutorial</h1>
<div class="swiper">
<div class="swiper-wrapper">
<div class="swiper-slide"><img src="Untitled122_20260713120029.png" alt="Till Parts"></div>
<div class="swiper-slide"><img src="2.jpg" alt="Joint Tutorial"></div>
<div class="swiper-slide"><img src="3.jpg" alt="Assembling Guide"></div>
<div class="swiper-slide"><img src="4.jpg" alt="Step 1"></div>
<div class="swiper-slide"><img src="5.jpg" alt="Step 2"></div>
<div class="swiper-slide"><img src="6.jpg" alt="Final Till"></div>
</div>
<div class="swiper-pagination"></div>
<div class="swiper-button-prev"></div>
<div class="swiper-button-next"></div>
</div>
<script src="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.js"></script>
<script>
new Swiper('.swiper',{
    pagination:{ el:'.swiper-pagination', clickable:true },
    navigation:{ nextEl:'.swiper-button-next', prevEl:'.swiper-button-prev' }
});
</script>
</body>
</html>