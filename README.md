github-na-pratica

## clonar repositório
git clone <endereço-github>

## criar nova branch e ir para ela 
git checkout -b nome-nova-branch

## criar nova branch e permanecer na main ou em branch
git branch nome-nova-branch

## mostrar as branchs criadas e ativa
git branch

## analisar o status do repositório/branch
git status

## para começar a enviar arquivos para o servidor github
    //para enviar todos os arquivos criados ou alterados
    git add .

    //para enviar somente o arquivo .gitignore
    git add .gitignore

    //para criar um 'envelope de envio' com dados de quem esta fazendo o envio
    git commit 

    um editor será aberto... pressionar tecla I (inserção)... colocar título da alteração... 3 ENTER... texto exolicativo da alteração... pressionar ESQ... pressionar : .... na sequencia digitar wq 

    uma alternativa é...

    git commit -m "texto explicativo do que esta indo para o github"

    Atenção!! Na primeira vez, o git instalado na máquina vai precisar autorizar 
    git config --global user.email "you@exeample.com"
    git config --global user.name "Your name"

    //para enviar as alterações locais ao servidor github na branch ativa
    git push

    //para enviar as alterações locais ao servidor github especificando branch
    git push -u origin nome-branch-desejada