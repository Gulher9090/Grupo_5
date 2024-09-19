<h1>Gerenciamento de Configuração de Software</h1>
<h2>Prof. Daniel Callegari, 2024/2</h2>
<h3>Trabalho 1 – Prática com Git em Times</h3>
O trabalho consiste em observar os requisitos do trabalho, implementar uma solução seguindo os conceitos
vistos em aula e produzir um relatório final.
O trabalho deverá ser realizado em times compostos por 10 membros. Cópias ou tentativas de fraude
resultarão em nota zero para todos os envolvidos.
Data de entrega: 11/10/2024
<h3>Atividades</h3>
Cada time deverá:

 - 1. Cada grupo deve criar um único repositório no GitHub. O repositório deve ser público e seu
endereço deve ser copiado para o relatório.
 - 2. Definir e descrever claramente o seu processo de branching (fluxo de trabalho), com base em
um dos fluxos estudados.
 - 3. Descrever as regras do fluxo de trabalho no relatório e segui-las ao longo da implementação.
   - A. O professor verificará a participação de cada membro do grupo através do log do git no
repositório do time. Cada aluno deverá participar de pelo menos duas features ou
correções de bug, com uma contribuição substancial.
   - B. As submissões ao repositório no GitHub deverão ocorrer via Pull Requests.
   - C. Os movimentos no repositório deverão acontecer até no máximo a data de entrega.
Serão desconsiderados os trabalhos que tiverem movimentos depois da data de entrega.
- 4. Escrever o software a partir do repositório inicial criado de acordo com os requisitos e com o
fluxo de trabalho definido pelo time.
- 5. Entregar um relatório via Moodle até a data limite. O relatório deverá conter:
   - A. Folha de rosto com nomes completos dos componentes do time e seus nomes de
usuário no GitHub.
   - B. Link para o repositório público no GitHub.
   - C. Descrição clara do fluxo de trabalho adotado (pode ser uma variação dos fluxos vistos
em aula, adaptado pelo time).
   - D. Demonstração de que o time seguiu o fluxo definido. Deve conter capturas de tela e
descrições que deixem isto claro. (sugere-se capturar o Network graph do GitHub:
Insights/Network)
   - E. Tabela com os nomes dos componentes do grupo e suas contribuições (ex. links para
commits ou pull-requests registrados no GitHub).
   - F. Conclusão do grupo contendo reflexões sobre as dificuldades encontradas, como foram
superadas e quais as lições aprendidas. A conclusão deverá conter uma nota de
autoavaliação do grupo (0,0 a 10,0), e também cada aluno deverá escrever a sua
autoavaliação e se atribuir uma nota.
<h3>Critérios de Avaliação</h3>
Avaliação: 30% da nota é resultado da contribuição individual e 70% da nota advém do resultado do grupo.
Cada aluno deverá garantir que seu nome/usuário conste (em bom número de ocorrências) nos commits e
linhas de código do histórico do git, confirmando a sua participação no processo de desenvolvimento,
seguindo o fluxo de trabalho definido pelo grupo.
 - Dica: utilize o comando abaixo para uma métrica básica por usuário:
  - git shortlog -s -n --all --no-merges
<h3>Item Pontos</h3>
Descrição clara do fluxo de trabalho adotado pelo
grupo -- nomes de branches, regras de uso,
comandos utilizados, exemplos, etc.
3,0
Demonstração de que o grupo seguiu o fluxo de
trabalho definido – capturas de tela, descrições,
anotações sobre trechos de código, log do git, etc.
4,0
Qualidade geral do relatório, em atendimento os
itens listados no item Atividades.
2,0
Conclusão com autoavaliação do grupo. 1,0
TOTAL 10,0
<h3>Requisitos Gerais</h3>
 - 1. Deseja-se um sistema para gerenciar itens e trocas de itens entre jogadores.
 - 2. O sistema deverá ser implementado em Java Console /ou/ Web Puro (apenas
HTML+CSS+Javascript). Não utilizar frameworks ou outras dependências. A ideia é ter a base de
código o mais simples possível. Cuidar para que todos os membros do time conheçam a(s)
linguagem(s) escolhida(s).
 - 3. Não implementar um mecanismo de persistência de dados. O sistema deverá manter dados
apenas em memória durante a execução.
 - 4. Não implementar um mecanismo de login. No entanto, deverá ser possível identificar/alterar o
usuário/funcionário que está usando o sistema no momento.
 - 5. O sistema deverá iniciar com dados já preenchidos (em bom número e de boa qualidade), de
forma a facilitar os testes.
<h3>Detalhamento</h3>
 - O sistema deverá permitir que jogadores se inscrevam, cadastrem itens de jogos (físicos ou virtuais),
proponham e façam trocas de itens. Cada jogador se inscreve com seu email, nome completo e pin de 6
dígitos. Cada jogador poderá gerenciar seus itens (cadastrar ou excluir). Não será possível editar um item.
Cada item deverá ser composto de um id (gerado automaticamente pelo sistema), o nome do item, uma
descrição, um tipo (sejam criativos!) e um valor aproximado em Reais. Cada jogador poderá consultar
quaisquer itens dos demais jogadores. Qualquer jogador poderá abrir uma proposta de troca, indicando um
item seu e um item de algum outro jogador. Quando o outro jogador entrar no sistema, as propostas de
trocas que o envolvem devem aparecer, junto com opções de aceitar ou declinar a proposta. Aceitando, o
sistema automaticamente troca a propriedade dos dois itens.
<h3>Funcionalidades desejadas</h3>
 - 1) O sistema deverá permitir que um novo jogador se cadastre no sistema. O sistema deverá permitir
que um jogador entre no sistema com seu email e pin.
 - 2) O sistema deverá permitir a um jogador listar os seus próprios itens, em ordem alfabética.
 - 3) O sistema deverá permitir a um jogador listar os itens dos demais jogadores, por ordem de preço.
 - 4) O sistema deverá permitir a um jogador buscar itens fornecendo parte do nome, descrição,
categoria.
 - 5) O sistema deverá permitir a um jogador selecionar um item seu e um item de outro usuário para
abrir uma proposta de troca. A proposta de troca deverá registrar dia e hora.
 - 6) O sistema deverá listar as propostas de troca na tela do jogador logado.
 - 7) O jogador logado poderá selecionar uma proposta de troca para ver seus detalhes e aceitar ou
declinar a proposta.
 - 8) O sistema deverá exibir estatísticas gerais, como:
  - a) Total de usuários
  - b) Total de itens (e a soma total de seus preços)
  - c) Quantidade de Propostas de troca aceitas / declinadas
  - d) Quantidade total de propostas aguardando resposta.
 - 9) Duas funcionalidades a mais, à escolha do grupo.
