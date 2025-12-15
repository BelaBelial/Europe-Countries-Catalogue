# Catálogo Dos Países Europeus
Este projeto é um visualizador de informaçõs geográficas (website) de todos os países da Europa, funcionando de fato como um catálogo com informações padronizadas para cada um dos países. É possível encontrar todas as bandeiras dos respectivos países organizadas em um grid de 5 países em baixo de outros 5. O grid contém as bandeiras dos países e abaixo o nome deles. Quando clicamos no nome, somos redirecionados para a página específica só dele com as seguintes informações: Capital, População e Línguas faladas. *Todo o conteúdo presente foi retirado de fontes confiáveis para fornecer os dados, e se encontra em Inglês.*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

### Esse projeto foi feito utilizando as seguintes linguagens e ferramentas:
![CSS](https://img.shields.io/badge/css-%23663399.svg?style=for-the-badge&logo=css&logoColor=white) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)

# Confira abaixo algumas imagens demonstrativas do website:

![alt text](image.png) 
![alt text](image-1.png)
<video controls src="20251215-1245-53.0181605.mp4" title="Title"></video>


# Como Instalar e Visualizar o Projeto na Máquina Local:
### Pré-Requisitos: 
- É necessário que a pasta do projeto seja baixada em seu computador.
- Deve-se ter o Git instalado na máquina, para poder clonar o repositório.
    - Para fazer isso, acesse este link: [Instalação do Git](https://git-scm.com/install/).
    - Siga as informações presentes no site e verifique o seu Sistema Operacional para baixar de acordo.
    - Quando foi baixar, deixe todo em configuralções ***default***, pois não será necessário funções a mais para utilizar este projeto.
- Uma vez que o processo de instalação chegou ao fim, verifique se o Git está mesmo em sua máquina.
    - Abra o terminal de seu computador: *(Windows: Win + R, e digite "cmd" no pop-up que aparecer)*, *(Linux: Ctrl + Alt + T)*.
    - Ao abrir o terminal, digite o seguinte comando: (```git --version```) ou (```git -v```)
        ![alt text](image-2.png)
    
    - Deve aparecer um texto indicando a versão atual do Git instalado em sua máquina. Se aparecer algo diferente disso, verifique se você realmente seguiu o processo correto de instalação, ou reinicie o terminal e o computador para que o programa possa se ajustar à sua máquina. Na dúvida, repita o processo de instalação.

**Clonando o Repositório Para a Máquina:**
- Agora que você tem o Git instalado em sua máquina, você deve seguir seguintes passos para acessar o projeto e o repositório. Vamos clonar ele para o seu computador.
1. Tenha o Github aberto em seu navegador.
2. Lá, acesse o repositório deste projeto e **Clique no botão verde onde estpa escrito "<> Code"**
3. Na aba "Local", perceba que há um link *https://*, e **o copie clicando no botão ao lado direito do link:**.
        ![alt text](image-3.png)
4. Agora o link do repositório remoto está na sua área de tranferência, e você deve começar o processo de clonagem para sua máquina. Para começar, abra o terminal seguindo as instruções dadas anteriormente dependendo de seu SO ou o faça da maneira que achar melhor.
5. Navegue até a pasta onde deseja clonar, e digite o comando: (```git clone <https://github.com/BelaBelial/Europe-Countries-Catalogue.git>```)
        ![alt text](image-4.png)
6. Agora abra a pasta onde você acabou de clonar o projeto por meio do Explorador de Arquivos do seu OS para poder visualizar os arquivos presentes. Você acabou de clonar o projeto.
        ![alt text](image-5.png)

### Abrindo com sua IDE:
- Uma vez que o processo de clonagem está pronto, você deve abrir a pasta inteira do projeto em um editor de código de sua preferência. 
- Recomendo o uso do VS Code, mas você pode usar aquele que preferir.
- *Caso você não tenha o VS Code instalado ou nenhuma outra IDE, instale ele por meio deste link:* [Download por sistema do VS Code](https://code.visualstudio.com/download).
    - Execute todos os passos que são dados e deixe tudo em ***default***.
    - Para verificar se funcionou, digite no terminal: (```code --version```) e a versão do VS Code deve aparecer para você.
- Depois disso, você **abrir o VS Code e clicar em "File - Open Folder"** (ou qualquer outra IDE que você esteja usando) e selecionar a pasta do repositório que você acabou de clonar.
- Quando você tiver a pasta já aberta no VS Code, **no painel lateral que fica na esquerda, clique em "Extensões" e pesquise por "Live Server"**.
        ![alt text](image-6.png)
- Clique em "Instalar" e complete a instalação. 
- Agora abra o arquivo *"index.html"* na raíz da pasta e no canto inferior direito do VS Code, clique em "Go Live", o que vai abrir uma aba em seu navegador.
- **Uma vez que você fez isso, vai poder visualizar o projeto e usufruir do website completo ou até mesmo distribuir ele.**

## Sugestões de Uso:
- Para aproveitar melhor o website, é sugerível que o user acesse para garantir informações precisas sobre cada país respectivo e garanta que sabe especificamente cada um deles.
- Caso o user seja uma pessoa que goste de se desafiar, pode utilizar este site como material de estudo para quizes geográficos sobre o tema.


# Estrutura do Projeto: 
```
EuropeCountriesList/
│── README.md
│── LICENSE
│── index.html
│── style.css
├── pages/
│   │── albania.html
│   │── andorra.html
│   │── austria.html
│   └── ...
├── assets/
│   │── albania.webp
│   │── andorra.png
│   │── austria.jpg
│   └── ...
└── demo-imgs/
    │── 20251215-1245:53.0181605.mp4
    │── image-1.png
    │── image-2.png
    └── ...
```

- Dentro da pasta *pages* há uma página para cada país, já que não foram usadas rotas nem React para aproveitar o template, tendo em vista que esse projeto foi feito por mim quando eu era bem iniciante.
- Na pasta *assets* há a imagem da bandeira de todos os países, porém só estão sendo listadas 3, assim como na *pages* para não extender muito o arquivo.
- O arquivo *index.html* é o arquivo principal, que é no caso a homepage do site, onde é possível acessar todas as outras páginas.
- O arquivo *style.css* é muito importante pois providencia a estilização da página inicial.

# Licensa:

Este projeto está licenciado sob a MIT License - veja o arquivo [LICENSE](LICENSE) para mais detalhes a respeito.  
