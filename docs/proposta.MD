## Proposta Inicial do Jogo

> Versão preenchida a partir do template oficial da disciplina. O nome do jogo e os controles ainda são provisórios; os integrantes podem ajustar a proposta antes da entrega.

## 1. Nome provisório do jogo

**Nome:** Campanha Brasileira

## 2. Integrantes do grupo

- Arthur Gabriel Rezende Rocha
- Alissa Aguiar Fernandes
- Gabriel Henrique Lourenço Pires
- Brian Marcondes Braga

## 3. Tema escolhido

**Tema:** Inteligência Artificial no Cotidiano e Uso Responsável, com foco no uso da IA em campanhas políticas, na avaliação crítica de informações e na tomada de decisões cidadãs.

**Como esse tema se relaciona com o jogo?**

O jogador concorre à Presidência e enfrenta situações de campanha relacionadas à IA, como avaliar conteúdos possivelmente gerados ou manipulados, analisar propostas e escolher comunicações responsáveis. As respostas afetam o apoio popular, então o tema influencia diretamente as regras e o progresso do jogo.

## 4. Tipo de jogo

**Tipo escolhido:** Jogo educativo de perguntas e respostas com escolhas, decisões de campanha e progressão por territórios. A proposta visual em pixel art é provisória.

## 5. Descrição geral do jogo

O jogador assume o papel de uma pessoa candidata à Presidência do Brasil. Para conquistar apoio e avançar na campanha, responde a 20 missões sobre Inteligência Artificial e seu uso responsável. As missões podem aparecer como debates eleitorais, publicações em redes sociais, propostas de governo e desafios para avaliar a origem e a confiabilidade de imagens, textos ou notícias.

O mapa do jogo terá quatro territórios fictícios de campanha: Norte, Sul, Leste e Oeste. A distribuição prevista é Norte (4 missões), Sul (5), Leste (5) e Oeste (6). O jogador escolhe por qual território começar e libera outros conforme conquista apoio. A IA será representada por situações e respostas simuladas no próprio jogo; não haverá conexão com serviços externos nem necessidade de treinar ou consultar um modelo real.

## 6. Objetivo do jogador

Conquistar apoio popular suficiente para vencer a eleição e chegar à Presidência, tomando decisões fundamentadas sobre IA, cidadania e uso responsável da tecnologia.

## 7. Regras principais

- O jogador escolhe o território inicial; os outros territórios são liberados ao alcançar pelo menos 40% do apoio máximo possível no território atual.
- Cada resposta correta acrescenta 20 pontos de apoio; cada resposta incorreta reduz 10 pontos.
- O jogo terá no máximo 20 missões, distribuídas entre os quatro territórios; missões já concluídas não poderão ser repetidas.
- Depois de liberar outros territórios, o jogador poderá voltar a territórios anteriores para realizar missões que ainda não concluiu.
- A meta para vencer é alcançar 55% da pontuação máxima nacional possível antes de acabar o limite de missões.

## 8. Condição de vitória

A partida é vencida quando o jogador alcança pelo menos 55% da pontuação máxima nacional possível. Com 20 missões valendo até 20 pontos cada, o máximo é 400 pontos; portanto, a meta inicial é 220 pontos de apoio.

## 9. Condição de derrota ou encerramento

A partida termina em derrota se as 20 missões forem concluídas sem alcançar 220 pontos de apoio. A partida também se encerra quando o jogador vence a eleição. A porcentagem de apoio será calculada em relação ao máximo de pontos possível, conforme as regras acima.

## 10. Elementos previstos no jogo

- **Personagem ou elemento principal:** pessoa candidata controlada pelo jogador e um mapa de campanha.
- **Obstáculos ou desafios:** perguntas e situações sobre confiabilidade de informações, conteúdos gerados por IA, privacidade, vieses e decisões responsáveis.
- **Itens ou objetos de interação:** cartões de missão e alternativas de resposta; telas de debate, publicação em rede social, proposta de governo e análise de conteúdo.
- **Pontuação, vidas, tempo ou progresso:** pontos de apoio popular, barra de progresso nacional, territórios liberados e contador de missões concluídas.

## 11. Controles previstos

**Controles:** clique do mouse para escolher uma alternativa; Enter para confirmar; Escape para voltar ao menu ou encerrar. Esses controles são uma proposta inicial e podem ser ajustados durante a implementação.

## 12. Principais dificuldades esperadas

- Criar perguntas e alternativas claras, equilibradas e ligadas ao uso responsável da IA.
- Organizar a pontuação, o desbloqueio dos territórios e o limite de 20 missões sem inconsistências.
- Exibir textos e alternativas de forma legível na janela do Pygame e testar as regras do jogo.

## 13. Escopo mínimo para a entrega final

Uma versão executável em Python e Pygame com tela inicial, mapa com quatro territórios, seleção de missões, perguntas de múltipla escolha, pontuação de apoio, liberação de territórios conforme a regra de 40%, limite total de 20 missões e finais de vitória ou derrota conforme a meta de 55%. O conteúdo poderá ser armazenado em listas e dicionários; funções separadas cuidarão da exibição, seleção de respostas, atualização da pontuação e verificação do estado da partida. O jogo deve funcionar sem conexão à internet e sem uso de IA real.

## 14. Possíveis melhorias, caso haja tempo

- Animações e efeitos sonoros em estilo pixel art.
- Tela de histórico da campanha com respostas e variação do apoio popular.
- Mais variedade visual para os territórios e os tipos de missão.

## 15. Organização inicial do código, dados e testes

A estrutura seguirá o template da disciplina: `main.py` iniciará o jogo; `src/` reunirá as funções de telas, missões e regras; `data/` guardará perguntas e, se necessário, o progresso local; `assets/` conterá recursos visuais e sonoros; `tests/` terá testes para pontuação, cálculo do apoio, desbloqueio de territórios e condições de vitória e derrota.

As missões podem ser representadas por listas e dicionários em arquivos locais. Imagens, fontes, sons ou trechos de código externos usados pelo grupo deverão ter a origem e, quando disponível, a licença registradas no `README.md`.

## 16. Declaração de originalidade

**Para validação do grupo antes da entrega:** confirmar que a proposta, os textos das missões e as mecânicas foram elaborados pelo grupo; que o template oficial será usado como base; e que qualquer recurso externo será identificado no `README.md`. O projeto não deve reproduzir integralmente um jogo existente ou um tutorial.