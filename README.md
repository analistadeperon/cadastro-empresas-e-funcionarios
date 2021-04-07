# cadastro-empresas-e-funcionarios
<!DOCTYPE html>

<html>
 <head>
 <title> Como criar um formulário completo em HTML </title>
 <meta name="description" content="Aprenda a criar um site completo que usa formulários em HTML">
 <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
 </head>

 <body>
  <h1> Bem vindo a Empresa Fantasma</h1>
  <h2> Preencha o formulário abaixo com seus dados Pessoais</h2><br />

<form action="Script_do_Formulario.javascript" method="post">

<!-- DADOS PESSOAIS FUNCIOANRIOS-->
<fieldset>
 <legend>Dados Pessoais</legend>
 <table cellspacing="10">
  <tr>
   <td>
    <label for="nome">Nome: </label>
   </td>
   <td align="left">
    <input type="text" name="email">
   </td>
   <td>
    <label for="sobrenome">Sobrenome: </label>
   </td>
   <td align="left">
    <input type="text" name="sobrenome">
   </td>
  </tr>
  <tr>
   <td>
    <label>Nascimento: </label>
   </td>
   <td align="left">
    <input type="text" name="dia" size="2" maxlength="2" value="dd">
   <input type="text" name="mes" size="2" maxlength="2" value="mm">
   <input type="text" name="ano" size="4" maxlength="4" value="aaaa">
   </td>
  </tr>
  <tr>
   <td>
    <label for="rg">RG: </label>
   </td>
   <td align="left">
    <input type="text" name="rg" size="13" maxlength="13">
   </td>
  </tr>
  <tr>
   <td>
    <label>CPF:</label>
   </td>
   <td align="left">
    <input type="text" name="cpf" size="9" maxlength="9"> - <input type="text" name="cpf2" size="2" maxlength="2">
   </td>
  </tr>
 </table>
</fieldset>

<br />
<!-- ENDEREÇO -->
<fieldset>
 <legend>Dados de Endereço</legend>
 <table cellspacing="10">

  <tr>
   <td>
    <label for="rua">Rua:</label>
   </td>
   <td align="left">
    <input type="text" name="rua">
   </td>
   <td>
    <label for="numero">Numero:</label>
   </td>
   <td align="left">
    <input type="text" name="numero" size="4">
   </td>
  </tr>
  <tr>
   <td>
    <label for="bairro">Bairro: </label>
   </td>
   <td align="left">
    <input type="text" name="bairro">
   </td>
  </tr>
  <tr>
   <td>
    <label for="Empresa">Empresa:</label>
   </td>
   <td align="left">
    <select name="Empresa">
    <option value="ac">Acre</option>
    <option value="al">Alagoas</option>
    <option value="am">Amazonas</option>
    <option value="ap">Amapá</option>
    <option value="ba">Bahia</option>
    <option value="ce">Ceará</option>
    <option value="df">Distrito Federal</option>
    <option value="es">Espírito Santo</option>
    <option value="go">Goiás</option>
    <option value="ma">Maranhão</option>
    <option value="mt">Mato Grosso</option>
    <option value="ms">Mato Grosso do Sul</option>
    <option value="mg">Minas Gerais</option>
    <option value="pa">Pará</option>
    <option value="pb">Paraíba</option>
    <option value="pr">Paraná</option>
    <option value="pe">Pernambuco</option>
    <option value="pi">Piauí</option>
    <option value="rj">Rio de Janeiro</option>
    <option value="rn">Rio Grande do Norte</option>
    <option value="ro">Rondônia</option>
    <option value="rs">Rio Grande do Sul</option>
    <option value="rr">Roraima</option>
    <option value="sc">Santa Catarina</option>
    <option value="se">Sergipe</option>
    <option value="sp">São Paulo</option>
    <option value="to">Tocantins</option>
   </select>
   </td>
  </tr>
  <tr>
   <td>


    <label for="cidade">Cidade: </label>
   </td>
   <td align="left">
    <input type="text" name="cidade">
   </td>
  </tr>
  <tr>
   <td>
    <label for="cep">CEP: </label>
   </td>
   <td align="left">
    <input type="text" name="cep" size="5" maxlength="5"> - <input type="text" name="cep2" size="3" maxlength="3">
   </td>
  </tr>
 </table>
</fieldset>
<br />


<!-- DADOS EMPRESAS-->
<fieldset>
  <legend>Dados Empresa</legend>
  <table cellspacing="10">
   <tr>
    <td>
     <label for="nome">Nome: </label>
    </td>
    <td align="left">
     <input type="text" name="email">
    </td>
    <td>
     <label for="cnpj">CNPJ: </label>
    </td>
    <td align="left">
     <input type="text" name="cnpj">
    </td>
   </tr>
   <tr>
    <td>
     <label>local: </label>
    </td>
    <td align="left">
     <input type="text" name="data" size="2" maxlength="2" value="dt">
    <input type="text" name="mes" size="2" maxlength="2" value="mm">
    <input type="text" name="ano" size="4" maxlength="4" value="aaaa">
    </td>
   </tr>
   <tr>
    <td>
     <label for="cnpj">cnpj: </label>
    </td>
    <td align="left">
     <input type="text" name="cnpj" size="13" maxlength="13">
    </td>
   </tr>
   <tr>
    <td>
     <label>nome figurativo:</label>
    </td>
    <td align="left">
     <input type="text" name="nome figurativo" size="9" maxlength="9"> - <input type="text" name="cpf2" size="2" maxlength="2">
    </td>
   </tr>
  </table>
 </fieldset>

 <br />

<button>return ao inicio</button>
