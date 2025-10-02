# Projeto LAGARTA
Nome: Bárbara Diogo Passos e Janaína Diogo Passos
RA: 10737885 e 10737888

# Processo de Ideação
O WomanTech é um projeto de extensão da FCI, em parceria com o programa Meninas Digitais da Sociedade Brasileira de Computação. Seu objetivo é promover a participação feminina na tecnologia, incentivando meninas do ensino médio, mulheres em transição de carreira e estudantes a ingressarem na área, por meio de oficinas, palestras, criação de conteúdos e atividades práticas.

Para ampliar sua visibilidade e alcance, propomos a criação de um site oficial do WomanTech, reunindo informações sobre a ideação do projeto, colaboradores e palestrantes, além de disponibilizar gravações das palestras e um formulário para interessadas em participar ou apoiar a iniciativa. Esse espaço digital funcionaria como um canal de divulgação, engajamento e inclusão, fortalecendo ainda mais a presença feminina na tecnologia.

# Caráter Extensionista
A disciplina Web Mobile possui um caráter extensionista, o que implica que o trabalho que desenvolvermos precisará estar aberto à participação da comunidade, promovendo um diálogo e uma troca de saberes entre a universidade e o público externo. No nosso caso, o foco é ampliar o alcance do projeto Womantech, fazendo, assim, com que o projeto gere um impacto social positivo, ampliando oportunidades e visibilidade para mulheres na tecnologia, um campo historicamente marcado pela baixa representatividade feminina.

Ao atuar de forma extensionista, nosso projeto ajuda a construir pontes entre conhecimento técnico e necessidades sociais, fortalecendo a inclusão e a diversidade no setor tecnológico.


# Protótipo (Wireframe)
<img width="500" height="1600" alt="image" src="https://github.com/user-attachments/assets/db46cd39-e6de-42e8-ade6-782de62d8927" />

# Tutorial HTML
# Homepage
# 1. Estrutura básica do HTML

<img width="667" height="256" alt="image" src="https://github.com/user-attachments/assets/4a473f02-ce59-455d-bb08-8fb141ba6811" />

O código começa com __!DOCTYPE html__, que indica que o site usa HTML5. A tag __html__ envolve todo o conteúdo, e o __head__ contém informações importantes que não aparecem na página, como o título, metadados e o link para o arquivo de estilo (CSS). O __title__ define o nome que aparece na aba do navegador. As tags __meta__ garantem que os caracteres especiais funcionem corretamente e que o site seja responsivo em diferentes dispositivos. O __body__ contém todo o conteúdo visível da página, como textos, imagens e menus.


# 2. Cabeçalho e menu

<img width="597" height="236" alt="image" src="https://github.com/user-attachments/assets/055ee951-3a13-46c5-b93b-5e920d74959a" />


O __header__ é a seção do cabeçalho do site, onde ficam elementos como o logo e o menu. Dentro dele, __section class="header"__ agrupa esses elementos, organizando visualmente o cabeçalho. A tag __nav__ indica a área de navegação, e __ul__ com __li__ cria uma lista de itens do menu. Os links __a href="#"__ permitem que o usuário acesse diferentes páginas ou seções do site.

# 3. Seções

<img width="1095" height="447" alt="image" src="https://github.com/user-attachments/assets/dff11d9e-9c09-42e3-b895-718470e37cf9" />


A __section class="anuncio"__ é usada para separar a imagem que foi usada para promover o evento do resto do código, podendo editá-la separadamente. A __section class="tudo"__ agrupa todo o conteúdo principal da página. Dentro dela, __section class="texto"__ contém o logo, o título e o texto de apresentação do projeto. A __section class="circulo"__ apresenta os objetivos do projeto, e os IDs c1 e c2 foram usados para estilizar separadamente o __h1__ e o __p__ .

# 4. Seção de organizadoras e colaboradoras

<img width="722" height="617" alt="image" src="https://github.com/user-attachments/assets/e02751e7-67b8-4abd-a5e9-118d1e87d64c" />


A __section class="organizadoras"__ agrupa informações sobre as pessoas envolvidas no projeto. Dentro dela, __section class="pessoas"__ organiza a lista de todas as participantes. Cada __section class="pessoa"__ representa uma pessoa, com sua foto e descrição, e a __section class="foto"__ contém especificamente a imagem de cada participante.

