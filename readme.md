Automatização de upload de imagem
=========================
<p>
    programa que tira o fundo branco e deixa transparente, transforma a imagem em png e faz o rezise para 250 X 250.
	faz o upload no cloudinare e atualiza as imagens dos produtos no postgre.
</p>


<p>
   <h3>Dependencia do Runtime c Windows</h3>
   <h5>Para Windows Server 2008 R2</h5>
   https://support.microsoft.com/pt-br/help/2999226/update-for-universal-c-runtime-in-windows
</p>


Exemplo de configuraçao do arquivo ***config.ini***
--------
     
    [CONFIG]
	revenda = licença
	upload = false
	path_image = path_image
	path_image_formatted =


	[COULDINARY]
	cloud_name = user
	api_key = apikey
	api_secret = secret


	[POSTGRES]
	dbname = portal_vendas_6461
	user = user
	host = localhost
	port = 9999
	password = senha
 
 
 Como instalar
 -------
  
 <ul>
	<li>Criar uma virtualenv com *** pip install virtualenv ***</li>
	<li>inciar a virtualenv *** virtualenv --no-site-packages pastavirtualenv/scripts/activate ***</li>
	<li>instalar dependencias na maquina virtual *** pip install -r requerments.txt  ***</li>	
 </ul>
