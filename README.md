# e-Power UFRGS KiCad library

É recomendado olhar esse [vídeo](https://www.youtube.com/watch?v=SWYqp7iY_Tc) pra saber o básico sobre Git e GitHub.

## Como instalar e ficar atualizado com a biblioteca da e-Power UFRGS pra KiCad através do GitHub:

(Passo 1): Instalar o Git

- Windows: http://git-scm.com/download/win

(Passo 2):

- criar uma pasta (normalmente nos documentos), clicar com o botão direito e selecionar "Git Bash Here"

(Passo 3): 
- rodar o comando:
```
git clone https://github.com/e-Power-UFRGS/e-Power_KiCad_library.git
```

Aqui você já está atualizado com a biblioteca da e-Power na versão mais recente. Agora já pode configurar esses arquivos no KiCad.

Comandos úteis de saber:
```
git status                   mostra os arquivos que foram alterados
git add .                    adiciona todos arquivos alterados
git commit -m "<message>"    realiza o commit com a mensagem que está entre aspas
git push origin master       envia para o servidor central as alterações feitas
git pull                     requisita do servidor central as alterações feitas
````

## License
[MIT](https://choosealicense.com/licenses/mit/)
