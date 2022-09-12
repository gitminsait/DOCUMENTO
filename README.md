<html>
<head>

<meta charset="UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1">

<title>Layout Encerramento SD</title>

<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>
<style>
body {background-color: black; color: #f8f9fa; margin: 0;
	}
img {
    vertical-align: middle;
    border-style: none;
   }
#transacao{
    text-transform: uppercase;
}
#menu ul{
margin: 0;
list-style: none;
}
#menu ul li{
display: inline;
}
#menu ul li a {
padding: 2px 10px;
display: inline-block;
text-decoration: none;

}
#menu ul li a:hover {
color: @004d00;
}
</style>
<script>
<!-- ______________________________________________________Variáveis_____________________________________________________________ -->
function pega(){
var1 = "Ação: " + document.formulario.acao.value + "\n";
var2 = "Tipo: " + document.formulario.tipo.value + "\n";	
var3 = "Tema / Assunto: " + document.formulario.temaassunto.value + "\n";
var4 = "Subtema 1 / Assunto: " + document.formulario.subtema1.value + "\n";
var5 = "Subtema 2 / Assunto: " + document.formulario.subtema2.value + "\n";
var6 = "Subtema 3 / Assunto: " + document.formulario.subtema3.value + "\n";
var7 = "Rejeição 1: " + document.formulario.rejeicao1.value + "\n";
var8 = "Rejeição 2: " + document.formulario.rejeicao2.value + "\n";
var9 = "Rejeição 3: " + document.formulario.rejeicao3.value + "\n";
var10 = "Transação: " + document.formulario.transacao.value + "\n";


document.write('<br>');


document.write('<textarea class=form-control rows=20 cols=150 style="border:transparent;">');

document.write(var2);
document.write(var3);
document.write(var4);
document.write(var5);
document.write(var6);
document.write(var7);
document.write(var8);
document.write(var9);
document.write(var10);
document.write(var1);


document.write('</textarea>');



document.write('<br>');
document.write('<br>');
document.write('<button type="button" class="copy" style="background-color:black; color: #fff; borber: 2px solid #4CAF50; padding: 8px 18px;">Copiar Texto</button>');
document.write('<br>');
document.write('<br>');
document.write('<a href="https://rhianmello.github.io/layout.minsait.indra/">Retornar</a>');


const btnCopy = document.querySelector('button.copy');
const textArea = document.querySelector('textarea');

btnCopy.addEventListener('click', (e) => {
  e.preventDefault();
  
  navigator.clipboard.writeText(textArea.value);
  alert('Confirme para que o Texto seja copiado!');
  
});



}

</script>

</head>

<body>
<header>
	<div class="caixa">
		<h1><img src="https://www.indracompany.com/sites/default/files/d7/Nueva_Marca/kit_de_prensa/Imagenes_multimedia/logotipo_minsait_version_secundaria.jpg" width="269">
		</h1>
	</div>
	<HR size="5" color=#fff>
	<div id = "menu">
		<UL>
<div class="container-fluid">
<form name="formulario">
		<div class="form-row">
		<div class="form-group col-md-6">
			<li><a href = "https://rhianmello.github.io/layout.minsait.indra/"> Inicio </a></li>
			<li><a href = "<html>
<head>

<meta charset="UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1">

<title>Layout Encerramento SD</title>

<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>
<style>
body {background-color: black; color: #f8f9fa; margin: 10px, right: 10px;
	}

