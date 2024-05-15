<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Cadastro de Clientes</title>
</head>
<body>

<h2>Cadastro de Clientes</h2>

<form action="processar_formulario.php" method="POST">
    <label for="nome">Nome Completo:</label><br>
    <input type="text" id="nome" name="nome" required><br><br>

    <label for="cpf">CPF:</label><br>
    <input type="text" id="cpf" name="cpf" pattern="[0-9]{11}" required><br><br>

    <label for="email">Endereço de E-mail:</label><br>
    <input type="email" id="email" name="email" required><br><br>

    <label for="data_nascimento">Data de Nascimento:</label><br>
    <input type="date" id="data_nascimento" name="data_nascimento" required><br><br>

    <input type="submit" value="Cadastrar Cliente">
</form>

</body>
</html>

