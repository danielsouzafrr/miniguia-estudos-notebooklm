# 🎵 Miniguia de Estudos: Música e Contracultura

> **Projeto desenvolvido para a DIO** utilizando **Gemini Notebook** para curadoria, síntese e roteirização pedagógica.

---

## 📌 Contexto e Objetivos

Este repositório reúne a documentação e os resultados do estudo sobre **Música e Contracultura**, com foco na criação de uma simulação de aula de 50 minutos para o 9º ano do Ensino Fundamental (recortada em um vídeo de 5 a 7 minutos).

### Objetivos de Estudo
1. **Compreender o papel da música** como ferramenta de protesto, resistência e transformação social durante as décadas de 1960 e 1970 no cenário nacional e internacional.
2. **Explorar o uso de IAs (NotebookLM e Gemini)** para curadoria de fontes abertas, checagem de fatos e síntese de documentos.
3. **Elaborar e roteirizar uma videoaula**, utilizando técnicas de Engenharia de Prompts para ajustar linguagem, tom didático e engajamento para estudantes de 14 anos.

---

## 📚 Curadoria de Fontes

Foram selecionadas e analisadas as seguintes fontes abertas para alimentar a base do projeto:

* **[PDF/Slide]** [Música e Contracultura - Arte 9º Ano](https://conhecimento.fgv.br/sites/default/files/concursos/arte-9o-ano-aula-3.pdf) — Material didático sobre manifestações artísticas e cultura.
* **[PDF/Artigo]** [CULTURA E CONTRACULTURA: FERLINGHETTI](https://revistas.usp.br/criacaoecritica/article/download/83640/91601/126086) — Análise crítica sobre cultura e contracultura.
* **[Artigo Web]** [National Geographic Brasil - A Guerra do Vietnã](https://www.nationalgeographicbrasil.com/historia/2023/09/o-que-foi-a-guerra-do-vietna-e-quais-as-suas-causas) — Contexto histórico internacional dos conflitos e movimentos pacifistas.
* **[Vídeo/Aula]** [PSS SEDUC-SP 2027: Tudo o que você precisa saber sobre a VIDEOAULA!](https://www.youtube.com/watch?v=-MGOGT5sKV4) — Referência audiovisual sobre o o formato da videoaula.

---

## 🛠️ Engenharia de Prompts e "Cicatrizes"

O processo de construção do roteiro passou por três iterações principais até atingir o resultado esperado.

### Histórico de Testes

* **1ª Tentativa (Prompt Genérico):** *"Me ajude a criar o modelo da videoaula para a prova"*
  * **Resultado:** Resposta muito vaga, com dicas superficiais e pouca produção de roteiro. Faltaram parâmetros de tempo, público e formato.

* **2ª Tentativa (Ajuste de Escopo):** *"Escreva o roteiro da videoaula, mas ela não precisa começar e terminar em 5 ou 7 minutos, o objetivo é simular uma aula do nono ano do ensino fundamental."*
  * **Resultado:** Estrutura mais alinhada ao objetivo, mas a linguagem permaneceu engessada e acadêmica para alunos de 14 anos.

* **3ª Tentativa (Persona + Público + Tom):** *"Aja como um professor especialista em história da música. Crie o roteiro de videoaula simulando uma aula de 50 minutos para alunos de 14 anos do nono ano do ensino fundamental da rede pública. Utilize tom respeitoso e descontraído para deixar a aula dinâmica."*
  * **Resultado:** Sucesso na geração. O roteiro atingiu uma linguagem acessível, com dinâmicas adequadas à faixa etária e tom descontraído.

### Lições Aprendidas & Troubleshooting ("Cicatrizes")

* **Gestão do Tempo e Formato:** A IA inicialmente se confundia entre criar um vídeo curto ou uma aula expositiva longa. A solução foi orientar a IA a criar a estrutura completa de uma aula de 50 minutos, destacando o recorte central de 5 a 7 minutos para gravação.
* **Mitigação de Alucinações:** A restrição das buscas às fontes carregadas no caderno permitiu que fatos históricos e conceitos da teoria musical fossem citados com precisão e sem anacronismos.

---

## 📖 Miniguia de Estudo (Entrega Final)

### 1. Resumo Estruturado do Assunto

* **Guerra do Vietnã e Geopolítica:** Conflito central da Guerra Fria (1954-1975) motivado pela oposição entre o Norte comunista e o Sul apoiado pelos EUA sob a "Teoria do Dominó". Causou alto custo humano e impulsionou movimentos pacifistas globais.
* **Contracultura e Música de Protesto:** Movimentos como a Geração Beat e os Hippies questionaram o conservadorismo e as guerras. A canção "Imagine" de John Lennon tornou-se um marco da promoção da paz e da não-violência.
* **Diretrizes para Videoaulas (Prática Docente):** Gravação em enquadramento horizontal (5 a 7 min), simulação de interação com estudantes fictícios e foco na clareza, uso de metodologias ativas e antecipação de dúvidas dos alunos.
* **Fundamentos do Som e Análise Musical:** O estudo pedagógico da música envolve a identificação do **timbre** (identidade e fonte do som) e da **altura** (frequências agudas ou graves) para o desenvolvimento da escuta crítica.

---

### 2. Glossário de Conceitos-Chave

| Termo | Definição Resumida |
| :--- | :--- |
| **Contracultura** | Movimento social que questiona os valores e normas da cultura dominante. |
| **Guerra do Vietnã** | Conflito (1954-1975) inserido na Guerra Fria que catalisou reações culturais e movimentos pacifistas. |
| **Geração Beat & Movimento Hippie** | Movimentos poéticos e comportamentais dos anos 50 a 70 focados na paz, liberdade e contestação. |
| **Canção de Protesto** | Gênero musical com letras voltadas à crítica política, resistência e justiça social. |
| **Teoria do Dominó** | Hipótese geopolítica norte-americana que previa a expansão do comunismo em cadeia no Sudeste Asiático. |
| **Timbre e Altura** | Propriedades físicas do som que definem, respectivamente, a "identidade" do som e sua frequência (grave/agudo). |
| **Metodologias Ativas** | Estratégias de ensino que colocam o estudante como protagonista da aprendizagem. |
| **Antecipação de Dúvidas** | Habilidade docente de prever dificuldades dos alunos e apresentar soluções durante a explicação. |

---

### 3. Prompts Reutilizáveis para Estudos e Revisões

Estes prompts foram estruturados para apoiar a criação e revisão de conteúdos pedagógicos sobre o tema:

#### Prompt 1: Abordagem "Ponte Temporal" (Passado e Presente)
> *"Aja como um comunicador jovem e pesquisador musical. Crie o roteiro de uma videoaula de 6 minutos sobre Música e Contracultura para jovens de 14 anos, fazendo pontes entre as canções de protesto dos anos 60/70 e os gêneros urbanos de hoje (como o Rap, Trap e Funk consciente). O tom deve ser curioso, sem preconceitos musicais e provocativo."*

#### Prompt 2: Abordagem "Direção de Arte / Edição Dinâmica"
> *"Aja como um roteirista de canais educativos de sucesso no YouTube (estilo Nostalgia ou Manual do Mundo). Crie um roteiro de videoaula de 50 minutos sobre 'Música e Contracultura'. Estruture o texto em duas colunas: [CENA / ÁUDIO DE FUNDO] e [FALA DO NARRADOR]. Inclua sugestões de efeitos sonoros, inserções de fotos históricas e momentos de pausa dramática."*

#### Prompt 3: Abordagem "Investigation / Decodificando Metáforas"
> *"Aja como um detetive cultural. Crie uma introdução envolvente de 2 minutos para a videoaula, mostrando aos alunos de 14 anos como os compositores da MPB enganavam a censura na Ditadura Militar usando 'códigos secretos' e metáforas nas letras (ex: a palavra 'Cálice' soar como 'Cale-se'). O objetivo é fazer os alunos se sentirem decifrando uma mensagem oculta."*
> *"Aja como um detetive cultural. Crie uma introdução envolvente de 2 minutos para a videoaula, mostrando aos alunos de 14 anos como os compositores da MPB enganavam a censura na Ditadura Militar usando 'códigos secretos' e metáforas nas letras (ex: a palavra 'Cálice' soar como 'Cale-se'). O objetivo é fazer os alunos se sentirem decifrando uma mensagem oculta."*
