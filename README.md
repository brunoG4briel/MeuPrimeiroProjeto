# MeuPrimeiroProjeto
Challenge ONE Sprint 01: Decodificador de texto com Javascript
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link rel="stylesheet" href="style.css">
    <title>Challenge_Concluído_Decodificador_Alura</title>
</head>
<body>

    <header>
        <img src="./imagens/logoAlura.png" alt="Logo da Alura">
    </header>
    
    <main>
        <section>
            <textarea class="text-area"  cols="41" rows="4" placeholder="Digite seu texto"></textarea>
    
            <div>
                <h6 class="informacao">Apenas letras minúsculas e sem acento.</h6>
            </div>
            <div class="botoes">
                <button class="btn-encriptar" onclick="btnEncriptar()">Criptografar</button>
                <button class="btn-desencriptar" onclick="btnDesencriptar()">Descriptografar</button>
            </div>
        </section>
        
        <section>
            <textarea class="mensagem"  cols="20" rows="10"></textarea>
            <button class="btn-copiar">Copiar</button>
        </section>
    </main>
    <script src="script.js"></script>
</body>
</html>
