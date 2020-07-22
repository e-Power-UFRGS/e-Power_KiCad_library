# e-Power UFRGS KiCad library

É recomendado olhar esse [vídeo](https://www.youtube.com/watch?v=SWYqp7iY_Tc) que explica o básico sobre Git e GitHub e esse [vídeo](https://www.youtube.com/watch?v=75QfD59yHT8) que explica e descreve esse guia de forma didática.

Siga as convenções padrão de biblioteca do KiCad: https://kicad-pcb.org/libraries/klc/

## Como instalar e ficar atualizado com a biblioteca da e-Power UFRGS pra KiCad através do GitHub:

**(Passo 0):** Instalar o KiCad.

- [KiCad Downloads](https://kicad-pcb.org/download/)

**(Passo 1):** Instalar o Git.

- [Git Downlaod (Windows)](http://git-scm.com/download/win)

**(Passo 2):** Criar uma pasta (normalmente nos documentos), clicar com o botão direito e selecionar "Git Bash Here".

**(Passo 3):** Rodar o comando:
```
git clone https://github.com/e-Power-UFRGS/e-Power_KiCad_library.git
```

Aqui você já está atualizado com a biblioteca da e-Power na versão mais recente. Agora já pode configurar esses arquivos no KiCad.

Comandos úteis de se saber:
```
git status                   // mostra os arquivos que foram alterados
git add .                    // adiciona todos arquivos alterados
git commit -m "<message>"    // realiza o commit com a mensagem que está entre aspas
git push origin master       // envia para o servidor central as alterações feitas
git pull                     // requisita do servidor central as alterações feitas
```

**(Passo 4):** Configurar os "paths" no KiCad para reconhecer os arquivos:
```
Preferences > Configure Paths
```
![Configure Paths](https://user-images.githubusercontent.com/15946943/87470354-03d16200-c5f3-11ea-86e4-19bf7193a1f0.png)

**(Passo 5):** Configurar a biblioteca de símbolos no "Symbol Editor"
```
Symbol Editor > Preferences > Manage Symbol Libraries... > Global Libraries > Add existing library to table
```
![Symbol Editor](https://user-images.githubusercontent.com/15946943/87526148-d4f1d500-c660-11ea-8e08-1d04aaf40542.png)


**(Passo 6):** Configurar a biblioteca de footprints no "Footprint Editor"
```
Footprint Editor > Preferences > Manage Footprint Libraries... > Global Libraries > Add existing library to table
```
![Footprint Editor](https://user-images.githubusercontent.com/15946943/87471654-1a78b880-c5f5-11ea-8855-57f1d5b482cc.png)

**(Sempre que quiser atualizar a partir do servidor):** Abrir com o Git Bash onde a pasta está instalada no computador
```
git pull
```

**(Quando quiser enviar uma atualização pro servidor):** Abrir com o Git Bash onde a pasta está instalada no computador
```
git status
git add .
git commit -m "<message>"
git push origin master
```


## License
[MIT](https://choosealicense.com/licenses/mit/)
