<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Anonymous Paper</title>

<style>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    background: #000;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}

.container {
    background: #111;
    padding: 30px;
    border-radius: 15px;
    width: 350px;
    box-shadow: 0 0 25px rgba(0,0,0,0.8);
    color: white;
}

h2 {
    text-align: center;
    color: white;
}

label {
    font-weight: bold;
    margin-top: 10px;
    display: block;
    color: #ccc;
}

input, textarea, select {
    width: 100%;
    padding: 8px;
    margin-top: 5px;
    border-radius: 8px;
    border: 1px solid #333;
    background: #222;
    color: white;
    font-size: 14px;
}

textarea {
    resize: none;
    height: 80px;
}

button {
    margin-top: 15px;
    width: 100%;
    padding: 10px;
    border: none;
    border-radius: 20px;
    background: #6a11cb;
    color: white;
    font-weight: bold;
    cursor: pointer;
    transition: 0.3s;
}

button:hover {
    background: #8e2de2;
}

.pagamento {
    margin-top: 20px;
    padding-top: 10px;
    border-top: 1px solid #333;
}
</style>
</head>

<body>

<div class="container">
    <h2>🕶️ Anonymous Paper</h2>

    <label>Para quem deseja entregar:</label>
    <input type="text" id="destinatario" placeholder="Nome do destinatário">

    <label>Mensagem:</label>
    <textarea id="mensagem" placeholder="Escreva sua carta aqui..."></textarea>

    <div class="pagamento">
        <h3>💳 Pagamento</h3>

        <label>Plano:</label>
        <select id="plano">
            <option value="5">Carta Simples - R$5,00</option>
            <option value="100">Carta Premium - R$100,00</option>
        </select>

        <label>Número do Cartão:</label>
        <input type="text" id="cartao" placeholder="0000 0000 0000 0000">

        <label>Validade:</label>
        <input type="text" id="validade" placeholder="MM/AA">

        <label>CVV:</label>
        <input type="text" id="cvv" placeholder="123">
    </div>

    <button onclick="enviar()">Pagar e Enviar</button>
</div>

<script>
function enviar() {

    let destinatario = document.getElementById("destinatario").value;
    let mensagem = document.getElementById("mensagem").value;
    let cartao = document.getElementById("cartao").value;
    let cvv = document.getElementById("cvv").value;

    if(destinatario === "" || mensagem === "" || cartao === "" || cvv === ""){
        alert("Preencha todos os campos!");
        return;
    }

    alert("Pagamento aprovado! 💰\nCarta enviada com sucesso!");
}
</script>

</body>
</html>