# 5. Footer

<img width="475" height="131" alt="image" src="https://github.com/user-attachments/assets/e3632ead-bdcf-47aa-83ab-5732a56c2f08" />

O __hr__ cria uma linha horizontal para separar visualmente as seções. O __footer__ é a área do rodapé da página, e os __p__ contêm os parágrafos com informações de copyright e os nomes das autoras.

# Formulário
# 1. Estrutura básica

<img width="702" height="269" alt="image" src="https://github.com/user-attachments/assets/9a0a049c-45a1-41eb-808d-96373cd2f142" />

O código define o corpo visível da página com __body class="center-form"__, centralizando o conteúdo. Dentro dele, __section class="center-form"__ organiza a área do formulário, iniciado com __form id="form"__ para permitir identificação via CSS ou JavaScript. O __fieldset__ agrupa os campos com uma borda, e __legend__ adiciona o título “Formulário WomanTech”. Por fim, __h4__ fornece instrução ao usuário para preencher os dados.

# 2. Nome e RA

<img width="422" height="53" alt="image" src="https://github.com/user-attachments/assets/9bee120f-40a6-4d2c-ba25-98a4710b35e7" />

Os inputs de texto simples permitem que o usuário digite informações. O código cria um campo para o usuário digitar o nome, identificado pelo atributo __name="nome"__ e outro para digitar o RA (registro acadêmico), identificado por __name="ra"__.

# 3. Email

<img width="735" height="74" alt="image" src="https://github.com/user-attachments/assets/4e3cbfab-364b-4525-b0c9-6918338ec51c" />

O trecho cria um campo de email com __input type="email" id="email"__, associado a um __label__ para acessibilidade. O placeholder indica ao usuário o que digitar, e o __p id="email-error"__ exibe uma mensagem de erro em vermelho caso o email seja inválido, inicialmente escondida com __display:none__.

# 4. Disponibilidade

<img width="672" height="73" alt="image" src="https://github.com/user-attachments/assets/8a2fe145-0753-42fa-b598-50d5d1b451a7" />

O código cria um grupo de opções ( __radio buttons__ ) para selecionar a disponibilidade do usuário. Todas têm o mesmo __name="disp"__ , permitindo escolher apenas uma opção: Manhã ( __value="manha"__ ), Tarde ( __value="tarde"__ ) ou Noite ( __value="noite"__ ).

# 5. Curso

<img width="951" height="101" alt="image" src="https://github.com/user-attachments/assets/182a50e4-1be0-44b8-a75d-9eada19f9b98" />

O trecho cria uma pergunta sobre o curso de tecnologia que o usuário faz, seguida de três opções com caixas de seleção ( __checkbox__ ). O usuário pode marcar uma ou mais opções: Sistemas de Informação ( __value="1"__ ), Análise e Desenvolvimento de Sistemas ( __value="2"__ ) e Ciência da Computação ( __value="3"__ ).

# 6. Etapa e Unidade

<img width="756" height="373" alt="image" src="https://github.com/user-attachments/assets/91cd5a17-8c52-4db8-850f-6922d45c9501" />

O código cria dois menus suspensos (<select>). O primeiro pergunta em qual semestre o usuário está, oferecendo opções de 1º a 8º semestre. O segundo pergunta em qual unidade da Universidade Presbiteriana Mackenzie o usuário estuda, com opções Higienópolis, Alphaville e EAD. Cada <select> permite escolher apenas uma opção por vez.

# 7. Texto

<img width="765" height="41" alt="image" src="https://github.com/user-attachments/assets/e98028c9-24fb-4636-8761-ae40c1625dfc" />

O trecho cria uma área de texto ( __textarea__ ) para que o usuário escreva livremente suas motivações para participar do WomanTech. Os atributos __rows="6"__ e __cols="50"__ definem o tamanho da caixa, permitindo múltiplas linhas de texto.

# Tutorial CSS
# Homepage

# Estilos gerais e cor de fundo da página

<img width="282" height="199" alt="image" src="https://github.com/user-attachments/assets/d835f034-658b-4de7-a70b-96c6cfd75a21" />

