# dio-lab-AI-language-azure
Repositório do lab  "Análise de Sentimentos com Language Studio no Azure AI" da Digital Innovation One.

# Análise de sentimentos com Language Studio no Azure AI

## Explorando a fala com Speech Studio 💬

- Acesse o site [Speech Studio](https://speech.microsoft.com/portal) para explorar recursos de fala;

<font color="red">OBS: <font color="white"> Para acessar os recursos do Speech Studio, faz-se necessário logar/criar uma conta, que é a mesma utilizada no Microsoft Azure. Mesmo com recursos pagos, é possível criar conta gratuita. </font></font>

- Na página inicial, clique em Configurações (ícone de engrenagem no canto superior direito);

- Selecionar um recurso na lista "Todos os recursos"; caso não tenha recursos, clique na opção "+ Criar novo recurso";

- Com a janela "Criar um recurso Fala" aberta, preencha todas as informações e clique no botão "Criar um recurso" (canto inferior da janela suspensa);

- Após a criação do recurso, ele aparecerá na lista "Todos os recursos". Basta selecioná-lo (o símbolo de check estará azul);

- Clique no botão "Usar o recurso" no canto inferior esquerdo da tela;

- A janela automaticamente retornará para a página inicial do site. Rola a janela para baixo até o bloco de opções "Conversão de fala em texto" e selecione "Conversão de fala em texto em tempo real";

- Escolha o idioma do áudio, que no exemplo dado (vide arquivo disponibilizado em [fundamentos-de-ai-mslearn](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/09-speech.html)) é Inglês (Estados Unidos);

- Na parte "Escolher os arquivos de áudio", selecione o arquivo na opção "Procurar arquivos..." ou grave um áudio em "Gravar áudio com microfone". A medida que o upload vai sendo realizado, o texto referente ao arquivo vai aparecendo ao mesmo tempo (ou seja, em tempo real) em "Texto", na parte de ["Resultados de teste"](https://github.com/pedrosaroh/dio-lab-AI-language-azure/blob/main/images/Speech%20Studio.png);

- Na mesma página, há a opção de "Próximas etapas", incluindo códigos de exemplos no GitHub;

- Ao fim do laboratório, o documento do Azure aconselha a, caso não for mais utilizar o recurso, que ele seja excluído, para não gerar custos desnecessários. Como ainda foi realizado mais um laboratório, esse passo foi ignorado.

## Explorando texto com Language Studio 📄

- Acesse o site [Azure](https://portal.azure.com/#home) para explorar recursos de texto;

- Fazer o login na conta Microsoft Azure, caso ainda não esteja logado (ícone no canto superior direito);

- No bloco de opções "Serviços do Azure", clique na opção "Criar um recurso";

- Na barra lateral à esquerda, há uma lista de recursos chamada "Categorias". Clique na opção "IA + Machine Learning", que abrirá opções na parte central da tela "Serviços Populares do Azure";

- Clique na opção "Serviço de Linguagem";

- Na janela seguinte, clique no botão "Continue to create your resource", no canto inferior esquerdo;

- Na janela seguinte, preencha todas os campos e clique no botão "Examinar+criar" no canto inferior;

- Após carregar a tela seguinte, verifique as informações na tela e, caso as informações estejam corretas, clique em "Criar";

- Após carregar a tela seguinte, aparecerá o aviso confirmando que o deploy está completo. Clique no botão "Vá para grupo de recursos";

- Verifique na lista que o recurso recém-criado aparecerá em primeiro na lista;

- Abra o [Language Studio](https://language.cognitive.azure.com/home);

- Assim que a tela carregar, aparecerá uma tela suspensa para que seja selecionado um recurso do Azure (normalmente, ele identifica o último que foi criado). Preencha as informações restantes e, por fim, clique no botão "Done";

- Nas abas abaixo da caixa "Recent custom projects you've worked on", clique na aba "Classify text";

- Em seguida, clique na opção "Analyze sentiment and mine opinions";

- Na tela seguinte, selecione o idioma do texto (no caso do exemplo é inglês) e o recurso a ser utilizado (nesse caso, o que foi criado no início das instruções);

- A seguir, coloque o [texto](https://github.com/pedrosaroh/dio-lab-AI-language-azure/blob/main/images/Language%20Studio_TextoOriginal.png); nesse caso, foi utilizado o texto de exemplo disponibilizado em [mslearn-ai-fundamentals](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/06-text-analysis.html);

- Desça a tela e marque a opção "I acknowledge that runnig this demo..." e clique no botão "Run" logo abaixo;

- Na caixa "Result" aparecerá a análise de sentimentos por frase e geral;

- No caso do exemplo, a análise resultou em:

-[Análise de sentimento](https://github.com/pedrosaroh/dio-lab-AI-language-azure/blob/main/images/Language%20Studio_Analise%20geral.png): 100% negativo, sendo avaliado pelas sentenças identificadas;

-[Sentença 1](https://github.com/pedrosaroh/dio-lab-AI-language-azure/blob/main/images/Language%20Studio_Sentenca1.png): Opinião 100% negativa, com 99,00% sobre o hotel e 99,00% sobre o serviço;

-[Sentença 2](https://github.com/pedrosaroh/dio-lab-AI-language-azure/blob/main/images/Language%20Studio_Sentenca2.png): Opinião 100% negativa, sobre a internet;

-[Sentença 3](https://github.com/pedrosaroh/dio-lab-AI-language-azure/blob/main/images/Language%20Studio_Sentenca3.png): Opinião 70% neutra e 29% negativa, sem ter conseguido identificar o alvo da avaliação.

- A janela possui a opção de próximos passos "Next steps", porém não foi utilizada nesse caso;

- Após finalizar esse laboratório e seguindo as instruções do próprio Azure, o recurso foi deletado para não gerar custos desnecessários;

- Na página do [Azure](https://portal.azure.com/#home), clique na aba "Todos os recursos";

- Após carregar a lista de recursos, selecione os que não serão mais utilizados e em seguida o botão "Excluir" (última opção das abas disponíveis na página "Todos os recursos").


## Referências
1. [fundamentos-de-ai-mslearn](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/09-speech.html)
2. [Conhecendo o Estúdio de fala - DIO](https://web.dio.me/lab/analise-de-sentimentos-com-language-studio-no-azure-ai/learning/8add4f56-92bc-440b-9166-b1bed2d1e143?back=/track/randstad-analise-de-dados)
3. [mslearn-ai-fundamentals](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/06-text-analysis.html)
4. [GitHub Markdown](https://docs.github.com/pt/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#links)
