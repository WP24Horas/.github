<p align="center">
  <img src="https://www.wp24horas.com.br/wp-content/uploads/2021/08/wp24h-logo-4-2.svg" alt="WP24Horas" width="320">
</p>

<h1 align="center">WP24Horas Open Source</h1>

<p align="center">
  Ferramentas, referências e exemplos para desenvolvimento WordPress profissional.
</p>

A WP24Horas nasceu como um ecossistema de conteúdo e soluções WordPress. No GitHub, o foco é mais específico: manter projetos públicos que ajudem desenvolvedores a construir plugins com melhor arquitetura, segurança, testabilidade e processos de release mais previsíveis.

## O que mantemos aqui

Os projetos públicos priorizam problemas concretos do desenvolvimento WordPress:

- arquitetura e extensibilidade de plugins;
- Settings API e REST API;
- capabilities, nonces, sanitização e escaping;
- testes e análise estática;
- metadados de distribuição e `readme.txt`;
- automação editorial e integração com Markdown;
- exemplos pequenos o suficiente para estudar, mas estruturados para refletir práticas de produção.

Não buscamos quantidade de repositórios. Preferimos manter poucos projetos com documentação clara, responsabilidade definida e espaço real para contribuição.

> Repositórios explicitamente marcados como **legacy**, **historical** ou **experimental** são preservados apenas como material histórico e não representam a baseline técnica atual da WP24Horas.

## Projeto em destaque

### [WP24H Plugin Boilerplate](https://github.com/WP24Horas/wp24h-plugin-boilerplate)

Base modular e configurável para plugins WordPress profissionais, com Settings API, REST, módulos extensíveis, PHPCS, PHPStan, PHPUnit, `wp-env` e tooling de release.

O repositório também pode ser usado como **template** para iniciar novos plugins.

## Ferramentas relacionadas

Alguns projetos relacionados ainda são mantidos no perfil do mantenedor enquanto o ecossistema é consolidado:

- **[WP Plugin Readme Validator](https://github.com/asllanmaciel/wp-plugin-readme-validator)** — CLI e GitHub Action para validar consistência entre o cabeçalho principal do plugin e o `readme.txt`.
- **[WP24H MD Importer](https://github.com/asllanmaciel/wp24h-md-importer)** — importação de Markdown + front matter para WordPress, com mídia destacada, taxonomias, SEO e REST autenticada opcional.

## Princípios de engenharia

- **WordPress-native first:** usar APIs do core antes de inventar abstrações desnecessárias.
- **Security by default:** capability checks, nonces, permission callbacks, sanitização e escaping fazem parte do exemplo, não de uma etapa posterior.
- **Local-first validation:** testes, lint e análise estática devem poder rodar localmente sem depender de CI pago.
- **Explicit trade-offs:** documentação deve explicar por que uma abordagem foi escolhida e onde ela deixa de ser adequada.
- **Safe extension points:** código gerado ou de exemplo não deve incentivar sobrescrever customizações sem uma fronteira clara.

## Como contribuir

Issues e pull requests são bem-vindos quando melhoram um problema concreto do projeto.

Antes de contribuir:

1. leia o `CONTRIBUTING.md` do repositório;
2. procure issues marcadas como `good first issue` ou `help wanted`;
3. mantenha a mudança focada e testável;
4. não inclua credenciais, dados de clientes ou código comercial privado.

Relatos de segurança devem seguir o `SECURITY.md` específico de cada projeto, em vez de serem publicados como issue explorável.

## Sobre a WP24Horas

Conteúdo, materiais e outras iniciativas WordPress continuam disponíveis em [wp24horas.com.br](https://wp24horas.com.br).

Contato: `contato@wp24horas.com.br`
