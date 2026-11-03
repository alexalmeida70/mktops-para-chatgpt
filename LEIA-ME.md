# MktOps para ChatGPT by Alex Almeida

**Origem do material:** `os-15-agentes.zip` fornecido pelo usuário. Correspondência de nomes verificada com https://github.com/helio-debug/arsenal-mktops (`agentes.json`).

## Execução no ChatGPT

Use o `PROMPT-MESTRE.md` como instruções do projeto ou anexe o pacote como fonte. Peça, por exemplo:

- `Auditoria de marketing https://empresa.com.br`
- `Auditoria de anúncios Google + Meta com estes relatórios`
- `Audite rastreamento da landing page <URL>`
- `Crie uma campanha B2B para [oferta], com três conceitos e versões Meta e LinkedIn`
- `Acione o agente audit-google com o CSV anexo`

Três fluxos em `habilidades/`: `ads`, `ads-audit`, `market-audit`. Quinze papéis em `agentes/`. Referências técnicas mantidas em `referencias/`. Scripts originais em `scripts-originais/` para estudo, **não executados automaticamente** e podem exigir dependências, tokens e revisão de segurança.

## Limitações

Estes Markdown são instruções portáteis, não plugins instalados nem subprocessos persistentes. ChatGPT não ganha acesso à conta de anúncios por receber esses arquivos. Sem API, integração ou exportação de dados, o diagnóstico limita-se a informação pública e material fornecido. A biblioteca original contém referências potencialmente desatualizadas; validar políticas, formatos e benchmarks atuais antes de decisões de mídia.

## Estrutura

- `PROMPT-MESTRE.md`: triagem e orquestração
- `agentes/*.md`: cada agente original, com regras de execução na interface ChatGPT
- `habilidades/*/SKILL.md`: três orquestradores
- `referencias/*.md`: checklists e especificações originais
- `scripts-originais/*.py`: scripts de suporte (não executados)
- `MAPA.md`: relação entre fluxos e especialistas
