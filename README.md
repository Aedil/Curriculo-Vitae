# curriculo
Trabalho de CV - Web
<html>
	<head>
		<title>Curriculo Vitae</title>
		<meta http-equiv="Content-Type" content="text/html;charset=utf-8" >
		<link rel="stylesheet" type="text/css" href="style.css">
	</head>
	
	<body>
		<h1>Currículo Vitae</h1>

		<img src="1.jpg" tittle="Foto de Currículo" width=300 height=100/>
				  		
		<ul id="menu">
			<li><a href="cv-resumido.html">Resumido</a></li>
			<li class="ativo">Completo</li>
		</ul>
		
		<div class="secao">
			<h2>Dados Pessoais</h2>			
				<div id="hcard-Aedil-Capovilla-Jerdy" class="vcard">
				 <span class="given-name">Aédil</span>
				  <span class="additional-name">Capovilla</span>
				  <span class="family-name">Jerdy</span>
				<sup><a href="#1-fn" id="fn1" title="veja o rodapé">1</a></sup>

				 <a class="email" href="mailto:aedil.jerdy@gmail.com">aedil.jerdy@gmail.com</a>
				
				<div class="adr">
				  <span class="locality">Rio de Janeiro</span>
				, 
				  <span class="region">Rio de Janeiro</span>

				 </div>
				</div>
		</div>

		<div class="secao">
			<h2>Dados Profissionais</h2>
			
			<p><label>Empresa</label>Lagesolos</p>
			<p><label>Empresa</label>Contax</p>
			<p><label>Empresa</label>SAP</p>
		</div>

		<div class="secao">
			<h2>Formação Acadêmica</h2>
			
			<p><label>Curso</label>Geografia</p>
			<p><label>Curso</label>Sistemas de Informação</p>
		</div>

		<div class="secao">
			<h2>Formação Complementar</h2>
			<table>
				<thead>
				<tr>
					<th>Curso</th>
					<th>Carga horária</th>
				</tr>
				</thead>
				<tr class="par">
					<td>Pontos de Função</td>
					<td>40h</td>
				</tr>
				<tr class="impar">
					<td>Testes de Software</td>
					<td>40h</td>
				</tr>
				<tr class="par">
					<td>Ferramenta de Testes de Software</td>
					<td>16h</td>
				</tr>
				<tr class="impar">
					<td>Requisitos de Software</td>
					<td>24h</td>
				</tr>
			</table>			
		</div>

		<div class="secao">
			<h2>Línguas</h2>
			<table>
				<thead>
				<tr>
					<th>Língua</th>
					<th>Escrita</th>
					<th>Fala</th>
					<th>Leitura</th>
				</tr>
				</thead>
				<tr class="par">
					<td>Inglês</td>
					<td class="bom">Bom</td>
					<td class="bom">Bom</td>
					<td class="otimo">Ótimo</td>
				</tr>
				<tr class="impar">
					<td>Espanhol</td>
					<td class="ruim">Ruim</td>
					<td class="ruim">Ruim</td>
					<td class="regular">Regular</td>
				</tr>
			</table>			
		</div>

		<form action="#" method="post">
			<fieldset>
			<legend>Entre em contato</legend>
			<label for="nome">Nome</label>
			<input type="text" name="nome"/>

			<label for="nome">Email</label>
			<input type="text" name="email"/>

			<label for="nome">Mensagem</label>
			<textarea name="msg"></textarea>

			<input type="submit" value="enviar"/>
			</fieldset>
		</form>

		
		<div id="footnote">
			<li id="1-fn">1 - Microformato <a href="#fn1" title="volte">^</a></li>
			<li>Este <a href="http://microformats.org/wiki/hcard">hCard</a> foi criado com <a href="http://microformats.org/code/hcard/creator">hCard creator</a>.</li>
		</div>		
	</body>
</html>
