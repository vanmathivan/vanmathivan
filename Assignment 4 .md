doctype html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <meta 4http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="description" content="Example Consulting Pvt.Ltd" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="https://use.fontawesome.com/44da50e13f.css">
</head>
<style>
    .row {
        overflow: auto;
    }

    .col {
        float: left;
        width:15%;
        margin-right:10%;
        
    }
    .col:nth-child(4n){
        margin:0;
    }

    #img-pro {
        width: 200px;
    }

    #img-365 {
        width: 200px;
    }

    #img-edge {
        width: 200px;
    }

    #img-ovel {
        width: 200px;
    }

    a {
        text-decoration: underline;
        color:royalblue;
    }
    
</style>

<body>
    <div class="row">
        <div class="col">
            <img src="pro.jpeg" id="img-pro" />
            <h1>Surface Laptop Go</h1>
            <p>Make the most every day with the sleek style and performance
                of our lightest surface laptop.
            </p>

            <p> <a href="https://www.microsoft.com/en-in/" class="shopnow >">shop now ></a></p>
        </div>

        <div class="col">
            <img src="365.jpeg" id="img-365" />
            <h1>Microsoft 365</h1>
            <p>Premium Office apps,extra cloud storage,advanced security,and more-all in one convenient
                subscription. </p>
            <p> <a href="https://www.microsoft.com/en-in/" class="shopnow ">For up to 6 people ></a></p>
            <p> <a href="https://www.microsoft.com/en-in/" class="shopnow ">For 1 Person></a></p>
        </div>
        <div class="col">
            <img src="edge.jpeg" id="img-edge" />
            <h1>Xbox Game Pass Ultimate</h1>
            <p> Xbox Live Gold and over 100 high-quality console and PC games.Play
                together with friends and discover your next favourite game.
            </p>
            
            <p> <a href="https://www.microsoft.com/en-in/" class="shopnow ">Download now ></a></p>
        </div>
        <div class="col">
            <img src="ovel.jpeg" id="img-ovel" />
            <h1>Xbox Game Pass Ultimate</h1>
            <p>Lorem ipsum dolor si t amet consecuter adipiscing elit.Dolor,quasi dicta rem ea,vitae,laudantium
                doloremque
                correupti nulla asperiores,quos dolorum sunt tenetur maiores
            </p>
            <p> <a href="https://www.microsoft.com/en-in/" class="shopnow ">Join now ></a></p>
        </div>
    </div>

</body>

</html>
