# catequese.github.io
  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
    }

    body{
      font-family: Arial, Helvetica, sans-serif;
      background: linear-gradient(135deg,#0f172a,#1e293b);
      min-height:100vh;
      padding:30px;
      display:flex;
      align-items:center;
      justify-content:center;
      color:#fff;
    }

    .container{
      width:100%;
      max-width:1100px;
      background: rgba(255,255,255,0.08);
      backdrop-filter: blur(12px);
      border:1px solid rgba(255,255,255,0.15);
      border-radius:20px;
      overflow:hidden;
      box-shadow:0 10px 30px rgba(0,0,0,0.35);
    }

    .topo{
      padding:40px;
      text-align:center;
      background: rgba(255,255,255,0.05);
      border-bottom:1px solid rgba(255,255,255,0.1);
    }

    .logo{
      width:80px;
      height:80px;
      margin:0 auto 20px;
      border-radius:50%;
      background:#2563eb;
      display:flex;
      align-items:center;
      justify-content:center;
      font-size:32px;
      font-weight:bold;
    }

    h1{
      font-size:2rem;
      margin-bottom:10px;
    }

    .subtitulo{
      color:#cbd5e1;
      font-size:1rem;
    }

    .conteudo{
      padding:25px;
    }

    iframe{
      width:100%;
      height:1000px;
      border:none;
      border-radius:15px;
      background:#fff;
    }

    .info{
      margin-top:20px;
      background:rgba(37,99,235,0.15);
      border:1px solid rgba(96,165,250,0.3);
      padding:18px;
      border-radius:12px;
      color:#dbeafe;
    }

    .info h3{
      margin-bottom:10px;
      color:#fff;
    }

    .rodape{
      text-align:center;
      padding:20px;
      color:#94a3b8;
      font-size:14px;
      border-top:1px solid rgba(255,255,255,0.08);
    }

    @media(max-width:768px){

      body{
        padding:15px;
      }

      .topo{
        padding:25px;
      }

      h1{
        font-size:1.5rem;
      }

      iframe{
        height:1200px;
      }
    }
  </style>
</head>
<body>

  <div class="container">

    <div class="topo">

      <div class="logo">
        📷
      </div>

      <h1>Envio de Imagens</h1>

      <p class="subtitulo">
        Preencha o formulário abaixo e anexe suas imagens com segurança.
      </p>

    </div>

    <div class="conteudo">

      <!-- SUBSTITUA PELO LINK DO SEU GOOGLE FORMS -->
      <iframe 
        src="[[[https://docs.google.com/forms/d/e/SEU_FORMULARIO/viewform?embedded=true](https://docs.google.com/forms/d/e/1FAIpQLSeu0u3qLKD4I5ipR6NVN2OIZ42HOCZziEYk-KkS5a3ydiDwGw/viewform?usp=header)](https://forms.gle/t3eXzPsEhhzzPQxNA)](https://forms.gle/t3eXzPsEhhzzPQxNA)">
        Carregando…
      </iframe>

      <div class="info">
        <h3>Informações importantes</h3>

        <p>
          ✔ Permitido upload de imagens JPG, PNG e PDF.<br><br>

          ✔ O Google pode solicitar login para envio dos arquivos.<br><br>

          ✔ Todos os arquivos enviados ficam armazenados no Google Drive.
        </p>
      </div>

    </div>

    <div class="rodape">
      Desenvolvido para coleta segura de arquivos e imagens
    </div>

  </div>

</body>
</html>
