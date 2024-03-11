# formularios.html

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exercícios</title>
</head>
<body>
    <h1>Pesquisa de Satisfação</h1>
    <h2>Dados pessoais:</h2>
    <form action="pesquisa_satisfacao.html" method="post">

        <p>
            <label for="name">Nome:</label>
            <input type="text" name="name" id="name" placeholder="Digite aqui">
        </p>
        <p>
            <label for="e-mail">E-mail:</label>
            <input type="email" name="e-mail" id="e-mail" placeholder="Digite aqui">
        </p>
        <p>
            <label for="telefone">Telefone:</label>
            <input type="number" name="telefone" id="telefone" placeholder="(DD) 9 XXXX-XXXX">
        </p>

        <h2>Dados de Pesquisa</h2>

        <p> 
            Nível de Satisfação com a empresa: 
            <label for="">1</label>
            <input type="radio" name="empresa" id="">
            <label for="">2</label>
            <input type="radio" name="empresa" id="">
            <label for="">3</label>
            <input type="radio" name="empresa" id="">
            <label for="">4</label>
            <input type="radio" name="empresa" id="">
            <label for="">5</label>
            <input type="radio" name="empresa" id="">
            <label for="">6</label>
            <input type="radio" name="empresa" id="">
            <label for="">7</label>
            <input type="radio" name="empresa" id="">
            <label for="">8</label>
            <input type="radio" name="empresa" id="">
            <label for="">9</label>
            <input type="radio" name="empresa" id="">
            <label for="">10</label>
            <input type="radio" name="empresa" id="">
        </p>

        <p>
            Nível de Satisfação no atendimento prestado:
            <label for="">1</label>
            <input type="radio" name="atendimento" id="">
            <label for="">2</label>
            <input type="radio" name="atendimento" id="">
            <label for="">3</label>
            <input type="radio" name="atendimento" id="">
            <label for="">4</label>
            <input type="radio" name="atendimento" id="">
            <label for="">5</label>
            <input type="radio" name="atendimento" id="">
            <label for="">6</label>
            <input type="radio" name="atendimento" id="">
            <label for="">7</label>
            <input type="radio" name="atendimento" id="">
            <label for="">8</label>
            <input type="radio" name="atendimento" id="">
            <label for="">9</label>
            <input type="radio" name="atendimento" id="">
            <label for="">10</label>
            <input type="radio" name="atendimento" id="">
        </p>

        <p>
            Depertamento do atendimento:
            <select name="departamento" id="">
                <option value="">SELECIONE...</option>
                <option value="">Suporte</option>
                <option value="">Comercial</option>
                <option value="">Retenção</option>
                <option value="">Cobrança</option>
                <option value="">Implantação</option>
            </select>
        </p>

        <p>
            <input type="checkbox" name="resposta" id="">
            <label for="">Eu autorizo compartilhar minhas respostas com terceiros</label>
        </p>

        <input type="submit" value="Enviar">
    </form>
</body>
</html>