#transacao{
    text-transform: uppercase;
}
#menu ul{
margin: 0;
list-style: none;
}
#menu ul li{
display: inline;
}
#menu ul li a {
padding: 2px 10px;
display: inline-block;
text-decoration: none;

}
#menu ul li a:hover {
color: @004d00;
}
</style>
<script>
<!-- ______________________________________________________Variáveis_____________________________________________________________ -->
function pega(){
var1 =  document.formulario.tipo.value + "\n"+"\n";	
var2 = "" + document.formulario.temaassunto.value + "\n";
var3 = "" + document.formulario.rejeicao1.value + "\n";


document.write('<br>');


document.write('<textarea class=form-control rows=20 cols=150 style="border:transparent;">');

document.write(var1);
document.write(var2);
document.write(var3);


document.write('</textarea>');



document.write('<br>');
document.write('<br>');
document.write('<button type="button" class="copy" style="background-color:black; color: #fff; borber: 2px solid #4CAF50; padding: 8px 18px;">Copiar Texto</button>');
document.write('<br>');
document.write('<br>');
document.write('<a href="https://rhianmello.github.io/layout.minsait.indra/">Retornar</a>');


const btnCopy = document.querySelector('button.copy');
const textArea = document.querySelector('textarea');

btnCopy.addEventListener('click', (e) => {
  e.preventDefault();
  
  navigator.clipboard.writeText(textArea.value);
  alert('Confirme para que o Texto seja copiado!');
  
});



}

</script>

</head>

<body>
<header>
	<div class="caixa">
		<h1><img src="https://www.indracompany.com/sites/default/files/d7/Nueva_Marca/kit_de_prensa/Imagenes_multimedia/logotipo_minsait_version_secundaria.jpg" width="269">
		</h1>
	</div>
	<HR size="5" color=#fff>
	<div id = "menu">
		<UL>
			<li><a href = "https://rhianmello.github.io/layout.minsait.indra/"> Inicio </a></li>
			<li><a href = "sitef.html"> SITEF </a></li>
			<li><a href = "vivonext.html"> VIVO NEXT </a></li>
			<li><a href = "vivocorp.html"> VIVO CORP </a></li>
			<li><a href = "vivomoney.html"> VIVO MONEY </a></li>
			<li><a href = "Documento CS.html"> Documento CS </a></li>
			<li><a href = "mm.html"> MM </a></li>
			<li><a href = "fi.html"> FI </a></li>
			<li><a href = "email.html"> E-mail para rejeições... </a></li>
			<li><a href = "suporte.html"> Suporte SD </a></li>
		</ul>
	</div>
	</header>
<HR size="5" color=#fff>

<div class="container-fluid">
<form name="formulario">
		<div class="form-row">
			<div class="form-group col-md-6">
			<label>SITEF</label>
			<select id="tipo" class="form-control">
				<option selected>Prezados, 
favor verificar problema de SITEF</option>
				</select>
		</div>

		<div class="form-group col-md-6">
			<label>Consultor</label>
			<select id="temaassunto" class="form-control">
				<option selected>Escolha o Consultor...</option>
                                <option>Ana Kedia</option>
				<option>Cyndi Souza</option>
				<option>Débora Cunha</option>				
                                <option>Fabrícia Silvestre</option>
                                <option>João Paulo Rangel</option>
                                <option>Lennon Queiroz</option>
                                <option>Rhian Mello</option>
                                <option>Vinícius Cusini</option>
            </select>
		</div>                    
		
		<div class="form-group col-md-4">
			<label>Assinatura:</label>
			<select id="rejeicao1" class="form-control">
				<option selected>Consultor SAP SD</option>
                               
			</select>
		</div>

	</div>	
	<button type="button" class="btn btn-success" onclick="pega()">Gerar</button>
	
</form>
</div>

</body>
<div class="form-group col-md-4">
	<label>Fila</label><br>
	<img src="https://user-images.githubusercontent.com/79878127/158693953-f5b66936-0e20-41c2-96d8-e9eac675445c.png" alt="image" height="250"  width="1300">
	
	 </select>
	 </div>
</html>"> SITEF </a></li>
			<li><a href = "vivonext.html"> VIVO NEXT </a></li>
			<li><a href = "vivocorp.html"> VIVO CORP </a></li>
			<li><a href = "vivomoney.html"> VIVO MONEY </a></li>
			<li><a href = "Documento CS.html"> Documento CS </a></li>
			<li><a href = "mm.html"> MM </a></li>
			<li><a href = "fi.html"> FI </a></li>
			<li><a href = "email.html"> E-mail para rejeições... </a></li>
			<li><a href = "suporte.html"> Suporte SD </a></li>
		</ul>
	</div>
	</header>