Remove margens e espaçamentos padrão de todos os elementos com __* { margin: 0; padding: 0; box-sizing: border-box; }__ e faz com que o padding e a border sejam incluídos no tamanho total do elemento. __body { background-color: #ffe8f0; }__ define a cor de fundo da página como um tom rosa claro.

# Estilo e layout do cabeçalho

<img width="320" height="295" alt="image" src="https://github.com/user-attachments/assets/630e7a8f-b646-46bb-bf3a-d92fdcb8c41f" />

Estiliza o __header__ da página, definindo largura total (__width: 100%__), altura mínima (__min-height: 50px__), e espaçamento interno (__padding: 15px 30px__). O uso de __display: flex__ , __justify-content: space-between__ e __align-items: center__ organiza os elementos horizontalmente, com espaçamento entre eles e centralizados verticalmente. __header img { height: 80px; }__ define a altura das imagens dentro do cabeçalho.

# Estilo do menu de navegação do cabeçalho

<img width="295" height="597" alt="image" src="https://github.com/user-attachments/assets/a008fc05-392b-4a96-9590-6847899718ae" />

Estiliza o menu de navegação dentro do __header__. A lista (__ul__) remove os marcadores (__list-style-type: none__), exibe os itens em linha com flex, alinhando-os à direita (__justify-content: flex-end__) e centralizados verticalmente (__align-items: center__), com espaçamento (__gap: 20px__) e padding à direita. Cada item (__li__) é exibido em linha (__inline-block__) com margem horizontal e alinhamento vertical no topo do texto. Os links (__a__) dentro dos itens não têm sublinhado, têm cantos arredondados, padding, tamanho de fonte de 20px, cor branca e transição suave de 0,3s. Ao passar o mouse (__hover__), o fundo do link muda para rosa claro.

# Estilo de título e parágrafos

<img width="200" height="256" alt="image" src="https://github.com/user-attachments/assets/9f845e40-9b87-4c7a-b59a-09eafe050247" />

Define o estilo do __h1__ com cor rosa, margem de 5px e tamanho de fonte de 30px. Os parágrafos (__p__) também usam a mesma cor, têm espaçamento superior de 20px, flutuam à esquerda (__float: left__) e possuem altura de 100px, organizando o texto de forma alinhada e visualmente consistente.

# Estilo do rodapé

<img width="321" height="411" alt="image" src="https://github.com/user-attachments/assets/7a9fc663-2c3a-44c2-a47d-916203599adf" />

Estiliza o __footer__ com fundo rosa claro, texto centralizado, padding de 20px vertical e 10px horizontal, e cor do texto rosa escuro. A linha horizontal (__hr__) não tem borda padrão, mas recebe uma borda superior rosa escura, centralizada e com 80% da largura. Os parágrafos dentro do rodapé têm margem e padding ajustados, fonte de 16px e mesma cor rosa escura, garantindo um visual limpo e consistente.

# Estilo de imagem 

<img width="289" height="180" alt="image" src="https://github.com/user-attachments/assets/ed37dc8d-e02d-462f-bba1-618c79fa6a04" />

Define que a imagem dentro da classe __.anuncio__ ocupem toda a largura disponível (__width: 100%__) e altura de 430px. O __display: flex__ junto com __justify-content: center__ e __align-items: center__ centraliza o conteúdo da imagem. Além disso, __margin: 0__ remove qualquer espaçamento externo, garantindo que a imagem se ajuste perfeitamente ao contêiner.

# Estilo de layout e conteúdo

<img width="332" height="464" alt="image" src="https://github.com/user-attachments/assets/85c2567d-a626-4bf2-9bcd-31a12ae53d9b" />

Define a classe __.tudo__ como um contêiner flexível (__display: flex__) que distribui os elementos com espaço ao redor (__justify-content: space-around__), mantém um espaçamento interno de 3% (__padding: 3%__) e permite que os itens quebrem linha (__flex-wrap: wrap__) com gap: 20px. A classe __.texto__ organiza o conteúdo em coluna (__flex-direction: column__) com espaçamento de 20px entre elementos, fonte de 20px, margem inferior de 20px e centraliza o conteúdo verticalmente (__justify-content: center__). As imagens dentro de __.texto__ têm posicionamento relativo, deslocadas 50px para a esquerda e 50px para baixo.

# Estilo de elemento circular interativo

<img width="352" height="334" alt="image" src="https://github.com/user-attachments/assets/0bc9835e-a224-4258-ad4e-58d988843f20" />

A classe __.circulo__ cria um elemento de 0 0 300px; com fundo rosa escuro e bordas arredondadas (__border-radius: 50%__), formando um círculo. Ele usa __display: flex__ em coluna para centralizar conteúdo vertical e horizontalmente, com padding de 30px e texto centralizado. A propriedade __transition: 0.3s__ suaviza alterações de estilo. Ao passar o mouse (__:hover__), o círculo aumenta de tamanho com __transform: scale(1.2)__, criando efeito interativo.

# Estilo da seção de organizadoras

<img width="590" height="614" alt="image" src="https://github.com/user-attachments/assets/bfa3f10c-8ba4-468d-8e38-0e27bb29482e" />

A classe __.organizadoras__ define o espaçamento interno (__padding: 60px 10%__) e uma borda superior rosa (__border-top: 2px solid #c9797d__) para a seção de participantes. O título (__.organizadoras h1__) tem margem inferior, fonte de 30px e exibe elementos alinhados horizontalmente com espaço (__gap: 10px__). A lista de pessoas (__.pessoas__) é organizada em grid responsivo, com colunas automáticas e espaçamento de 40px, centralizando os itens. Cada participante (__.pessoa__) tem texto centralizado. As imagens (__.foto img__) são circulares (__border-radius: 50%__), têm tamanho 150x150px, margem inferior de 15px e centralização, com efeito de aumento ao passar o mouse (__hover: transform: scale(1.2)__) para interatividade visual.

# Estilos responsivos para telas pequenas

<img width="465" height="541" alt="image" src="https://github.com/user-attachments/assets/baaf2da5-1224-4b87-ae02-2c175dcd3dc6" />

Este trecho adapta o layout para telas com largura máxima de 768px, como tablets e celulares. Elementos em __.tudo__ passam a se organizar em coluna e centralizados. O menu de navegação se ajusta, centralizando os itens e permitindo que quebrem linha, com fontes menores. Os elementos circulares (__.circulo__) ficam mais estreitos, com bordas menos arredondadas, e a grade de participantes (__.pessoas__) se ajusta para caber melhor em telas pequenas. Além disso, os parágrafos deixam de flutuar e sua altura se ajusta automaticamente, garantindo melhor leitura e usabilidade em dispositivos móveis.

# Formulário
# Centralização do formulário e estilo do corpo

<img width="387" height="293" alt="image" src="https://github.com/user-attachments/assets/215b874f-4d1b-420a-a2d0-dd6c58127d1f" />

O __body__ recebe um fundo rosa escuro. A classe __.center-form__ garante que o corpo tenha altura mínima de 100% da tela, permitindo que o formulário seja centralizado vertical e horizontalmente. O formulário dentro de __.center-form__ usa __position: absolute__ e transformações (__translate__) para ficar exatamente no centro da tela, criando um layout visualmente equilibrado e destacado.

# Estilo de formulário e links

<img width="195" height="205" alt="image" src="https://github.com/user-attachments/assets/f286fdc6-9238-4eda-853f-9d3bd2b94288" />

O __fieldset__ define a cor da borda e do texto como branca, destacando os títulos e conteúdos do formulário. O __form__ tem largura de 40% e altura de 50% da tela, garantindo um tamanho proporcional e centralizado. Os links (__a__) aparecem em branco e sem sublinhado, mantendo a estética limpa e consistente com o design do formulário.

# Javascript
# Formulário

# Função de envio do formulário

<img width="436" height="569" alt="image" src="https://github.com/user-attachments/assets/3dcf70b9-548b-4311-b34b-321c4a213bee" />

Ele verifica se o nome foi preenchido, se o e-mail está no formato correto e se o campo sobre você não está vazio. Caso algum campo esteja incorreto, mostra alertas de erro e impede o envio do formulário (__preventDefault__). Se todos os campos estiverem válidos, o envio prossegue (ou aparece o alerta “Formulário enviado com sucesso”).
