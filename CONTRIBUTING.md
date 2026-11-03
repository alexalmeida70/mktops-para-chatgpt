# Contribuição e versionamento

## Commits

Use Conventional Commits com uma descrição objetiva:

| Prefixo | Finalidade |
|---|---|
| `feat:` | Novas funcionalidades |
| `fix:` | Correções |
| `docs:` | Documentação |
| `refactor:` | Reorganização sem mudança funcional |
| `test:` | Testes e validações |
| `chore:` | Manutenção |

## Branches e revisão

`main` é a branch estável de manutenção. O estado de homologação de cada distribuição é indicado no Release; a v1.0.0 é um pré-lançamento.

Crie branches `feat/nome-da-funcionalidade` ou `fix/nome-da-correcao`. Submeta alterações por Pull Request com descrição, motivação e evidências das verificações antes do merge. Esta é uma política documentada; não implica que a proteção de branch esteja habilitada no GitHub.

## Releases

1. Atualize [VERSION](VERSION), [README.md](README.md), [PROMPT-MESTRE.md](PROMPT-MESTRE.md) e [CHANGELOG.md](CHANGELOG.md).
2. Use SemVer: `2.0.0` para alterações incompatíveis, `1.1.0` para novos recursos compatíveis e `1.0.1` para correções.
3. Verifique arquivos, links, créditos, frontmatter das habilidades e ausência de credenciais. Registre separadamente testes funcionais e inspeções estáticas.
4. Confirme o commit no GitHub antes de criar a tag `vX.Y.Z`. Não mova tags de versões já distribuídas.
5. Gere o ZIP diretamente da árvore da tag, com a pasta `mktops-para-chatgpt/` na raiz. Não inclua `.git`, credenciais ou arquivos locais externos ao commit.
6. Compare todos os caminhos e bytes do ZIP com os objetos Git da tag. Anexe o pacote ao Release e confira por download posterior.
7. Use pré-lançamento enquanto não houver homologação funcional. Mantenha versões anteriores para recuperação.

## Autoria e direitos

Mantenha a autoria de Alex Almeida nas adaptações e os créditos dos componentes originais. Não atribua uma licença a conteúdos de terceiros sem base documental. Consulte [origem e direitos](ORIGEM-E-DIREITOS.md) antes de redistribuir ou propor mudança de visibilidade.