<HR size="5" color=#fff>

<div class="container-fluid">
<form name="formulario">
		<div class="form-row">
		<div class="form-group col-md-6">
			<label>Tipo</label>
			<select id="tipo" class="form-control">
				<option selected>Escolha o tipo...</option>
				<option>#Cadastro equivocado/ausência</option>
				<option>#Chamado duplicado</option>
				<option>#Desconhecimento de processos</option>
				<option>#Falha de configuração</option>
				<option>#Falha de desenvolvimento</option>
				<option>#Falta de evidências</option>
				<option>#Informativo</option>
				<option>#Instabilidade sistêmica/lentidão</option>
				<option>#Não identificado</option>
				<option>#Normalizado sem intervenção</option>
			</select>
		</div>

		<div class="form-group col-md-6">
			<label>Tema/Assunto:</label>
			<select id="temaassunto" class="form-control">
				<option selected>Escolha o assunto...</option>
                                <option>#Boletim de atendimento - ISHIKAWA</option>
                                <option>#Boletim de atendimento - VICKY</option>
                                <option>#Cliente</option>
                                <option>#Dep Apple</option>
				<option>#Documento CS</option>
                                <option>#Estorno fatura/NF-e</option>
                                <option>#Formulário</option>
                                <option>#Farol TOPUP</option>
				<option>#GAI</option>
                                <option>#GNRE</option>
                                <option>#Impressão DANF-e</option>
                                <option>#Material</option>
				<option>#Nota Fiscal eletrônica (Inclui XML e DANF-e)</option>
                                <option>#Nota Fiscal não eletrônica</option>
                                <option>#Preço</option>
                                <option>#Preenchimento ZCAIXA_MOVIMIP</option>
                                <option>#Processo standard (VA*/VL*/VF*)</option>
                                <option>#Processo ZLOJA/ZCAIXA/ZTROCA</option>
                                <option>#Relatório</option>
                                <option>#Recarga Física</option>
                                <option>#Recarga online</option>
                                <option>#RFCs e interfaces (incluindo trocas de arquivos)</option>
                                <option>#Saldo em estoque</option>
				<option>#SAP Mobile</option>
			</select>
		</div>

	<div class="form-group col-md-4">
			<label>SubTema 1:</label>
			<select id="subtema1" class="form-control">
				<option></option>
                                <option>#AVANT</option>
                                <option>#Callidus</option>
                                <option>#Dep apple</option>
				<option>#Escrituração Fiscal</option>
                                <option>#HYBRIS (Loja online)</option>
                                <option>#NF-e presa na engrenagem/status equivocado</option>
                                <option>#Parada em alguma etapa</option>
                                <option>#Rejeição 109,114,558 - Tentativa de contingência</option>
                                <option>#Rejeição 210,232, 233, 234, 237, 305, 306, 728 - Cadastro cliente perante SEFAZ</option>
                                <option>#Rejeição 215, 225, 532, 531, 508, 602, 693, 694, 798, 799, 815, 930 - Dados tributários de ICMS</option>
                                <option>#Rejeição 228, 703 - Data de operação muito no passado/Data-Hora de Emissão posterior ao horário de recebimento</option>
                                <option>#Rejeição 241 - Nº NF-e já utilizado</option>
                                <option>#Rejeição 245, 301, 302 - Cadastro emitente perante SEFAZ</option>
                                <option>#Rejeição 267, 321, 552 - Devolução referenciando NF-e não aprovada</option>
                                <option>#Rejeição 327, 328, 523, 770, 772, 773 - CFOP não aderente</option>
                                <option>#Rejeição 355, 377, 525, 527 - Exportação</option>
                                <option>#Rejeição 392 - Dados de cartão de crédito/débito</option>
                                <option>#Rejeição 402 - Caracteres especiais</option>
                                <option>#Rejeição 501 - Prazo de cancelamento superior ao permitido</option>
				<option>#Rejeição 570 - tpEmis = 3 só é válido na contingência SCAN</option>
				<option>#Rejeição 610 - Valores totais de NF</option>
                                <option>#Rejeição 627, 663, 697, 698 - Valores de ICMS</option>
				<option>#Rejeição 745 NF-e sem grupo de PIS</option>
                                <option>#Rejeição 806 - Falta de cadastro de CEST</option>
                                <option>#Rejeição 866 - Ausência de troco</option>
                                <option>#Rejeição 876 - Operação interestadual para Consumidor Final e valor do FCP informado em campo diferente de vFCPUFDes</option>
                                <option>#Rejeição 885 - Sem GTIN</option>
                                <option>#Rejeição 904 - Valor de pagamento informado indevidamente</option>
                                <option>#Rejeição 924 - Cupom fiscal referenciado indevidamente</option>
                                <option>#Site de Compras</option>
                                <option>#Status 150, 151, 155 - NF-e cancelada fora do prazo</option>
                                <option>#Valores/formato DANF-e</option>
                                <option>#Valores tributários/contábeis</option>
                                <option>#VICKY</option>
                                <option>#VIVO 360</option>
                                <option>#VIVOCORP</option>
                                <option>#VIVONEXT (Loja física)</option>
                                <option>#VIVONEXT (Loja online)</option>
                                <option>#WFM</option>
                                <option>#XML</option>
			</select>
		</div>
			<div class="form-group col-md-4">
			<label>SubTema 2:</label>
			<select id="subtema2" class="form-control">
                                <option></option>
                                <option>#AVANT</option>
                                <option>#Callidus</option>
                                <option>#Dep apple</option>
								<option>#Escrituração Fiscal</option>
                                <option>#HYBRIS (Loja online)</option>
                                <option>#NF-e presa na engrenagem/status equivocado</option>
                                <option>#Parada em alguma etapa</option>
                                <option>#Rejeição 109,114,558 - Tentativa de contingência</option>
                                <option>#Rejeição 210,232, 233, 234, 237, 305, 306, 728 - Cadastro cliente perante SEFAZ</option>                                <option>#Rejeição 210,232, 233, 234, 305, 306, 728 - Cadastro cliente perante SEFAZ</option>
                                <option>#Rejeição 215, 225, 532, 531, 508, 602, 693, 694, 798, 799, 815, 930 - Dados tributários de ICMS</option>
                                <option>#Rejeição 228, 703 - Data de operação muito no passado/Data-Hora de Emissão posterior ao horário de recebimento</option>
                                <option>#Rejeição 241 - Nº NF-e já utilizado</option>
                                <option>#Rejeição 245, 301, 302 - Cadastro emitente perante SEFAZ</option>
                                <option>#Rejeição 267, 321, 552 - Devolução referenciando NF-e não aprovada</option>
                                <option>#Rejeição 327, 328, 523, 770, 772, 773 - CFOP não aderente</option>
                                <option>#Rejeição 355, 377, 525, 527 - Exportação</option>
                                <option>#Rejeição 392 - Dados de cartão de crédito/débito</option>
                                <option>#Rejeição 402 - Caracteres especiais</option>
                                <option>#Rejeição 501 - Prazo de cancelamento superior ao permitido</option>
				<option>#Rejeição 570 - tpEmis = 3 só é válido na contingência SCAN</option>
				<option>#Rejeição 610 - Valores totais de NF</option>
                                <option>#Rejeição 627, 663, 697, 698 - Valores de ICMS</option>
				<option>#Rejeição 745 NF-e sem grupo de PIS</option>
                                <option>#Rejeição 806 - Falta de cadastro de CEST</option>
                                <option>#Rejeição 866 - Ausência de troco</option>
				<option>#Rejeição 876 - Operação interestadual para Consumidor Final e valor do FCP informado em campo diferente de vFCPUFDes</option>
                                <option>#Rejeição 885 - Sem GTIN</option>
                                <option>#Rejeição 904 - Valor de pagamento informado indevidamente</option>
                                <option>#Rejeição 924 - Cupom fiscal referenciado indevidamente</option>
                                <option>#Site de Compras</option>
                                <option>#Status 150, 151, 155 - NF-e cancelada fora do prazo</option>
                                <option>#Valores/formato DANF-e</option>
                                <option>#Valores tributários/contábeis</option>
                                <option>#VICKY</option>
                                <option>#VIVO 360</option>
                                <option>#VIVOCORP</option>
                                <option>#VIVONEXT (Loja física)</option>
                                <option>#VIVONEXT (Loja online)</option>
                                <option>#WFM</option>
                                <option>#XML</option>
			</select>
		</div>
			<div class="form-group col-md-4">
			<label>SubTema 3:</label>
			<select id="subtema3" class="form-control">
				<option></option>
                                <option>#AVANT</option>
                                <option>#Callidus</option>
                                <option>#Dep apple</option>
								<option>#Escrituração Fiscal</option>
                                <option>#HYBRIS (Loja online)</option>
                                <option>#NF-e presa na engrenagem/status equivocado</option>
                                <option>#Parada em alguma etapa</option>
                                <option>#Rejeição 109,114,558 - Tentativa de contingência</option>
                                <option>#Rejeição 210,232, 233, 234, 237, 305, 306, 728 - Cadastro cliente perante SEFAZ</option>
                                <option>#Rejeição 215, 225, 532, 531, 508, 602, 693, 694, 798, 799, 815, 930 - Dados tributários de ICMS</option>
                                <option>#Rejeição 228, 703 - Data de operação muito no passado/Data-Hora de Emissão posterior ao horário de recebimento</option>
                                <option>#Rejeição 241 - Nº NF-e já utilizado</option>
                                <option>#Rejeição 245, 301, 302 - Cadastro emitente perante SEFAZ</option>
                                <option>#Rejeição 267, 321, 552 - Devolução referenciando NF-e não aprovada</option>
                                <option>#Rejeição 327, 328, 523, 770, 772, 773 - CFOP não aderente</option>
                                <option>#Rejeição 355, 377, 525, 527 - Exportação</option>
                                <option>#Rejeição 392 - Dados de cartão de crédito/débito</option>
                                <option>#Rejeição 402 - Caracteres especiais</option>
                                <option>#Rejeição 501 - Prazo de cancelamento superior ao permitido</option>
				<option>#Rejeição 570 - tpEmis = 3 só é válido na contingência SCAN</option>
				<option>#Rejeição 610 - Valores totais de NF</option>
                                <option>#Rejeição 627, 663, 697, 698 - Valores de ICMS</option>
				<option>#Rejeição 745 NF-e sem grupo de PIS</option>
                                <option>#Rejeição 806 - Falta de cadastro de CEST</option>
                                <option>#Rejeição 866 - Ausência de troco</option>
				<option>#Rejeição 876 - Operação interestadual para Consumidor Final e valor do FCP informado em campo diferente de vFCPUFDes</option>
                                <option>#Rejeição 885 - Sem GTIN</option>
                                <option>#Rejeição 904 - Valor de pagamento informado indevidamente</option>
                                <option>#Rejeição 924 - Cupom fiscal referenciado indevidamente</option>
                                <option>#Site de Compras</option>
                                <option>#Status 150, 151, 155 - NF-e cancelada fora do prazo</option>
                                <option>#Valores/formato DANF-e</option>
                                <option>#Valores tributários/contábeis</option>
                                <option>#VICKY</option>
                                <option>#VIVO 360</option>
                                <option>#VIVOCORP</option>
                                <option>#VIVONEXT (Loja física)</option>
                                <option>#VIVONEXT (Loja online)</option>
                                <option>#WFM</option>
                                <option>#XML</option>
			</select>
		</div>
		
		<div class="form-group col-md-4">
			<label>Rejeição 1:</label>
			<select id="rejeicao1" class="form-control">
				<option></option>
                                <option>#Rejeição 109</option>
                                <option>#Rejeição 114</option>
                                <option>#Rejeição 210</option>
                                <option>#Rejeição 215</option>
                                <option>#Rejeição 225</option>
                                <option>#Rejeição 228</option>
                                <option>#Rejeição 232</option>
                                <option>#Rejeição 233</option>
                                <option>#Rejeição 234</option>								
                                <option>#Rejeição 237</option>
                                <option>#Rejeição 241</option>
                                <option>#Rejeição 245</option>
                                <option>#Rejeição 267</option>
                                <option>#Rejeição 301</option>
                                <option>#Rejeição 302</option>
                                <option>#Rejeição 305</option>
                                <option>#Rejeição 306</option>
                                <option>#Rejeição 321</option>
                                <option>#Rejeição 327</option>
                                <option>#Rejeição 328</option>
				<option>#Rejeição 355</option>
                                <option>#Rejeição 377</option>
                                <option>#Rejeição 392</option>
                                <option>#Rejeição 402</option>
                                <option>#Rejeição 501</option>
                                <option>#Rejeição 508</option>
                                <option>#Rejeição 523</option>
				<option>#Rejeição 525</option>
                                <option>#Rejeição 527</option>
			        <option>#Rejeição 531</option>
                                <option>#Rejeição 532</option>
			        <option>#Rejeição 552</option>
				<option>#Rejeição 558</option>
				<option>#Rejeição 570</option>
				<option>#Rejeição 602</option>
				<option>#Rejeição 610</option>
				<option>#Rejeição 627</option>
                                <option>#Rejeição 663</option>
				<option>#Rejeição 693</option>
                                <option>#Rejeição 694</option>
                                <option>#Rejeição 697</option>
                                <option>#Rejeição 698</option>
				<option>#Rejeição 703</option>
				<option>#Rejeição 745</option>
				<option>#Rejeição 770</option>
                                <option>#Rejeição 728</option>
                                <option>#Rejeição 772</option>
				<option>#Rejeição 773</option>
                                <option>#Rejeição 798</option>
                                <option>#Rejeição 799</option>
                                <option>#Rejeição 806</option>
				<option>#Rejeição 815</option>
                                <option>#Rejeição 866</option>
				<option>#Rejeição 876</option>
                                <option>#Rejeição 885</option>
                                <option>#Rejeição 904</option>
                                <option>#Rejeição 924</option>
				<option>#Rejeição 930</option>
			</select>
		</div>

		<div class="form-group col-md-4">
			<label>Rejeição 2:</label>
			<select id="rejeicao2" class="form-control">
				<option></option>
                                <option>#Rejeição 109</option>
                                <option>#Rejeição 114</option>
                                <option>#Rejeição 210</option>
                                <option>#Rejeição 215</option>
                                <option>#Rejeição 225</option>
                                <option>#Rejeição 228</option>
                                <option>#Rejeição 232</option>
                                <option>#Rejeição 233</option>
                                <option>#Rejeição 234</option>
                                <option>#Rejeição 237</option>								
                                <option>#Rejeição 241</option>
                                <option>#Rejeição 245</option>
                                <option>#Rejeição 267</option>
                                <option>#Rejeição 301</option>
                                <option>#Rejeição 302</option>
                                <option>#Rejeição 305</option>
                                <option>#Rejeição 306</option>
                                <option>#Rejeição 321</option>
                                <option>#Rejeição 327</option>
                                <option>#Rejeição 328</option>
				<option>#Rejeição 355</option>
                                <option>#Rejeição 377</option>
                                <option>#Rejeição 392</option>
                                <option>#Rejeição 402</option>
                                <option>#Rejeição 501</option>
                                <option>#Rejeição 508</option>
                                <option>#Rejeição 523</option>
				<option>#Rejeição 525</option>
                                <option>#Rejeição 527</option>
                                <option>#Rejeição 531</option>
                                <option>#Rejeição 532</option>
				<option>#Rejeição 552</option>
				<option>#Rejeição 558</option>
				<option>#Rejeição 570</option>
				<option>#Rejeição 602</option>
				<option>#Rejeição 610</option>
				<option>#Rejeição 627</option>
                                <option>#Rejeição 663</option>
				<option>#Rejeição 693</option>
                                <option>#Rejeição 694</option>
                                <option>#Rejeição 697</option>
                                <option>#Rejeição 698</option>
				<option>#Rejeição 703</option>
				<option>#Rejeição 745</option>
				<option>#Rejeição 770</option>
                                <option>#Rejeição 728</option>
                                <option>#Rejeição 772</option>
				<option>#Rejeição 773</option>
                                <option>#Rejeição 798</option>
                                <option>#Rejeição 799</option>
                                <option>#Rejeição 806</option>
				<option>#Rejeição 815</option>
                                <option>#Rejeição 866</option>
				<option>#Rejeição 876</option>
                                <option>#Rejeição 885</option>
                                <option>#Rejeição 904</option>
                                <option>#Rejeição 924</option>
				<option>#Rejeição 930</option>
			</select>
		</div>

		<div class="form-group col-md-4">
			<label>Rejeição 3:</label>
			<select id="rejeicao3" class="form-control">
				<option></option>
                                <option>#Rejeição 109</option>
                                <option>#Rejeição 114</option>
                                <option>#Rejeição 210</option>
                                <option>#Rejeição 215</option>
                                <option>#Rejeição 225</option>
                                <option>#Rejeição 228</option>
                                <option>#Rejeição 232</option>
                                <option>#Rejeição 233</option>
                                <option>#Rejeição 234</option>
                                <option>#Rejeição 237</option>								
                                <option>#Rejeição 241</option>
                                <option>#Rejeição 245</option>
                                <option>#Rejeição 267</option>
                                <option>#Rejeição 301</option>
                                <option>#Rejeição 302</option>
                                <option>#Rejeição 305</option>
                                <option>#Rejeição 306</option>
                                <option>#Rejeição 321</option>
                                <option>#Rejeição 327</option>
                                <option>#Rejeição 328</option>
				<option>#Rejeição 355</option>
                                <option>#Rejeição 377</option>
                                <option>#Rejeição 392</option>
                                <option>#Rejeição 402</option>
                                <option>#Rejeição 501</option>
                                <option>#Rejeição 508</option>
                                <option>#Rejeição 523</option>
				<option>#Rejeição 525</option>
                                <option>#Rejeição 527</option>
                                <option>#Rejeição 531</option>
                                <option>#Rejeição 532</option>
				<option>#Rejeição 552</option>
				<option>#Rejeição 558</option>
				<option>#Rejeição 570</option>
				<option>#Rejeição 602</option>
				<option>#Rejeição 610</option>
				<option>#Rejeição 627</option>
                                <option>#Rejeição 663</option>
				<option>#Rejeição 693</option>
                                <option>#Rejeição 694</option>
                                <option>#Rejeição 697</option>
                                <option>#Rejeição 698</option>
				<option>#Rejeição 703</option>
				<option>#Rejeição 745</option>
				<option>#Rejeição 770</option>
                                <option>#Rejeição 728</option>
                                <option>#Rejeição 772</option>
				<option>#Rejeição 773</option>
                                <option>#Rejeição 798</option>
                                <option>#Rejeição 799</option>
                                <option>#Rejeição 806</option>
				<option>#Rejeição 815</option>
                                <option>#Rejeição 866</option>
				<option>#Rejeição 876</option>
                                <option>#Rejeição 885</option>
                                <option>#Rejeição 904</option>
                                <option>#Rejeição 924</option>
				<option>#Rejeição 930</option>
                       </select>
		</div>
		<div class="form-group col-md-4">
			<label>Transação:</label>
				<input type="text" class="form-control" id="transacao" Value="">
		</div></div>
	<div class="form-row">
		<div class="form-group col-md-12">
			<label>Ação:</label>
				<textarea class="form-control" id="acao" style="margin-top: 0px; margin-bottom: 0px; height: 120px;"></textarea>
		</div>
	</div>	
	<button type="button" class="btn btn-success" onclick="pega()">Gerar</button>
	 
</form>
</div>
</body>
</html>
