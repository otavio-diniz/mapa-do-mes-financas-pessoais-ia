# Mapa do Mês — Organização de Finanças Pessoais

**Protótipo educacional com registro por formulário, chat simulado e confirmação humana.**

O **Mapa do Mês** ajuda a visualizar receitas, despesas e saldo do mês, além de registrar e revisar movimentações fictícias. Foi desenvolvido como exercício de Vibe Coding no programa **Santander — Construa seu Primeiro App com IA**, da **DIO**, utilizando o **Lovable** na prototipação.

> **Estado em 18/11/2026:** protótipo visual interativo experimentado pelo estudante. Este repositório apresenta conceito e evidências; **não contém código-fonte executável do aplicativo** nem disponibiliza demonstração pública hospedada.

## Problema e público

Pessoas iniciantes no controle financeiro podem ter dificuldades para registrar despesas frequentemente e entender o resultado do mês. O objetivo é simplificar a experiência de lançamento e apresentar indicadores básicos com clareza.

**Público proposto:** pessoas físicas que desejam começar a acompanhar receitas e despesas. A utilidade para esse público é uma hipótese de produto, não resultado de pesquisa com usuários.

## Solução e funcionalidades

O usuário pode registrar receita ou despesa por formulário ou por **chat simulado**. Antes de salvar, revisa o lançamento e decide confirmar ou cancelar. Registros confirmados alimentam histórico e painel.

1. **Painel mensal:** receitas, despesas, saldo e categorias.
2. **Chat simulado:** sugestões de lançamentos por regras de palavras-chave e solicitação de informação ausente.
3. **Formulário:** cadastro direto de receitas e despesas.
4. **Confirmação humana:** revisão, confirmação ou cancelamento antes de salvar.
5. **Histórico:** consulta, edição e exclusão de movimentações.

A IA auxiliou na **criação do protótipo pelo Lovable**. O chat **dentro do aplicativo** funciona por regras, **não por um modelo de IA conversacional**.

## Evidências do protótipo

**[Abrir as quatro capturas reais (PDF)](assets/mapa-do-mes-evidencias-visuais.pdf)**

O PDF mostra o painel antes do lançamento, a janela de revisão, o registro por chat simulado e o painel depois de uma despesa fictícia de R$ 50,00.

| Indicador | Antes | Depois |
| --- | ---: | ---: |
| Receitas | R$ 3.650,00 | R$ 3.650,00 |
| Despesas | R$ 1.635,30 | R$ 1.685,30 |
| Saldo | R$ 2.014,70 | R$ 1.964,70 |
| Categoria Mercado | R$ 236,30 | R$ 286,30 |

O painel exibiu **despesas + R$ 50,00 e saldo − R$ 50,00**, coerentes com o lançamento confirmado. Essa comparação é evidência visual do cenário apresentado, não auditoria completa do código.

## PRD — especificação orientadora do protótipo

**Objetivo:** demonstrar uma experiência simples, em português brasileiro e valores em reais, para acompanhar receitas e despesas pessoais utilizando apenas dados fictícios.

**Requisitos prioritários:**

- Registrar receita/despesa por chat simulado ou formulário.
- Estruturar tipo, valor, descrição, categoria e data.
- Solicitar revisão e confirmação explícita antes de alterar histórico ou saldo.
- Apresentar totais mensais derivados de lançamentos confirmados.
- Permitir consultar, editar e excluir movimentações, com recálculo coerente do painel.

**Limites:** sem integração bancária, Open Finance, autenticação, pagamentos, aconselhamento de investimentos ou movimentação de dinheiro. A simulação do chat deve estar identificada visualmente.

**Proveniência do PRD e dos prompts:** esta seção consolida editorialmente os requisitos orientadores do experimento, revisados pelo estudante. **Não é transcrição literal integral da mensagem enviada ao Lovable.** Um comando real de interação visível nas capturas é **“Mercado 50,00”**. Não se atribui ao estudante texto literal que não tenha sido documentado como tal.

