<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>scroll</title>
</head>
<style>
    *{
        margin: 0%;
        padding: 0%;
        box-sizing: border-box;
    }
    body{
        background-color: black;
    }
    .container{
    margin-top: 10%;   
        height: 80%;
            display: flex;
            margin: 2%;
            gap: 20px;
            overflow-x: auto;
            scrollbar-width: none;
            scroll-snap-type: x mandatory;
            scroll-behavior: smooth;
    }
    .card1,.card2,.card3,.card4,.card5{
        background-color: blueviolet;
        opacity: 0.5;
        display: flex;
        justify-content: center;
        align-items: center;
        gap: 20px;
        width: 20%;
        height: 50%;
        border-radius: 20px;
        scroll-snap-align:centre ; 
         transition: transform 0.3s ease;
    }
      .box:hover{
        margin-top: 2%;
    background-color:blueviolet;
     border-radius: 20px;
    height: 80%;
    width: 35%;
     transform: scale(1.1);
    opacity: 1;
    }
    input{
      background-color: greenyellow;
      position:absolute;
       border: none;
      top: 80%;
      left: 30%;
      padding:10px 60px;
        font-weight: 600;
    }
    .Previous{
       background-color: rgb(229, 153, 112);
      position:absolute;
      border: none;
      top: 80%;
      left: 50%;
      padding:10px 50px;
      font-weight: 600;
    }
</style>
<body>
    <div class="container">
        <div class="card1 box"></div>
        <div class="card2 box"></div>
        <div class="card3 box"></div>
        <div class="card4 box"></div>
        <div class="card5 box"></div>
    </div>
    <input type="button" value="Next">
     <input class="Previous" type="button" value="Previous">
</body>
</html>
