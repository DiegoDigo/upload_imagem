Automatização de upload de imagem
=========================
<p>
    programa que tira o fundo branco e deixa transparente, transforma a imagem em png e faz o rezise para 250 X 250.
	faz o upload no cloudinare e atualiza as imagens dos produtos no postgre.
</p>

	 Exemplo de configuraçao do arquivo ***config.ini***
	 --------
     
    [CONFIG]
	revenda = 6461
	upload = false
	path_image = C:\Users\diego.delmiro\Pictures\Allize
	path_image_formatted =


	[COULDINARY]
	cloud_name = dutxxwomw
	api_key = 224363459748192
	api_secret = 9hlO5CJ8hx5LupDQ10UZM5YGe-4



	[POSTGRES]
	dbname = portal_vendas_6461
	user = postgres
	host = localhost
	port = 5432
	password = control
 