## Tecnologia, funcionamento e acesso

- **Lovable:** ferramenta de criação e experimentação do protótipo com apoio de IA.
- **Chat simulado:** interpretação por regras de palavras-chave.
- **GitHub / Markdown / PDF:** documentação pública e evidências.

Fluxo principal: **chat ou formulário → revisão → confirmação/cancelamento → histórico → painel mensal**.

O protótipo declara persistência local no navegador, sem serviço bancário remoto ou autenticação nesta demonstração.

**Como consultar:** leia o fluxo descrito acima, [abra as evidências visuais](assets/mapa-do-mes-evidencias-visuais.pdf) e compare os indicadores antes e depois da confirmação.

**Como executar a partir de clone:** não se aplica a esta versão documental, pois ela não distribui código executável. Não há comandos de instalação, serviços ou versões de runtime a inventar. O editor autenticado do Lovable não é apresentado como URL pública de demonstração.

## Testes e limites da validação

O estudante relatou **sete procedimentos manuais positivos**:

- Sugestão do chat sem salvamento automático.
- Confirmação de despesa e atualização do painel.
- Cadastro de receita por formulário e atualização do painel.
- Edição de despesa e recálculo do saldo.
- Mensagem sem valor solicitando complemento.
- Cancelamento sem registrar movimentação.
- Exclusão e conferência do estado após recarga.

As quatro capturas permitem verificar visualmente a consistência aritmética do lançamento fictício de R$ 50,00. Não comprovam todos os cenários possíveis.

A ferramenta também informou resultados de testes próprios, mas sua suíte **não foi auditada independentemente**. Não são declarados testes de carga, segurança, compatibilidade universal, integração bancária ou disponibilidade pública contínua.

Todos os dados da demonstração são **fictícios**. O aplicativo não deve receber credenciais ou dados financeiros sensíveis, nem realiza pagamentos. Armazenamento local não equivale a sincronização entre dispositivos.

## Aprendizados — reflexão do estudante

Ao transformar a ideia do Mapa do Mês em um protótipo com IA, aprendi que uma ideia aparentemente simples precisa ser bem estruturada para se tornar uma solução realmente útil. Foi necessário pensar no problema, no público que utilizaria a ferramenta, nas informações mais importantes e em como apresentá-las de maneira clara e prática.

O que mais chamou minha atenção foi a rapidez com que a inteligência artificial conseguiu ajudar a transformar uma necessidade em algo mais concreto. Ao mesmo tempo, percebi que a IA não substitui a análise humana: é necessário revisar as sugestões, testar o protótipo e ajustar as instruções até que o resultado esteja realmente alinhado ao objetivo.

Também aprendi que a criação de um protótipo é um processo de melhoria contínua. Testar, identificar falhas e fazer novos ajustes faz parte do desenvolvimento. No caso do Mapa do Mês, a IA ajudou não apenas na construção da solução, mas também a enxergar novas possibilidades de organização, automação e apresentação das informações.

A principal conclusão foi perceber que a IA pode acelerar bastante o processo de transformar uma ideia em uma solução prática, desde que seja utilizada com objetivos claros, bons comandos e validação humana.

## Formação, autoria e direitos

Projeto de estudo de **Otávio Diniz** no programa **Santander — Construa seu Primeiro App com IA**, na **DIO (Digital Innovation One)**. Referência acadêmica: [DIO — App de Finanças Pessoais com Vibe Coding](https://github.com/digitalinnovationone/dio-lab-vibe-coding-app-financas).

Este é um **repositório independente**, não um fork. O contexto acadêmico não implica parceria, endosso, nota, aprovação ou certificação institucional.

© 2026 Otávio Diniz, ressalvados direitos de ferramentas e materiais de terceiros. A visibilidade pública **não constitui licença open source automática** nem autorização geral para reutilização comercial. Sugestões podem ser feitas pelos recursos públicos do GitHub, sem compartilhamento de segredos ou dados pessoais.
