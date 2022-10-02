<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Bootstrap demo</title>
    <link
    rel="stylesheet"
      href="https://pro.fontawesome.com/releases/v5.10.0/css/all.css"
      integrity="sha384-AYmEC3Yw5cVb3ZcuHtOA93w35dYTsvhLPVnYs9eStHfGJvOvKxVfELGroGkvsg+p"
      crossorigin="anonymous"
    />
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.1/dist/js/bootstrap.bundle.min.js" integrity="sha384-u1OknCvxWvY5kfmNBILK2hRnQC3Pr17a+RTT6rIHI7NnikvbZlHgTPOOmMi466C8" crossorigin="anonymous"></script>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-iYQeCzEYFbKjA/T2uDLTpkwGzCiq6soy8tYaI1GyVh/UjpbCx/TYkiZhlZB6+fzT" crossorigin="anonymous">
    <style>
      *{
        margin: 0;
        padding: 0;
      }

      body{
        min-height: 100vh;
        display: grid;
        place-items: center;
        background-color: #07112e;
      }

      #message{
        height: 100vh;
        width: 100%;
        font-size: 50px;
        display: flex;
        align-items: center;
        justify-content: center;
        color: white;
      }

    </style>
</head>
  <body>
  <i id="message" class="fas fa-envelope" onclick="changeIcon(this)" aria-hidden="true" data-bs-toggle="modal" data-bs-target="#staticBackdrop"></i>



  
  <!-- Modal -->
  <div class="modal fade" id="staticBackdrop" data-bs-backdrop="static" data-bs-keyboard="false" tabindex="-1" aria-labelledby="staticBackdropLabel" aria-hidden="true">
    <div class="modal-dialog">
      <div class="modal-content">
        <div class="modal-header">
          <h3 class="modal-title" id="staticBackdropLabel">Pesan (1)</h3>
        </div>
        <div class="modal-body">
          Walah walah, kita ketemu lagi niccchh, sekarang Linda tolong tekan ikon whatsapp ini dongg
          <a href="https://api.whatsapp.com/send/?phone=6281247665625&text=%20Hai%20Yuda%20Ganteng">
            <i class="fab fa-whatsapp"></i>
          </a>
        </div>
      </div>
    </div>
  </div>
  <script>
        alert("Halo Linda, thankyou ya udh mau buka link yang saia kirim, coba kamu tekan ikon amplopnya")
        let changeIcon = function(icon) {
          icon.classlist.toggle('fa-envelope-open')
        }
        changeIcon = (icon) => icon.classList.toggle('fa-envelope-open')
  </script>
    
  </body>
</html>
