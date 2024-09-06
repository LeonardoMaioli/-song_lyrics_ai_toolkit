# Song Lyrics AI Toolkit 🎶
> Status: em andamento

Alunos:
*   Gustavo Bauer Nogueira
*   Leonardo Severgnine Maioli
*   Thiago Alexandre Paiares e Silva

## _índice_

- <a href="#intro">Introdução</a>
- <a href="#tecnologias-utilizadas">Tecnologias utilizadas</a>
- <a href="#codigo">Código</a>
- <a href="#funcionamento">Funcionamento/a>
- <a href="#exemplo">Exemplo de Resultado</a>

## _Introdução_

**Song Lyrics AI Toolkit** é projeto desenvolvido por alunos da UFABC no decorrer da disciplina Processamento de Linguagem Natural (PLN) que oferece ferramentas baseadas em IA para análise, extração e geração de informações de letras de músicas. 

Utilizando técnicas de PLN e geração de imagens, o projeto **Song Lyrics AI Toolkit** permite realizar tarefas como:

- Buscar letras de músicas pelo nome da música e cantor(a)/banda.
- Traduzir a letra de uma música do idioma original para um idioma alvo.
- Identificar emoções existentes na letra da música.
- Identificar as palavras-chave da letra da música.
- Sintetizar a letra de uma música em um pequeno resumo.
- Identificar o gênero da música.
- Geração de arte para capa de álbum inspirada na letra da música.

Um exemplo da realização dessas tarefas é mostrado na seção exemplos.

Com foco na exploração criativa e analítica de letras de músicas, este toolkit possibilita novas formas de interação com composições musicais.

## _Tecnologias utilizadas_

A equipe utilizou a linguagem **Python** com o framework **LangChain** junto de modelos da **Groq* e *OpenAI** para o desenvolvimento do projeto. O modelo _*llama-3.1-70b-versatil*_ da Groq foi utilizado para quase todas as ferramentas com exceção para a ferramenta de geração de arte para capa de álbum inspirada na letra da música, na qual foi utilizado o modelo dall-e-3 da OpenaAI.

Para obtenção das letras das músicas a partir do nome da música e cantor(a)/banda foi utilizada a API lyrics.ovh, cuja documentação pode ser acessada [aqui](lyricsovh.docs.apiary.io)!

## _Código_

O código desenvolvido e as explicações detalhadas de cada etapa estão disponíveis no formato de um notebook Python [aqui]()!

## _Funcionamento_

Os resultados obtidos podem ser melhor explorados no código citado anteriormente. Na figura abaixo tem-se uma pequena amostra dos dados sintéticos obtidos para transações fraudulentas.
![Dados Sintéticos para Transações Fraudulentas](images/synthetic_data_example.png)

## _Exemplo de Resultado_

Para demonstrar um exemplo de resultado, segue as saídas obtidas para a música **Viva La Vida** da banda **Coldplay** para cada uma das ferramentas.

- **Tradução**:
  
- **Identificação das emoções:**
  
- **Identificação das palavras-chave:**
  
- **Resumo:**
  
- **Identificação do gênero:**
  
- **Arte para capa de álbum:**

Para visualizar mais exemplos de arte para capa de álbum geradas, você pode clicar [aqui]().



