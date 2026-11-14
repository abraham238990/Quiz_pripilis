# ✨ O Oráculo Secreto das Prililis ✨

<p align="center">
  <i>Uma experiência narrativa e interativa em Python na qual você se transforma em um prilili durante uma noite mágica, do pôr do sol à alvorada, para descobrir qual essência vive dentro de você.</i>
  <br><br>
  <i>"Piri katiki ña ña me"</i>
</p>

## Sobre o projeto

**O Oráculo Secreto das Prililis** é um teste de personalidade interativo desenvolvido em Python, utilizando Jupyter Notebook. A experiência combina narrativa, escolhas pessoais e elementos visuais para criar uma jornada pelo universo mágico dos prililis.

Durante a aventura, o jogador percorre **oito momentos de uma noite encantada**, desde o pôr do sol até o amanhecer. Em cada etapa, são apresentadas situações e escolhas que ajudam a revelar sua personalidade e a essência mágica que mais combina com você.

Ao iniciar a jornada, o jogador pode informar seu nome e receber um nome mágico de prilili, criado a partir dele. Conforme as escolhas são feitas, sua aura muda de cor e o cenário acompanha a passagem das horas, criando uma experiência visual que evolui junto com a história.

Ao final da aventura, quando a noite chega ao fim, o jogador recebe uma **ficha de personalidade completa**, contendo suas cinco essências, a distribuição percentual de cada uma, seu perfil predominante e uma descrição de sua identidade mágica.

O resultado também pode ser exportado como um arquivo HTML independente, permitindo guardar e compartilhar sua ficha.

Toda a experiência é construída com recursos nativos do Python e elementos visuais em HTML, CSS e SVG, sem depender de bibliotecas externas complexas.

---

## As Cinco Prililis

O universo do oráculo possui cinco personalidades mágicas, cada uma representando diferentes características, comportamentos e formas de enxergar o mundo.

Durante a jornada, cada escolha contribui para a formação da sua aura. As respostas podem favorecer uma essência principal e também revelar características de outras personalidades, formando uma combinação única.

| Prilili | Título | Personalidade e essência mágica |
|---|---|---|
| **Prilili** | *A Guardiã dos Sonhos* | Representa a delicadeza, a empatia e a esperança. Sua magia faz florescer aquilo que parecia impossível e encontra beleza até nos pequenos detalhes. |
| **Lilika** | *A Tecelã dos Mistérios* | Representa a curiosidade, a intuição e a observação. Sua magia permite descobrir segredos escondidos e enxergar aquilo que muitas vezes passa despercebido. |
| **Nili** | *O Espírito Livre da Floresta* | Representa a independência, a liberdade e a leveza. Sua magia encontra novos caminhos e transforma a vontade de explorar em grandes descobertas. |
| **Priki** | *A Centelha Indomável* | Representa a coragem, a espontaneidade e a energia. Sua magia transforma desafios em oportunidades e encontra força para enfrentar o inesperado. |
| **Kiki** | *A Estrela Brincalhona* | Representa o humor, a irreverência e a alegria. Sua magia espalha diversão, quebra a rotina e mostra que até os momentos mais sérios podem guardar uma surpresa. |

Cada jogador possui uma combinação dessas cinco essências. Isso significa que o resultado não se limita a uma única personalidade: ele também revela características complementares que tornam cada prilili diferente dos demais.

---

## Como o Notebook está estruturado

O código foi organizado em **quatro células principais**, cada uma responsável por uma parte da experiência. Essa divisão facilita a compreensão, a manutenção e a personalização do projeto.

- **Célula 1 — Configurações e ferramentas:** reúne os principais ajustes da experiência, como a pontuação atribuída às respostas, o tempo de espera entre os textos e o nome do arquivo utilizado para salvar o resultado. Também contém funções matemáticas responsáveis por calcular a porcentagem de cada personalidade.

- **Célula 2 — Universo dos Prililis:** concentra as informações sobre as cinco personalidades, a história do povo prilili e o conjunto de perguntas utilizadas durante a jornada. As perguntas são selecionadas de maneira variável, fazendo com que cada partida possa apresentar uma sequência diferente. Também existem perguntas especiais para resolver empates entre personalidades.

- **Célula 3 — Identidade visual:** responsável pela aparência do oráculo. Define as cores, fontes, animações e elementos gráficos da experiência. Inclui um céu estrelado, uma floresta com silhuetas geradas pelo código e símbolos mágicos representados por desenhos vetoriais (SVG).

- **Célula 4 — Funcionamento da experiência:** reúne a lógica principal do jogo. É responsável por gerar os nomes mágicos, atualizar as cores da aura conforme as escolhas, controlar a navegação entre as perguntas e calcular o resultado final. Também permite voltar para uma pergunta anterior, encerrar a jornada e acessar as opções disponíveis após o término do jogo.

---

## Requisitos e execução

O projeto foi desenvolvido para funcionar sem a necessidade de instalar bibliotecas externas adicionais, utilizando os recursos disponíveis no próprio Python e no ambiente Jupyter.

**Requisitos:**
- Python 3.8 ou superior.
- JupyterLab ou Jupyter Notebook.
- IPython, utilizado para exibir os elementos visuais e interativos.

### Como jogar

1. Abra o notebook no **JupyterLab** ou **Jupyter Notebook**.
2. Execute todas as células na ordem apresentada, utilizando a opção **Run All**. A última célula inicia a experiência por meio da função `iniciar()`.
3. Digite seu nome para receber uma identidade mágica personalizada. Caso prefira, basta pressionar `ENTER` para continuar sem informar um nome.
4. Acompanhe a narrativa e responda às situações apresentadas escolhendo uma das cinco alternativas disponíveis, digitando um número de `1` a `5`.
5. Durante a jornada, você também pode utilizar os seguintes comandos:
   - **`v`** — retorna à etapa anterior, permitindo revisar e refazer sua última escolha.
   - **`s`** — encerra a jornada a qualquer momento.
6. Ao chegar à alvorada, você receberá sua ficha de personalidade com a distribuição das cinco essências e a descrição do seu perfil mágico.
7. No menu final, será possível conhecer melhor as outras prililis, descobrir mais sobre o povo da floresta, iniciar uma nova partida ou exportar sua ficha em HTML.

---

## Nota

> *O Oráculo Secreto das Prililis é uma criação artística e interativa, desenvolvida como uma brincadeira de personalidade inspirada no universo dos prililis. As personalidades, histórias, características e resultados apresentados fazem parte da interpretação criativa do projeto e não representam necessariamente uma história oficial.*

---

## Autor

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/FipaLipe">
        <img src="https://avatars.githubusercontent.com/u/178325127?v=4"
             width="100px;"
             alt="Perfil de Abraham Contreras no GitHub"
             style="border-radius:50%;"><br>
        <b>Abraham Contreras</b>
      </a>
    </td>
  </tr>
</table>
