<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Atividade prática</title>
</head>


<header>
    <h1>Página de formúlario de reserva</h1>
    <hr>
    <br><br><br>
</header>

<body>
    <section>
        <h2>Preencha o formulário corretamente</h2>
        <form method="GET" action="">

        
    <fieldset>
        

        <legend>Dados</legend>

        <label>Nome</label>
        <input type="text" name= "Nome" value="" > Preencha com seu nome completo <br><br>

        <label>E-mail</label>
        <input type="email" required name="Email"> Preenchimento de campo obrigatório <br><br>
        
        <label for=""></label>

    </fieldset><br><br><br>

    <fieldset>
     <legend>Quais serviços deseja contratar?</legend>


        <label>
            <input type="checkbox" name="passagens" value="Passagens"> Compra de passagens
        </label>

        <label>
            <br><input type="checkbox" name="hospedagem" value="Hospedagem"> Reserva de hospedagem
        </label>

        <label>
            <br><input type="checkbox" name="veiculos" value="Veículos"> Reserva de veículos
        </label>
        

    </fieldset><br><br><br>

    <fieldset>
        <legend>Forma de pagamento</legend>
        <br><input type="radio" name="formadePagamento" value="Cartão de Crédito">Cartão de crédito
        <br><input type="radio"name="formadePagamento" value="Boleto">Boleto
        <br><input type="radio"name="formadePagamento" value="Pix">Pix

    </fieldset><br><br><br>

    <fieldset>
<legend>Prazo para pagamento</legend>

<select name="prazoPagamento">
    <option value="aVista">À vista</option>
    <option value="5x">5x Sem juros</option>
    <option value="10x">10x com juros</option>



</select>

    </fieldset><br><br><br>
         
<fieldset>
    <label>Comentário</label><br>
    <textarea name="Comentário" id="" cols="30" rows="5"></textarea><br><br>
    <input type="submit" value="Enviar">
</fieldset>
    
</form>
</section>    
</body>

</html>

