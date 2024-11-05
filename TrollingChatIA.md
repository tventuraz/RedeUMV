# Trolling como Ataque à Coesão do Contexto em Ambientes de Interação Humano-IA: Desafios e Estratégias de Mitigação

_por Tiago Ventura [2024.11.05]_

## **Abstract**

This paper explores the phenomenon of *trolling* in platforms involving both humans and artificial intelligences (AIs), focusing on how *trolling* can be used as an attack on context coherence. *Trolling*, understood as the practice of diverting attention and diluting the focus of a conversation, is a discursive manipulation technique aimed at interrupting the flow of thought and weakening the logical continuity of interactions. By analyzing the impact of *trolling* on AI-mediated discussions, this paper proposes strategies to mitigate this attack, based on advanced AI models, such as those utilizing the *Transformer* architecture, designed to maintain context coherence and relevance during complex conversations. In particular, we discuss how *multi-head attention*, *long-term memory*, and *context management* techniques can be used to identify and neutralize *trolling* tactics in real time.

**Keywords**: *Trolling*, Context Coherence, Artificial Intelligence, Natural Language Processing, *Transformer* Architecture, *Trolling* Mitigation, Context Management.

## **Resumo**

Este trabalho explora o fenômeno do *trolling* em plataformas de interação que envolvem tanto humanos quanto inteligências artificiais (IAs), com foco particular em como o *trolling* pode ser utilizado como um ataque à coesão do contexto. O *trolling*, entendido como a prática de desviar a atenção e diluir o foco de uma conversa, é uma técnica de manipulação discursiva que visa interromper o fluxo de pensamento e enfraquecer a continuidade lógica das interações. Ao analisar o impacto do *trolling* em discussões mediadas por IA, o artigo propõe estratégias para mitigar esse ataque, com base em modelos avançados de IA, como os que utilizam a arquitetura *Transformer*, que têm como objetivo manter a coesão e a relevância do contexto durante conversas complexas. Em particular, discutimos como a *atenção multi-cabeça*, a *memória de longo prazo* e técnicas de *gestão de contexto* podem ser usadas para identificar e neutralizar táticas de *trolling* em tempo real.

**Palavras-chave**: *Trolling*, Coesão do Contexto, Inteligência Artificial, Processamento de Linguagem Natural, Arquitetura *Transformer*, Mitigação de *Trolling*, Gestão de Contexto.

## 1. Introdução

Com o crescente uso de *inteligências artificiais* (IAs) em plataformas de comunicação, a *interação humano-IA* se tornou um componente central em diversos contextos, como assistentes virtuais, fóruns de discussão e sistemas de suporte técnico. Embora as IAs sejam projetadas para oferecer *assistência inteligente* e enriquecer as interações, elas também se tornam alvos potenciais de *trolls*, ou participantes mal-intencionados que utilizam técnicas discursivas para interromper a coesão do contexto de uma conversa. O *trolling*, nesse caso, pode ser entendido como um ataque à capacidade da IA de manter a continuidade lógica e a relevância durante o fluxo de comunicação.

O objetivo deste artigo é investigar como o *trolling* atua como um ataque à coesão do contexto em discussões mediadas por IA, além de sugerir estratégias para mitigar esse impacto e restaurar o fluxo da conversa. Para isso, discutimos o conceito de *trolling* como uma técnica de diluição do contexto, suas formas de manifestação e os desafios impostos a sistemas baseados em *processamento de linguagem natural* (PLN), como aqueles que utilizam a arquitetura *Transformer*.

## 2. Trolling como Ataque à Coesão do Contexto

### 2.1. Definição e Características do Trolling

O *trolling* em ambientes de discussão online pode ser descrito como a prática de fazer intervenções que desviam a conversa de seu rumo original, muitas vezes com o intuito de causar distração, conflito ou confusão (*Binns*, 2022). Em ambientes de interação humano-IA, o *trolling* tem um impacto particularmente significativo na coesão do contexto, que é a capacidade de uma conversa manter-se relevante e lógica ao longo do tempo.

A coesão do contexto em uma conversa exige que todos os participantes — sejam humanos ou IAs — sigam uma linha de raciocínio lógica e se concentrem em tópicos pertinentes. Quando um troll interfere com palavras-chave irrelevantes, questões filosóficas vagas ou provocações, ele desestabiliza esse fluxo, criando distrações que diluem a qualidade do debate (*Vaswani et al.*, 2017).

### 2.2. Tipos de Trolling

Existem várias formas de *trolling* que podem afetar a coesão do contexto:

- **Introdução de palavras-chave irrelevantes**: Palavras ou expressões como "alienígenas" ou "vacinas" podem ser inseridas em uma conversa sobre um tema técnico, criando um desvio que obriga os participantes a discutir tópicos sem relação com o tema central (*Radford et al.*, 2019).

- **Desvios gradativos**: O troll pode começar com uma pequena interrupção que, com o tempo, amplia o escopo da discussão para tópicos vagos ou irrelevantes, como "tecnologia" ou "energia", em uma conversa sobre mudanças climáticas, por exemplo (*Hochreiter & Schmidhuber*, 1997).

