# Formulario-tecnologias
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cadastro</title>
</head>
<body>
 
  <div>
    <h1>Cadastro De DEVs</h1>
    <p>Complete as suas informações</p>
    <br>
  </div>  

<form>
    <fieldset>
        <div>
        <label>Nome</label>
        <input type="text" name="nome" id="nome">
        </div>

<div>
    <label>Sobrenome</label>
    <input type="text" name="Sobrenome" id="Sobrenome">
</div>
</fieldset>

<div>
    <label>Email</label>
    <input type="email" name="email" id="email">
</div>

<div>
<label>De Qual Lado Da Aplicação Você Desenvolve</label>
<label>
    <input type="radio" name="devweb" value="Front-End" checked>Front-End
</label>
<label>
  <input type="radio" name="devweb" value="Back-End">Back-End
</label>
<label>
    <input type="radio" name="Devweb" value="Full-Stack">Full-Stack
</label>
</div>
<br>
<div>
    <label>Senioridade</label>
    <select id="senioridade">
        <option selected disabled value="">Selecione</option>
        <option>Junior</option>
        <option>Pleno</option>
        <option>Sênior</option>
    </select>
</div>

<br>
<fieldset>
    <div>
        <label>Selecione as tecnologias que utiliza</label><br><br>
        <input type="checkbox" id="tecnologia1" name="tecnologia1" value="HTML">
        <label for="tecnologia1">HTML</label>
        <input type="checkbox" id="tecnologia2" name="tecnologia2" value="CSS">
        <label for="tecnologia2">CSS</label>
        <input type="checkbox" id="tecnologia3" name="tecnologia3" value="Javascript">
        <label for="tecnologia3">Javascript</label>
        <input type="checkbox" id="tecnologia4" name="tecnologia4" value="PHP">
        <label for="tecnologia4">PHP</label>
        <input type="checkbox" id="tecnologia5" name="tecnologia5" value="C#">
        <label for="tecnologia5">C#</label>
        <input type="checkbox" id="tecnologia6" name="tecnologia6" value="Python">
        <label for="tecnologia6">Python</label>
        <input type="checkbox" id="tecnologia7" name="tecnologia7" value="Java">
        <label for="tecnologia7">Java</label>
    </div>
</fieldset>

<div>
    <br>
    <label>Conte um pouco da sua experiência</label>
    <textarea row="6" style="width:26em" id="experiência" name="experiência"></textarea>
</div>

<button type="submit">Concluido!</button>

</form>
</body>
</html>
