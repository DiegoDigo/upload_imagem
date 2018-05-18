Automatização de upload de imagem
=========================
<p>
    programa que tira o fundo branco e deixa transparente, transforma a imagem em png e faz o rezise para 250 X 250.
	faz o upload no cloudinare e atualiza as imagens dos produtos no postgre.
</p>


<p>
   <h5>Dependencia do Runtime c Windows</h5>   
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
 
