### Como hospedar na Square Cloud

##

### Arquivos necessários:
- Os arquivos onde estão os comandos, eventos, token e coisas importantes para sua aplicação (sua terminação é .py)
- requirements.txt (Arquivo de texto com todas as bibliotecas que sua aplicação usa)
- squarecloud.app **ou** squarecloud.config (Arquivo de configuração, para que a Square saiba qual o arquivo principal da sua aplicação, quanto de ram ela deve ter, e tals)

##

### NOTA:

- Antes de fazer uma aplicação que envolva python, **APRENDA PYTHON**. Não faz sentido você tentar fazer algo se você não sabe como fazer. Não faz sentido você tentar fazer uma casa se você não sabe fazer concreto. Se você quer algo pronto, **PAGUE POR ISSO**. Programação não é fácil e muito menos rápida. Se você quer fazer uma aplicação, seja do que ela for, **ESTUDE SOBRE O ASSUNTO**. Com o intuito de ajudar os pequenos gafanhotos que ainda tem a programação como algo novo para eles, vou indicar um curso muito bom de python: Curso em Vídeo. O Curso em Vídeo é uma rede de cursos muito boa que disponibiliza materiais de estudo relacionados à várias linguagens de programação. Inclusive, se você não gostar de Python, Não tem problema. Existem vários peixes no mar, não fique com um peixe que você não gosta. Tem várias outras linguagens que você também pode aprender, como **Go**, **Java**, **JavaScript**, **TypeScript** e **MUITO MAIS**. Mas, caso você goste de python, continue lendo essa documentação que, sem mais enrolação, eu vou ensinar a criar os arquivos necessários para poder hospedar sua aplicação em **Python**.

- **PS: Vou deixar links de cursos no final dessa documentação para quem quiser aprender Python**
- **PS²: Vou ensinar apenas como cria o requirements.txt e squarecloud.app, já tenha codado seus arquivos (primeiro item da lista de arquivos necessários)**

##

### requirements.txt 

- O requirements.txt é um **arquivo de texto** com o nome de "requirements", ele **NÃO É** um arquivo de texto com o nome "requirements.txt", apenas sua **extensão** que é ".txt" (extensão != nome). Para criar ele, é só criar um arquivo de texto com o nome "requirements" e colocar, nele, todas as bibliotecas que seu bot usa (como discord.py, por exemplo). Para cada biblioteca, você deixa uma linha reservada no seu requirements.txt, por exemplo:

- Código:
```
import discord #Importou a biblioteca "discord"
from discord.ext import commands #Importou a classe "commands" que é, também, da biblioteca "discord"
import pillow #Importou pillow
from discord.ui import Select, View #Importou a função Select e a classe View da biblioteca "discord"

... # Resto do código
```

- Considerando que o código acima só usou coisas da biblioteca "discord" e da biblioteca "pillow", o requirements.txt deve conter apenas o nome dessas duas bibliotecas

- requirements.txt:
```
discord
pillow
```

##

### squarecloud.app

- O squarecloud.app é a parte mais simples, apenas vá no <a href="https://squarecloud.cf" target="_blank">site de geração do squarecloud.app</a>, gera ele e adiciona ele no seu arquivo .zip

##

### Compactar para .zip

- <a href="https://www.youtube.com/watch?v=ByZtXLn7ydg" target="_blank">clique aqui</a> para saber como transformar seus arquivos em .zip

##

### Enviando para a Square Cloud

- Agora que seu arquivo .zip está pronto, é só enviar para a Square! Caso você ainda não esteja na Square, <a href="https://squarecloud.app" target="_blank">clique aqui</a> e, depois, clique no botão de "Entrar" para logar no servidor da Square Cloud.

<img src="https://cdn.discordapp.com/attachments/977555716166533200/1053383801528660038/image.png">

- Depois, vá no chat #commands na Square, digite /up, envie seu arquivo e seja feliz!

##

### Material de estudo

- <a href="https://www.cursoemvideo.com/curso/python-3-mundo-1/" target="_blank">Python - Primeira parte</a>
- <a href="https://www.cursoemvideo.com/curso/python-3-mundo-2/" target="_blank">Python - Segunda parte</a>
- <a href="https://www.cursoemvideo.com/curso/python-3-mundo-3/" target="_blank">Python - Terceira parte</a>
