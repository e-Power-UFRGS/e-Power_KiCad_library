# e-Power UFRGS KiCad library

É recomendado olhar esse [vídeo](https://www.youtube.com/watch?v=SWYqp7iY_Tc) pra saber o básico sobre Git e GitHub.

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
![Symbol Editor](https://user-images.githubusercontent.com/15946943/87470998-041e2d00-c5f4-11ea-899b-ded169c538df.png)

**(Passo 6):** Configurar a biblioteca de footprints no "Footprint Editor"
```
Footprint Editor > Preferences > Manage Footprint Libraries... > Global Libraries > Add existing library to table
```


**(Sempre que quiser atualizado do servidor):** 
```

```

**(Quando quiser enviar uma atualização pro servidor):** 
```
Symbol Editor > Preferences > Manage Symbol Libraries... > Global Libraries > Add existing library to table
```


## License
[MIT](https://choosealicense.com/licenses/mit/)
