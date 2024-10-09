# QuickDraw
Projeto onde o usuário desenha algo no site criado por HTML e ao enviar o desenho a IA reconhece o que foi desenhado. O banco de dados usado para a realização foi com imagens de maçã, banana, bolo, machado e faca, foi usado o TensorFlow para o aprendizado de máquina.
 -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
 Passo a Passo para rodar o projeto:
 
 1- Baixe todos os arquivos.
 
 2- Se não estiver em uma pasta, coloque-os em uma com nome 'coiso' e jogue a pasta para 'documentos' no gerenciador de arquivos.
 
 3- Após isso abra a pasta no Visual Studio Code.
 
 4- Baixe as bibliotecas para funcionamento: 'flask', 'tensorflow' e 'opencv-python'.
 
 5- Abra o código JS e altere o caminho do arquivo para o do seu computador na variável 'destination_folder'.
 
 6- Rode cada um dos três arquivos python em terminais distintos com a função: 'python (nome_do_arquivo).py.
 
 7- Abra outro terminal e rode a função: "python -m http.server".
 
 8- O código JS terá dois links especificados para Windows ou MacOS, basta ler e copiar o do devido sitema que vocÊ ultiliza.
 
 9- Abra um CMD e cole o link lá, ele abrirá o chrome, não logue com nenhum usuário.
 
 10- Na aba de pesquisa abra o local host, por exemplo 'http://localhost8000/'

Não foi possível realizar o upload do arquivo do aprendizado de máquina. Segue as instruções para a criação dele:
1- Entre no Teachable machine e use imagens dos objetos citados ou dos da sua preferência para criar um modelo.
2- salve o modelo e o adicione na pasta que está sendo usada para armazenar os arquivos de programação.
