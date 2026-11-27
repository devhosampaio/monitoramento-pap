# AGENTS.md — Diretrizes de UX e UI do Monitoramento PAP

Estas instruções orientam qualquer agente ou colaborador que trabalhe neste repositório. Elas documentam o uso de **Intent** para UX e **Impeccable** para UI no ambiente atual de ChatGPT com integração GitHub.

## 1. Referências obrigatórias

- **UX — Intent:** https://github.com/ghaida/intent
  - README: https://github.com/ghaida/intent/blob/main/README.md
  - Skill principal: https://github.com/ghaida/intent/blob/main/skills/intent/SKILL.md
  - Arquivos e skills especializados: https://github.com/ghaida/intent/tree/main/skills
- **UI — Impeccable:** https://github.com/pbakaus/impeccable
  - README: https://github.com/pbakaus/impeccable/blob/main/README.md
  - Skill principal: https://github.com/pbakaus/impeccable/blob/main/.agent/skills/impeccable/SKILL.md
  - Playbooks e demais referências: https://github.com/pbakaus/impeccable/tree/main

As versões originais mantidas pelos respectivos projetos são a fonte de verdade. Este arquivo não substitui nem reproduz integralmente essas instruções.

## 2. Consulta obrigatória antes de cada atividade

Antes de iniciar qualquer atividade pertinente:

1. Identifique se a tarefa envolve UX, UI ou ambas.
2. Consulte novamente a documentação original pertinente, diretamente nos links acima. Não dependa apenas de lembranças, resumos de conversas ou desta diretriz.
3. Para UX, leia a skill central do Intent e consulte as skills especializadas relacionadas à atividade solicitada.
4. Para UI, leia a skill principal do Impeccable e consulte os playbooks, referências e orientações relevantes à mudança pretendida.
5. Considere as instruções, métodos e critérios dessas ferramentas como referências de trabalho, aplicando-os manualmente conforme as limitações descritas na seção 5.
6. Registre para a coordenação as conclusões, decisões e critérios que afetem o projeto, sem transformar recomendações das ferramentas em requisitos automaticamente.

A consulta deve ser renovada a cada nova atividade pertinente, inclusive quando a ferramenta já tiver sido consultada em uma etapa anterior.

## 3. Separação entre UX e UI

**Intent — UX**

Utilize o Intent para orientar questões de experiência e comportamento: necessidades e objetivos dos usuários, contexto de uso, fluxos, arquitetura da informação, conteúdo, acessibilidade, estados, prevenção de erros, pesquisa, validação e critérios de experiência.

**Impeccable — UI**

Utilize o Impeccable para orientar questões de apresentação e implementação visual: hierarquia visual, tipografia, cores, espaçamento, composição, layout, responsividade, consistência, estados visuais e qualidade de acabamento da interface.

Não confunda as responsabilidades. Uma decisão visual não deve redefinir silenciosamente um fluxo ou requisito de experiência; uma decisão de UX não determina, por si só, uma solução visual específica. Quando uma atividade envolver ambas, explicite as duas dimensões e suas dependências.

## 4. Requisitos aprovados e autoridade da coordenação

- Os requisitos, regras de negócio, decisões de produto, restrições técnicas e definições já validados para o Monitoramento PAP devem ser respeitados integralmente.
- As ferramentas são referências metodológicas; não têm autoridade para substituir decisões aprovadas nem para ampliar o escopo.
- Não altere, descarte, reinterprete ou contradiga um requisito validado por iniciativa própria.
- Se uma recomendação do Intent ou do Impeccable entrar em conflito com um requisito, decisão anterior ou restrição do projeto, interrompa a decisão afetada e apresente o conflito à coordenação.
- Apresente também à coordenação qualquer dúvida relevante, lacuna de requisito, ambiguidade, dependência, risco ou proposta de mudança de escopo.
- Não implemente uma mudança de requisito ou de escopo sem aprovação explícita da coordenação.
- Quando houver alternativas legítimas, apresente opções, impactos e recomendação fundamentada; aguarde a decisão da coordenação quando a escolha alterar algo já aprovado ou ainda não definido.

## 5. Aplicação no ambiente atual

O projeto permanece no ambiente atual de ChatGPT com integração GitHub. Nesse ambiente, a consulta aos repositórios e arquivos pode ser feita pelos links oficiais e pelos recursos de leitura disponíveis na integração.

**A aplicação das instruções é manual.** A integração GitHub, por si só, não instala nem executa Agent Skills, comandos, agentes especializados, detectores, scripts ou hooks. Este arquivo também não ativa essas capacidades automaticamente.

Portanto:

- Abra e leia as instruções originais pertinentes antes de cada atividade, conforme a seção 2.
- Aplique manualmente os métodos e critérios relevantes no raciocínio, nas análises e nas entregas.
- Se necessário, traga para a conversa trechos específicos das instruções originais, preservando o contexto e os créditos.
- Não afirme que uma skill, comando, agente, detector ou hook foi instalado, ativado ou executado se isso não tiver ocorrido em um ambiente que realmente ofereça essa capacidade.
- Não execute nem simule os comandos de instalação documentados pelos projetos neste ambiente.
- Não copie grandes blocos dos repositórios originais para este projeto. Prefira links para as fontes oficiais. Se algum material original vier a ser incorporado futuramente, preserve os avisos de copyright, créditos e licença aplicável, verificando antes as condições de redistribuição.

A adoção de execução automática dependerá de uma decisão futura da coordenação e de um ambiente comprovadamente compatível. Esta diretriz não autoriza migração de ambiente.

## 6. Documentos de produto e design

Não criar `PRODUCT.md` ou `DESIGN.md` nesta etapa. A eventual elaboração desses documentos depende da conclusão e aprovação das etapas correspondentes de UX e UI pela coordenação.

## 7. Limites desta configuração

Este documento estabelece apenas o procedimento de consulta e aplicação manual das referências de UX e UI. Ele não autoriza:

- implementar ou alterar funcionalidades;
- modificar requisitos, regras de negócio ou decisões já validadas;
- instalar dependências ou ferramentas;
- configurar skills, comandos, agentes ou hooks;
- migrar para Codex ou outro ambiente;
- publicar, fazer deploy ou alterar configurações de hospedagem;
- criar documentos de produto ou design antes das etapas e aprovações correspondentes.
