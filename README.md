# MktOps para ChatGPT by Alex Almeida

**Versão 1.0.0 • 03/11/2026 • Pré-lançamento para homologação • Repositório público**

Adaptação para ChatGPT de 15 agentes especializados em marketing, SEO, mídia paga, conversão e criação de campanhas. Versão desenvolvida por Alex Almeida a partir do Arsenal MktOps.

## Recursos disponíveis

| Componente | Conteúdo |
|---|---|
| [Agentes](agentes/) | 15 papéis: seis de auditoria de anúncios, cinco de auditoria de marketing e quatro de criação de campanhas |
| [Habilidades](habilidades/) | Três fluxos: [mídia e campanhas](habilidades/ads/SKILL.md), [auditoria de anúncios](habilidades/ads-audit/SKILL.md) e [auditoria de marketing](habilidades/market-audit/SKILL.md) |
| [Referências](referencias/) | 20 arquivos de checklists, benchmarks e especificações técnicas |
| [Scripts originais](scripts-originais/) | Quatro scripts de suporte preservados para estudo e futura integração |
| [Prompt mestre](PROMPT-MESTRE.md) | Seleção de especialidades e regras de execução |

## Como utilizar

1. Leia o [guia de utilização](LEIA-ME.md) e o [mapa de agentes](MAPA.md).
2. Use o [PROMPT-MESTRE.md](PROMPT-MESTRE.md) nas instruções do seu projeto ChatGPT ou forneça-o como documento de contexto.
3. Disponibilize os arquivos dos agentes, das habilidades e das referências pertinentes. Extraia o ZIP antes de carregar arquivos quando a interface exigir; o limite de arquivos depende do ambiente utilizado.
4. Solicite uma análise ou campanha em linguagem natural, fornecendo URL, objetivo, contexto e dados disponíveis. Exemplo: `Auditoria de marketing https://empresa.com.br`.
5. Confira evidências, cobertura da análise e limitações antes de tomar decisões ou autorizar mudanças em contas.

As três habilidades usam `SKILL.md` com frontmatter `name` e `description`, compatível com leitura e descoberta nos ambientes que suportam esse formato. A instalação e as ferramentas disponíveis variam entre ChatGPT, Codex e Claude. Este pacote não instala 15 processos independentes nem concede acesso a contas de anúncios.

## Versões e manutenção

- Versão atual em [VERSION](VERSION); alterações no [CHANGELOG.md](CHANGELOG.md).
- Pacotes e notas em [Releases](https://github.com/alexalmeida70/mktops-para-chatgpt/releases).
- SemVer: MAJOR para incompatibilidades; MINOR para recursos compatíveis; PATCH para correções sem mudança funcional relevante.
- Conventional Commits, branches de trabalho e Pull Requests conforme [CONTRIBUTING.md](CONTRIBUTING.md).

## Limitações conhecidas

- Agentes ainda não validados individualmente em ambiente real.
- Fluxos de orquestração ainda necessitam de testes completos.
- Integrações externas dependem das ferramentas disponíveis e de acesso autorizado.
- Referências preservadas podem conter requisitos, modelos e benchmarks históricos; confirme sua atualidade antes de decisões de mídia.
- Scripts originais não foram executados nem homologados nesta publicação e podem exigir dependências e credenciais locais.
- O material herdado cita sub-skills externas que não fazem parte deste pacote; o inventário disponível é o apresentado acima.

## Autoria, origem e atribuição

**Projeto original:** Arsenal MktOps  
**Desenvolvimento original:** Studio Artemis  
**Repositório de origem:** https://github.com/helio-debug/arsenal-mktops  
**Portal original:** https://arsenal.studioartemis.co/

**Autoria da adaptação para ChatGPT:** Alex Almeida  
Presidente do Grupo MR | Máquina de Resultados  
Especialista B2B em Go-to-Market, Estruturação Comercial e Automação com IA

- LinkedIn: https://www.linkedin.com/in/alexalmeida70/
- Site: https://www.maquinaderesultados.com.br/
- E-mail: alex@maquinaderesultados.com.br
- Instagram: https://www.instagram.com/alexalmeida70/

Alex Almeida é autor das modificações e da estruturação desta versão. Os direitos e créditos dos componentes originais permanecem com seus respectivos titulares. A adaptação não implica vínculo oficial ou endosso da Studio Artemis.

## Autorização e direitos de redistribuição

Alex Almeida confirmou em 03/11/2026 que o autor autorizou **uso, adaptação e redistribuição pública**. Uma captura de conversa apresentada documenta a anuência ao pedido de adaptação para GPT; o escopo de redistribuição foi confirmado adicionalmente por Alex Almeida. Consulte o [registro da autorização](AUTORIZACAO-DE-USO.md).

Não foi identificada licença explícita na árvore pública de origem consultada. A autorização informada é específica e não foi convertida em uma licença aberta geral para terceiros. Os créditos originais foram mantidos. Consulte [ORIGEM-E-DIREITOS.md](ORIGEM-E-DIREITOS.md) e o [registro de proveniência da v1.0.0](PROVENIENCIA.json).

O repositório foi tornado **público em 03/11/2026**, por autorização expressa de Alex Almeida. Nenhuma licença sobre conteúdos de terceiros foi adicionada. A tag e o pacote da v1.0.0 preservam a situação documentada no lançamento, quando o repositório ainda era privado; atualizações posteriores estão no histórico.
