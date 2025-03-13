<!DOCTYPE html>
<html lang="en">
<head> 
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> the page deticated to seals :> </title>
    <style>
        .container {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(100px, 1fr));
            grid-gap: 10px;
        }
        .gif-item {
            width: 100px;
            height: 100px;
        }
    </style>
</head>
<body>


    <h1>SEALLLLZZZZZZ XD</h1> 
    <div class="container">
        <!-- This script will insert the GIF 3600 times -->
        <script>
            const container = document.querySelector('.container');
            for(let i = 0; i < 3600; i++) {
                const img = document.createElement('img');
                img.src = 'https://images.steamusercontent.com/ugc/868491890539623031/2DA4535A11D3E0148A174ED15A28A33D984612CC/?imw=5000&imh=5000&ima=fit&impolicy=Letterbox&imcolor=%23000000&letterbox=false.gif'; // Replace with your GIF URL
                img.alt = 'GIF';
                img.className = 'gif-item';
                container.appendChild(img);
            }
        </script>
    </div>
    THANK U FOR VISITING MY SIGMA SITE IF YOUR READING THIS, YOUR A ALPHA :>
    my discord: otaku_owo pdf files dni ^-^
    <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Visitor Counter</title>
</head>
<body>
  <p>You are visitor number: <span id="visitor-count"></span></p>

  <script>

    let visitorCount = localStorage.getItem('visitorCount') || 0;
    visitorCount++;
    localStorage.setItem('visitorCount', visitorCount);

  
    document.getElementById('visitor-count').textContent = visitorCount;
  </script>
</body>
</html>
