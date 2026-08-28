# Organização Atual

## Nível 1

Este documento descreve a organização atualmente utilizada no desenvolvimento e na distribuição do projeto Nível 1.

A organização atual é **incremental e orientada pelas necessidades reais do jogo**.

Não existe a exigência de estruturar previamente todo o acervo de cartas, todas as classes ou todas as possíveis coleções.

---

## Princípio de produção

As cartas e demais materiais são produzidos conforme surgem necessidades concretas durante o desenvolvimento ou utilização do jogo.

O processo geral é:

**Necessidade → Produção → Organização → Distribuição**

Uma necessidade pode surgir de:

* uma classe em desenvolvimento;
* um personagem em jogo;
* uma regra que precisa de representação visual;
* uma habilidade ou recurso que precisa ser disponibilizado;
* uma situação específica da campanha;
* uma necessidade de consulta rápida durante o jogo.

A produção não precisa aguardar a conclusão de um conjunto completo.

---

## Organização por classe

Os materiais destinados aos jogadores são organizados principalmente por classe.

Uma classe pode possuir:

* cartas de perícia;
* habilidades;
* magias;
* equipamentos;
* recursos específicos;
* cartas personalizadas;
* outros materiais necessários ao personagem.

Não é necessário que todas as classes possuam os mesmos tipos ou a mesma quantidade de materiais.

A estrutura pode crescer conforme cada classe for sendo preparada.

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

---

## Personagens

Quando necessário, materiais podem ser personalizados para um personagem específico.

A personalização pode incluir:

* nome do personagem;
* imagem do personagem;
* ilustrações específicas;
* adaptações visuais;
* cartas preparadas para sua utilização.

Uma carta personalizada não precisa representar uma regra exclusiva daquele personagem.

Ela pode ser apenas uma representação específica de um conteúdo que também possa existir para outros personagens.

---

## Distribuição

Os materiais destinados aos jogadores são disponibilizados principalmente através do **MEGA**.

A organização do MEGA deve priorizar a facilidade de acesso e utilização pelos jogadores.

A estrutura de distribuição pode ser modificada conforme as necessidades do jogo.

O MEGA é utilizado como meio de distribuição dos materiais, enquanto o GitHub é utilizado principalmente para documentação, organização e versionamento do projeto.

---

## GitHub

O repositório GitHub registra o desenvolvimento do projeto.

Ele pode conter:

* documentação;
* decisões de design;
* padrões de produção;
* organização do projeto;
* registros históricos;
* materiais selecionados;
* ferramentas;
* arquivos necessários ao desenvolvimento.

O GitHub não precisa conter obrigatoriamente todos os arquivos destinados aos jogadores.

---

## Versões

Uma mesma carta ou material pode possuir diferentes versões.

As versões podem existir por motivos como:

* correção;
* melhoria visual;
* alteração de regra;
* personalização;
* adaptação para uma classe;
* adaptação para um personagem;
* experimentação.

Versões antigas podem ser preservadas quando possuírem valor histórico ou forem úteis para comparação.

---

## Organização flexível

A organização atual não é definitiva.

Novas categorias, pastas, classes, tipos de carta ou métodos de distribuição podem ser criados quando houver necessidade.

Estruturas que deixarem de ser úteis podem ser modificadas ou substituídas.

O objetivo é manter a organização suficientemente clara para facilitar o desenvolvimento, sem transformar a estrutura do projeto em uma obrigação que dificulte a produção.

---

## Relação com a abordagem antiga

Durante uma fase anterior do projeto, foi desenvolvida uma estrutura mais abrangente baseada em cartas, coleções, Decks, Extra-Decks, Subdecks, Deck-Ficha e relações entre esses elementos.

Essa estrutura foi preservada na documentação histórica em:

`Documentacao/Abordagem_Antiga/SISTEMA_VISUAL_CARTAS_E_COLECOES.md`

A abordagem antiga continua podendo fornecer ideias e conceitos úteis, mas **não constitui uma obrigação para a organização atual**.

---

## Estado atual

O projeto encontra-se em desenvolvimento incremental.

A prioridade atual é:

1. identificar as necessidades dos jogadores;
2. produzir os materiais necessários;
3. organizar esses materiais de forma prática;
4. disponibilizá-los aos jogadores;
5. documentar as decisões e mudanças relevantes.

A estrutura será aprimorada conforme a experiência prática do jogo indicar novas necessidades.
