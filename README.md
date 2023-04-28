# Website-Creation

## HTML CODE:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Cafe Kaelish</title>
    <link rel="stylesheet" href="styles.css">
    <link href='https://fonts.googleapis.com/css?family=Alegreya' rel='stylesheet'>
    <link href='https://fonts.googleapis.com/css?family=Alegreya Sans SC' rel='stylesheet'>
    <link href='https://fonts.googleapis.com/css?family=Gruppo' rel='stylesheet'>
</head>
<body>
    <div class="wallpaper">
    <img src="wall6.jpg" id="bgwall" style="height: 100%; width: 100%;">
        <img src="logo.png" class="mid logo" style="height: 150px; width: 150px;">
        <h2 class=" mid title">Famous for its Rarity, Perfect Flavour.</h2>
        <h3 class="mid aroma">Intense Aroma & Balanced Taste</h3>
        <img src="cof2.png" class="mid coffee" style="height: 250px; width: 250px;">
        <p class="mid roast">DARK ROAST</p>
        <p class="mid roastinfo">Duls aute irure dolor in <br>&emsp;&emsp;reprehenderit <br> in volupt ate vellt essets</p>
        <img src="lattefin.png" class="mid latte" style="height: 300px; width: 350px;">
        <p class="mid cup">Exceeding the Standard<p class="mid whitecup">as the</p></p>
        <p class="mid whitecup1"> Best Coffee in the World</p>
        <p class="mid est">Est. 1993</p>
        <p class="mid desc">In the majestic Blue Mountains of Jamaica grows the <br>world's finest coffee. At elevations higher than 2000 ft <br>above sea level, the rich soil and continuous rainfall<br> combine to create conditions perfect for cultivating<br> the world's most distinguished brew, Kaelish Coffee.</p>
        <button class="mid history">OUR HISTORY</button>
        <p class="mid info">Kaelish Coffee company exceeds the standard in what is already known <br>as the best coffee in the world.</p>
        <p class="mid info1">" Jamaican Blue Mountain Coffee "</p>
        <button class="mid products">BROWSE OUR PRODUCTS</button>
        <img src="cof2.png" class="mid finalprod" style="height: 300px; width: 300px;">
    </div>
    <div class="footer"></div>
</body>
</html>
```

## CSS STYLESHEET:

```
body{
    margin: 0;
}
.wallpaper{
    height: 1650px;
    width: 99vw;
    background: rgb(0, 0, 0);
    overflow: hidden;
}
#bgwall{
    
    object-fit: cover;
    opacity: 0.2;
    
}


.mid{
    position: absolute;
    top: 11%;
    left: 50%;
    transform: translate(-50%, -50%);
}

.logo{
    opacity: 0.7;
}

.title{
    color: #d1cece;
    font-family: Georgia, 'Times New Roman', Times, serif;
    font-weight: lighter;
    margin-top: 8%;
}

.aroma{
    color: #d1cece;
    font-family: 'Alegreya Sans SC';
    font-weight: lighter;
    margin-top: 10%;
}

.coffee{
    margin-top: 23%;
}
.roast{
    font-family: 'Alegreya Sans SC';
    color: #d3b134;
    top: 335px;
    left: 570px;
    font-size: 20px;
    opacity: 0.7;
}

.roastinfo{
    font-family: 'Alegreya';
    color: #d1cece;
    top: 385px;
    left: 575px;
    font-size: 15px;
}

.latte{
    opacity: 0.7;
    top: 770px;
    left: 520px;
}

.cup{
    font-family: Georgia, 'Times New Roman', Times, serif;
    color: #d3b134;
    top: 650px;
    left: 850px;
    font-size: 22px;
    font-weight: lighter;
    opacity: 0.7;
}

.whitecup{
    font-family: Georgia, 'Times New Roman', Times, serif;
    color: #f2f0f0;
    top: 653px;
    left: 1000px;
    font-size: 20px;
    font-weight: lighter;
}

.whitecup1{
    font-family: Georgia, 'Times New Roman', Times, serif;
    color: #f2f0f0;
    top: 685px;
    left: 843px;
    font-size: 20px;
    font-weight: lighter;
}

.est{
    font-family: 'Alegreya';
    color: #d3b134;
    top: 720px;
    left: 763px;
    font-size: 15px;
    opacity: 0.7;
}

.desc{
    font-family: 'Gruppo';
    color: #d1cece;
    top: 780px;
    left: 930px;
    text-align: justify;
}

.history{
    top: 125%;
    left: 783px;
    padding: 15px;
    padding: 10px;
    font-size: 13px;
    background-color:transparent;
    color: #d1cece;
    border: 1px solid #d1cece;
    font-family: 'Alegreya Sans SC';
    cursor: pointer;
}

.history:hover{
    background-color: #a49356;
}

.info{
    text-align: center;
    color: #d1cece;
    font-family: 'Alegreya';
    top: 1000px;
    font-size:larger ;
}

.info1{
    text-align: center;
    color: #d3b134;
    opacity: 0.9;
    font-family: 'Alegreya Sans SC';
    top: 1045px;
    font-size:larger ;
}

.products{
    top: 160%;
    left: 755px;
    padding: 15px;
    padding: 10px;
    font-size: 13px;
    background-color:#a49356;
    color: #d1cece;
    border: 1px solid #d1cece;
    font-family: 'Alegreya Sans SC';
    cursor: pointer;
}

.products:hover{
    background-color: transparent;
}

.finalprod{
    margin-top: 85%;
}

.footer{
    text-align: center;
    color: rgb(52, 12, 90);
    text-align: center;
    font-size: x-large;
  }
```

## OUTPUT:

![websiteout](https://user-images.githubusercontent.com/93427086/235195878-9d5acf9d-87f7-46a0-bd64-104e758df11c.png)


