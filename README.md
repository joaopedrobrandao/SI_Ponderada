# Plano de Cutover

&emsp;&emsp; O objetivo desse exercício é encontrar um exemplo de Plano de Cutover e realizar a sua análise. Entre os pontos principais, estão a descrição do projeto; Seus principais elementos e seus pontos positivos e negativos.<p>

## Resumo

&emsp;&emsp; O projeto descrito no artigo [A framework for cut-over management ](https://peerj.com/articles/cs-29/#project-specific-cut-over-versus-release-specific-rollout)  trata de uma abordagem estruturada para gerenciar transições de sistemas (cut-overs). O objetivo é minimizar interrupções e riscos, garantindo uma transição suave de um sistema para outro por meio de um plano divido em fases. A escolha de uma pesquisa para a atividade foi com o intuito de tirar o melhor proveito das perguntas feitas na atividade passada.

&emsp;&emsp; Na imagem a seguir demonstra a estrutura que um projeto semi-ágil de release para produção em que o projeto pode ser aplicado.<p>

<p align="center">Imagem 1 - semi-agile release model</p>

<img src="assets\cutover.jpg">

<p align="center">Fonte: A framework for cut-over management</p>

## Elementos

&emsp;&emsp; Esse plano contém três elementos principais. O primeiro, assim como no [vídeo](https://www.youtube.com/watch?v=oZexFdrojko) disponibilizado no autoestudo, é o planejamento pré-cutover, que envolve garantir que todos os componentes técnicos, partes interessadas e planos de contingência estejam prontos e além disso, estejam alinhados com os resultados esperados. 

&emsp;&emsp; O segundo é a execução, onde ocorre a troca de sistemas. As equipes técnicas gerenciam a mudança em tempo real, solucionando problemas que surgem no processo, sempre mantendo em mente o plano traçado antes das operações.

&emsp;&emsp; O último é a avaliação pós-cutover, em que a funcionalidade do sistema é avaliada e problemas identificados são resolvidos. A preparação para possíveis problemas na transição de Q.A (quality assurance) para a produção devem ser mapeados e classificados de acordo com seu impacto no resto do projeto.

## Pontos Positivos

- **Mitigação de Riscos:** Reduz a chance de falhas operacionais, garantindo que as funções críticas continuem a funcionar durante a transição.

- **Abordagem Estruturada:** Passos claros para cada etapa da transição, o que facilita a execução por toda a equipe envolvida.

- **Revisão Pós-Cutover:** Garante que problemas sejam identificados e resolvidos rapidamente, promovendo melhorias contínuas.

&emsp;&emsp; Esses aspectos reforçam a confiabilidade do sistema ao longo do processo de transição, criando um ambiente controlado e de menor risco.

## Pontos Negativos

- **Intensivo em Recursos:** Exige muito tempo, equipe e esforço em todas as fases do processo.

- **omplexidade:** Pode ser desnecessariamente complicado para sistemas menores, dificultando sua aplicação.

- **Possível Tempo de Inatividade:** Mesmo com um planejamento detalhado, interrupções podem ocorrer, impactando as operações.

&emsp;&emsp; Esses fatores podem aumentar os custos e o tempo da implementação, além de trazer complexidade excessiva para organizações menores, prejudicando a eficácia do plano.
