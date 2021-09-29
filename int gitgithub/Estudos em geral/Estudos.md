### Comandos básicos de Git e terminal

DIR = Listando arquivos e pastas

CD = Entrar em uma pasta

CD .. =Retornar para a pasta anterior

CLS = Comando para limpar a tela (Clear Screen)

MKDIR = Usado para criar pasta (mkdir workspace←exemplo)

ECHO = Exibe mensagens que você digitou ou ativa ou desativa o eco de comandos

> (Maior que) = É redirecionador de fluxo

DEL = deleta apenas os arquivos de uma pasta

RMDIR = Usado para remover um diretório ou pasta

LS = Listar arquivos

LS -a = Mostra arquivos ocultos (-a é uma flag)

PWD = Mostra o caminho completo do diretório

GITCONFIG --LIST = Mostra as config, como nome, email

git remote add origin [URL] = para adicionar um repositorio remoto

git checkout = é usado para se mover entre as branches

git checkout -b = esta se movendo para outro branche e criando uma nova

git branch -m = para alterar o nome da branch q você está

git branch - m nome da branch novo nome da branch = altera o nome de outra branch sem ser a que vc se encontra

git branch -d nome da branch = deleta uma branch

git log = mostra o historico de mudanças

git log --oneline = mostro o historico com apenas uma linha

git log --graph = mostra um gráfico de branchs

git reset --soft = desfaz o commit e o move para o index/staging novamente, momento antes do "git commit -m "comentario" "

git reset --mixed = desfaz o commit e o move para o workind directory, momento antes do "git add *"

head~1 = Head - 1

git reset --hard = ele remove o commit por completo

git revert

git config --global core.editor "code --wait" = seta o vscode como editor de commits

git config --global core.editor unset = desfaz o acima

*para remover um email ou nome atrelado ao git faça:*

git config --global --unset user.email

git config --global --unset [user.name](http://user.name)

e para atrelar um nome ou email faça:

git config --global  user.email "[email@gmail.com](mailto:email@gmail.com)"

git config --global  [user.name](http://user.name) Willer Almeida

obs: Usar o comando cd + tab auto completa um nome de pasta, como por exemplo cd W(aperta tab) cd windows

---------------------------------------

futuramente farei um outro repositório mais organizado e com tudo que já aprendi até aqui! :smile: :books: 