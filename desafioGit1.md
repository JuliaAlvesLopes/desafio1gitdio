#Dicas Git e GitHub 
## Primeiros Passos 

###Fazer downloads e instalações dos programas:
#####
- Git (programa) entre no site oficial baixe e instale de forma instintiva seguindo as recomendações do mesmo.
-  MARKDOWN (extensão de arquivo) ao buscar o dowloads as duas primeiras opções já sugerem programas com a extensão MARKDOW, eu estou usando MARCKDOWNPAD, pois funciona em duas janelas uma você digita e ao lado o resultado aparece instantaneamente!
#### Agora entre  no site do GitHub e faça sua conta na plataforma, normal como em uma rede social.Em caso de duvidas tem vários vídeos explicando como criar a conta e editar o perfil.


####**Vamos começar pelo Markdown**
O MARKDOWN é uma maneira rápida e fácil de fazer anotações, criar conteúdo para um site e produzir documentos prontos para impressão. Mais fácil do o texto com HTML, é preciso colocar marcas ao redor do texto. Por exemplo, se você quiser marcar em negrito, precisa digitar "< b> texto em negrito </b >". Já com o markdown, basta escrever uma palavra entre [*asteriscos*] e ela aparecerá em negrito, assim como ocorre no aplicativo WhatsApp.

**Formatações Markdown**

* Negrito: adicione dois asteriscos **texto**

* Itálico: adicione apenas um asterisco *texto* 
 
* Texto-âncora: utilize os caracteres [](), adicionando entre chaves o texto que você quer que apareça, e entre os parênteses, o endereço de destino, no formato [exemplo](https://exemplo.com/).


* Link direto: envolva o endereço da web em chaves <>. O endereço ficará visível e será clicável pelo usuário. O endereço em forma de link direto tem o formato <https://exemplo.com/>. 

* Para inserir imagem: ![Alt ou título da imagem](URL da imagem)



**AGORA QUE SEU TEXTO ESTÁ LINDO E PRONTO AQUI É HORA DE INICIAR OS TRABALHOS NO  GIT.**

1.Crie uma pasta com o nome do seu projeto e  salve seu arquivo Markdown nessa pasta. 

2.Na pasta sem abrir nada clique com o botão direito do mouse e escolha **Git Bash Here**
Já vai abrir na pasta criada

###**Comandos no Windows  **

* cd   (abre pastas) 
* cd / (vai para a pasta raiz)
* cls (limpa o terminal)
* cd.. (sobe um nível de diretório) 
* cd/ (vai para pasta raiz)
* del (deleta)
* mkdir (cria uma pasta
* rmdir (deleta pasta)
* tab (auto completa)
* q (para sair da pasta ou diretório) 

###**Comandos GIT**
Todos os comandos irão ser iniciados pelo nome do programa GIT e serão complementados pela ação:
Sempre depois de escrever cada comando [ENTER]

*git init (inicia o repositório na pasta, começa a rodar o GIT efetivamente) 

_Caso sua pasta não apareça. Ela pode estar oculta.Então:
Use a flag  ls -a_

###**Hora de comitar nosso arquivo**

git add *

git commit -m ""
para colocar identificar qual commiti é Ex inicial ou data


###**Hora de enviar para Plataforma do GITHUB

Nesse momento é importante verificar se seu usuário e e-mail na plataforma estão iguais aos configurados no git 

Para isso dentro do GIT use o comando: 
git config --list

Caso necessário mudar no GIT
git config --global --unset user.email

git config --global --unset user.name

Depois faça o processo tirando unsert e colocando seu nome e e-mail no local

**exemplos**
git config --global user.email"funo@h.com"

git config --global user.name "fulaninho"

Agora dentro da sua pagina no GITHUB

* Ao lado da sua foto no alto a direita, clique na flecha que aponta para baixo.
* Escolha a opção _seus repósitorios_
* NOVO
* crie ou coloque o nome do seu repositório 
* escolha entre publico ou privado
* com repositório criado o GitHub já sugere algumas ações
* copie o link gerado 
* volte para GIT em sua maquina 
* coloque o comando
git remote add origin (e coloque lik copiado no GITHUB)
