# Criando o primeiro repositório

Após criar o repositório no github, utilize o comando abaixo para clonar e conectar o repositório em seu computador.

> git clone https://github.com/DiasKarol/my_first_steps.git

Para adicionar novos arquivos ou arquivos alterados, utilize a cadeia de comando a seguir:

> cd my_first_steps/

> git add .

> git commit -m "first commit"

> git push origin main

Caso queira ignorar algum arquivo, crie um arquivo .gitignore na pasta raiz do repositorio e insira a seguinte linha:

> /serei_ignorado.txt

É importante que seu projeto tenha um arquivo dizendo ou descrevendo o que foi realizdo no projeto, este arquivo se chama README.md.Para adicioná-lo, crie o arquivo em sua pasta local e insira a descrição, em seguida utilize os comandos:

> git add .

> git commit -m "Add README.md"

> git push origin main