- **Questões filosóficas sem resolução prática**: Em discussões técnicas ou éticas, um troll pode levantar questões como "O que é a verdade?" ou "Uma IA pode ser moral?", que, embora interessantes, não contribuem para o avanço da conversa e servem apenas para diluir o foco (*Binns*, 2022).

### 2.3. Impacto do Trolling na IA

Para IAs que utilizam modelos como *Transformers*, o *trolling* pode gerar sérios desafios. As IAs são projetadas para processar grandes volumes de dados e manter a coerência do contexto por meio de mecanismos de *atenção*. No entanto, palavras-chave desconexas ou referências irrelevantes podem interferir na capacidade da IA de manter a fluidez da conversa, fazendo com que ela se desvie de seu raciocínio lógico e gere respostas que parecem inadequadas ou fora de lugar para o contexto (*Vaswani et al.*, 2017). Além disso, a IA pode ser induzida a processar o conteúdo irrelevante como parte do contexto em andamento, comprometendo a qualidade das respostas e o engajamento dos participantes humanos na conversa.

## 3. Estratégias para Mitigar o Trolling e Manter a Coesão do Contexto

### 3.1. Mecanismos de Atenção Multi-Cabeça

A arquitetura *Transformer*, amplamente utilizada em modelos como o GPT, utiliza *atenção multi-cabeça* para permitir que a IA se concentre em diferentes partes de uma entrada de dados ao mesmo tempo. Isso permite que o modelo avalie várias perspectivas e relacione palavras ou frases de forma mais eficaz (*Vaswani et al.*, 2017). No contexto do *trolling*, isso pode ser usado para focar nas partes do texto que são realmente relevantes e ignorar aquelas que são distrações. A *atenção multi-cabeça* ajuda a IA a distinguir rapidamente entre conteúdo relevante e irrelevante, mantendo o foco no contexto central.

### 3.2. Filtragem de Relevância Contextual

Outra estratégia importante é o uso de filtros de relevância, onde o modelo é treinado para ignorar termos ou tópicos que não se conectam ao assunto central da conversa. Por exemplo, se a conversa é sobre ética em IA, o modelo pode ser treinado para reconhecer e rejeitar entradas que não se relacionam diretamente com esse tópico, mesmo que envolvam palavras-chave que, à primeira vista, pareçam pertinentes (*Radford et al.*, 2019).

### 3.3. Redirecionamento da Conversa

Em vez de permitir que o *trolling* se espalhe, a IA pode empregar estratégias de redirecionamento para trazer a conversa de volta ao tópico original. Isso pode ser feito por meio de respostas que reafirmem o foco do debate, como: "Vamos voltar à questão central sobre ética em IA" ou "Embora isso seja interessante, nosso foco agora é a relação entre IA e privacidade" (*Binns*, 2022). Ao estabelecer claramente o propósito da conversa, a IA ajuda a restaurar a coesão do contexto.

### 3.4. Análise de Intenção e Detecção de Manipulação

Uma técnica mais avançada envolve a análise de intenção por meio de modelos de IA treinados para identificar padrões de manipulação discursiva. Esses modelos podem ser capazes de detectar quando uma intervenção é, de fato, uma tentativa deliberada de desviar a conversa, em vez de uma contribuição genuína para o debate. A IA pode então interromper a manipulação ou redirecionar a atenção de volta para o tema central, sem cair na armadilha do troll (*Hochreiter & Schmidhuber*, 1997).

## 4. Conclusões

O *trolling*, quando usado como um ataque à coesão do contexto em interações humano-IA, representa um desafio significativo para a manutenção de um diálogo produtivo e focado. Este estudo abordou as formas como o *trolling* pode interromper o fluxo de pensamento e diluir o foco de uma conversa, prejudicando a qualidade da comunicação. No entanto, com

 a aplicação de técnicas como *atenção multi-cabeça*, filtragem de relevância, redirecionamento da conversa e análise de intenção, as IAs podem ser mais bem preparadas para mitigar esses ataques e preservar a integridade do debate.

Pesquisas futuras podem expandir essas estratégias de mitigação, explorando novos métodos de detecção de *trolling* em tempo real e desenvolvendo modelos de IA mais robustos para garantir que a coesão do contexto seja mantida, mesmo em ambientes altamente dinâmicos e manipulativos.


### Referências

- *Vaswani, A., Shazeer, N., Parmar, N., Uszkoreit, J., Jones, L., Gomez, A. N., Kaiser, Ł., & Polosukhin, I.* (2017). Attention is all you need. *Proceedings of NIPS*.
- *Radford, A., Wu, J., Amodei, D., & Clark, J.* (2019). Language models are unsupervised multitask learners. *OpenAI Blog*.
- *Hochreiter, S., & Schmidhuber, J.* (1997). Long short-term memory. *Neural Computation*.
- *Binns, R.* (2022). The Ethics of Artificial Intelligence and Manipulation. *Journal of AI Ethics*.
