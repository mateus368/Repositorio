Trabalho-emerson
Para começar a fazer o repositorio Nos vamos para o Git Bash, nos começamos dando "cd Documento/" para facilitar na hora de escrever vc da "cd doc" e aperta a tecla "TAB" que ele prenchera o resto que esta faltando do comando, o "cd Documento/" serve para vc entra na pasta Documentos, logo em seguida Dando "git init", git init serve para iniciar um novo repositório Git em um projeto local. Depois de você fazer o "git init" você vai dar "git add ." esse comando serve para preparar (adicionar à staging area) todos os arquivos modificados e novos do seu diretório atual. Com isso nois damos "cd e o nome do seu arquivo" com isso ele vai abri seu arquivo ai com isso nos vamos sair do git bash dando o comando "code ." para ir para o VScode, dentro do VScode nois damos " ctrl + ' " para abrir o terminal e com isso nois vamos no botao parecido com "+" e clicamos e você vai clicar em "Git bash" para você poder começar o seu repositorio. Apos você fizer isso você vai dar o comando " git commit -m "primeiro commit" " o git commit -m , serv para rastrear alterações nos mesmos arquivos toda vez, apos esse comando nois vamos dar o comando "git branch -M main" o comando branches permitem que você desenvolva recursos, corrija erros ou experimente com segurança novas ideias em uma área contida do seu repositório. Agora vc vai criar um repositorio no git hub e o git hub vai te dar varias "opcoes" como por exemplos dar o nome para o repositorio e eu vou ativar o opção "Add README" para colocar esse tutorial la ai vc cria o repositorio. Para você verificar seu arquivos de o codigo "git status", para adicionar o os arquivos você vai dar "git add ." Para Mandar pro github, Se o repositório já estiver conectado ao GitHub:

git push origin master

ou

git push origin main

(Depende do nome da branch.)

Como descobrir se é main ou master

Digite:

git branch

Exemplo:

main

Então use:

git push origin main Se for a primeira vez enviando o projeto Crie um repositório no GitHub. Copie a URL do repositório. No terminal: git init git add . git commit -m "Primeiro commit" git branch -M main git remote add origin URL_DO_REPOSITORIO git push -u origin main
