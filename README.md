# Mapa do Mês — Finanças Pessoais com IA

> **Conceito acadêmico em desenvolvimento | Santander — Construa seu Primeiro App com IA / DIO | M02 C06**

**Estado em 09/11/2026:** planejamento e especificação inicial. **Não há aplicativo implementado, demonstração funcional, testes executados ou entrega à DIO neste repositório.**

## Resumo e proposta de valor

O **Mapa do Mês** é um conceito de aplicativo para ajudar pessoas físicas a registrar receitas e despesas cotidianas, conferir lançamentos e compreender o orçamento mensal.

A proposta explora uma **experiência híbrida**: interação por linguagem natural com IA e cadastro/edição por formulário. O usuário mantém o controle sobre o que é efetivamente registrado.

**Proposta de valor em estudo:** registrar de maneira simples, conferir com segurança e entender o próprio mês. Os benefícios são hipóteses a validar, não resultados observados.

## Problema e público-alvo

O registro financeiro repetitivo e a interpretação de relatórios complexos podem dificultar a continuidade do acompanhamento de gastos. A hipótese de produto é que entradas conversacionais, combinadas com formulários editáveis e um painel simples, reduzam essa fricção.

**Público principal proposto:** adultos que desejam começar ou aprimorar o acompanhamento de receitas e despesas pessoais. O projeto não é um sistema bancário, plataforma de crédito, aplicativo contábil para MEI ou serviço de investimentos.

## Solução planejada

1. **Entrada conversacional:** interpretar frases como “Gastei R$ 48,90 no supermercado”.
2. **Conferência humana:** sugerir tipo, valor, data e categoria e solicitar confirmação antes de salvar.
3. **Entrada por formulário:** cadastrar, corrigir e excluir movimentações independentemente do chat.
4. **Visão mensal:** exibir receitas, despesas, saldo e gastos por categoria.
5. **Explicações simples:** descrever padrões observáveis nos dados confirmados, sem recomendar produtos financeiros.

**Importante:** todos os itens acima são requisitos **planejados**. Nenhum está declarado como implementado ou testado.

## Exemplo conceitual — não executado

**Mensagem de demonstração fictícia:** “Gastei R$ 48,90 no supermercado hoje”.

**Comportamento esperado:** sugerir uma *despesa* de R$ 48,90, categoria *Alimentação*, data corrente e exigir confirmação/edição antes de salvar. O saldo só deve mudar depois da confirmação.

O exemplo é um **critério de comportamento**, não um registro verdadeiro, print de execução ou teste aprovado.

## Requisitos e critérios de aceite propostos

| ID | Comportamento verificável | Estado |
| --- | --- | --- |
| CA01 | Chat gera sugestão editável antes de registrar a transação | Planejado |
| CA02 | Formulário e chat alimentam um histórico único | Planejado |
| CA03 | Receita fictícia de R$ 2.000 menos despesa de R$ 48,90 produz saldo de R$ 1.951,10 | Planejado |
| CA04 | Editar/excluir atualiza todos os totais correspondentes | Planejado |
| CA05 | Mensagem sem valor suficiente solicita esclarecimento | Planejado |
| CA06 | Painel mensal considera apenas transações confirmadas | Planejado |

## Abordagem de desenvolvimento e validação

O desafio acadêmico enfatiza o **Product Requirements Document (PRD)**, o refinamento de prompts e o uso de IA como parceira de concepção. Estão previstas, sem execução comprovada até agora:

- validação autoral do problema, público e escopo mínimo;
- consolidação de um PRD final pelo participante;
- experimentos documentados com Copilot e/ou Lovable;
- revisão da saída da IA contra os critérios de aceite;
- publicação de evidências reais e sanitizadas, somente quando existirem;
- reflexão pessoal sobre o processo, escrita e validada pelo participante.

**Stack atual:** apenas documentação em Markdown e versionamento GitHub. Copilot e Lovable são ferramentas **previstas para experimentação**, não integrações implementadas.

## Segurança, privacidade e limites

- Usar exclusivamente exemplos e dados financeiros **fictícios/sintéticos** nas demonstrações.
- Não pedir senhas, tokens, credenciais bancárias ou dados sensíveis.
- Não conectar contas bancárias, processar pagamentos ou movimentar dinheiro.
- Não inferir informações financeiras ausentes ou salvar sugestões sem consentimento.
- Não apresentar explicações gerais como aconselhamento financeiro ou de investimentos.
- Não declarar redução de esforço, adoção, precisão ou benefícios comerciais sem medição apropriada.

## Diferenciação no portfólio

Este exercício busca explorar a **experiência de registro financeiro pessoal**, sem replicar os objetivos de outros projetos de portfólio do autor:

- [MILA — Copiloto Financeiro para MEI](https://github.com/otavio-diniz/mila-copiloto-financeiro-mei): organização de caixa empresarial, PF/PJ e apoio à comparação de decisões.
- [Geo-Explorer — TrustPath AI](https://github.com/otavio-diniz/geo-explorer-trustpath-ai): aprendizagem em IA orientada por evidências e supervisão humana.
- [CreditExplain BR](https://github.com/otavio-diniz/creditexplain-br): pesquisa documental sobre crédito responsável e explicabilidade.
- [Assistente de Investimentos com RPA e n8n](https://github.com/otavio-diniz/dio-lab-assistente-investimentos-rpa-n8n): orquestração local de automação com bases fictícias.

Há **conexões conceituais**, não integração técnica comprovada entre os projetos.

## Contexto acadêmico e créditos

Este projeto foi iniciado no contexto do desafio **“App de Organização de Finanças Pessoais com Vibe Coding”**, do programa **Santander — Construa seu Primeiro App com IA**, na **DIO (Digital Innovation One)**.

Referência acadêmica original: [digitalinnovationone/dio-lab-vibe-coding-app-financas](https://github.com/digitalinnovationone/dio-lab-vibe-coding-app-financas).

O repositório é independente e não reproduz código ou materiais de terceiros. O reconhecimento à DIO e ao Santander não implica parceria, endosso técnico, nota, aprovação ou conclusão institucional.

## Autoria, direitos e participação

**Autoria do projeto:** © 2026 Otávio Diniz, respeitados direitos de terceiros.

Este repositório é público para acompanhamento acadêmico, apresentação de portfólio e recebimento de comentários. **A publicidade não constitui uma licença open source** nem implica autorização genérica para exploração comercial ou redistribuição de conteúdo autoral. Licenciamento definitivo e eventuais contribuições serão definidos em etapa própria, após revisão de direitos e proveniência.

Sugestões e feedback podem ser apresentados pelas funcionalidades públicas do GitHub. Não compartilhe dados pessoais, segredos ou credenciais.

## Histórico e próximas etapas

- **09/11/2026 — Conceito:** definido o nome de trabalho *Mapa do Mês*, a abordagem híbrida e o foco em finanças pessoais.
- **09/11/2026 — Preparação pública:** README inicial com problema, hipótese de solução, escopo provisório, limitações e vínculos conceituais com o portfólio.
- **Próxima etapa:** discutir e validar colaborativamente o PRD, antes de classificar requisitos como definitivos.
- **Após validação:** registrar experiências reais de prompting, resultados observados e reflexões pessoais.
- **Entrega à DIO:** ação futura e distinta, sujeita à realização do trabalho pelo estudante.

Nenhuma execução, avaliação ou entrega institucional é inferida da abertura deste repositório.
