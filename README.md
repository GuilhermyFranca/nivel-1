# Nível 1

Sistema visual de cartas e ferramentas para RPG.

## Objetivo

Produzir e disponibilizar aos jogadores as cartas e os materiais visuais necessários para a utilização das classes e personagens durante o jogo.

A produção é realizada de forma incremental, conforme surgem necessidades durante o desenvolvimento e a utilização do jogo.

## Abordagem atual

A produção atual é orientada pelas necessidades dos jogadores.

Em vez de produzir previamente um grande acervo organizado de todo o sistema, as cartas são desenvolvidas conforme as necessidades concretas das classes e personagens em jogo.

Os materiais destinados aos jogadores são organizados por classe e disponibilizados através do MEGA.

A estrutura pode evoluir conforme novas necessidades surgirem.

## Distribuição

A distribuição dos materiais aos jogadores é realizada através de pastas no MEGA.

A estrutura principal será organizada por classes.

Exemplo:

```text
Classes/
├── Guerreiro/
├── Ladino/
├── Mago/
├── Monge/
├── Ranger/
└── ...
```

Cada pasta de classe reúne os materiais necessários para aquela classe ou personagem.

Não é necessário que todas as classes possuam a mesma quantidade ou os mesmos tipos de materiais.

## Abordagem anterior

Durante o desenvolvimento inicial, foi utilizada uma abordagem de organização abrangente do acervo.

Essa abordagem buscava estruturar previamente:

* perícias;
* cartas;
* decks;
* subdecks;
* coleções;
* versões;
* relações de acesso;
* documentação detalhada do acervo.

Essa produção permanece registrada no histórico do projeto e constitui parte do desenvolvimento anterior.

A estrutura anterior não precisa ser eliminada e pode continuar sendo consultada ou reaproveitada quando necessário.

Ela é considerada a **abordagem antiga** do projeto.

## Produção das cartas

As cartas são produzidas conforme a necessidade.

Uma carta pode ser criada especificamente para atender às necessidades de uma determinada classe ou personagem, sem que isso implique necessariamente que seu conteúdo seja exclusivo daquela classe ou personagem.

Versões diferentes de uma mesma carta podem existir quando forem úteis para diferentes personagens ou situações.

## Documentação

Este repositório é utilizado principalmente para documentar o desenvolvimento do projeto.

A documentação pode registrar:

* decisões de design;
* padrões visuais;
* métodos de produção;
* organização dos materiais;
* ferramentas utilizadas;
* classes preparadas;
* cartas produzidas;
* alterações importantes;
* histórico do desenvolvimento.

## Versionamento

O projeto utiliza Git para controle de versão.

O histórico do repositório registra a evolução do projeto, incluindo a transição da abordagem anterior para a abordagem atual.

Os arquivos destinados diretamente aos jogadores podem ser distribuídos e mantidos fora do GitHub, principalmente através do MEGA.

## Estado atual

O projeto está em desenvolvimento incremental.

A prioridade é produzir materiais funcionais para os jogadores e disponibilizá-los conforme forem necessários.

A estrutura do projeto não é considerada definitiva e pode evoluir de acordo com as necessidades reais do jogo.
