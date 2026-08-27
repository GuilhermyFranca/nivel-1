# Nível 1

## Sistema Visual de Cartas e Ferramentas de RPG

Projeto de desenvolvimento de um sistema visual de cartas para RPG, acompanhado de ferramentas, documentação e recursos para jogadores e mestre.

## Objetivos

* Organizar e estruturar o acervo de cartas do Nível 1.
* Criar decks organizados para diferentes classes e personagens.
* Documentar perícias, habilidades, magias, equipamentos e outras cartas.
* Desenvolver materiais visuais para explicar regras e combinações complexas.
* Criar ferramentas digitais para facilitar a consulta e utilização das cartas.
* Desenvolver o projeto de forma versionada e documentada.

## Estrutura conceitual

### Cartas

As cartas são os elementos fundamentais do sistema.

#### Tipos de Carta

Os tipos de carta identificados atualmente são:

* Perícia
* Habilidade de Classe
* Magia
* Infusão
* Equipamento
* Personagem

Esta classificação permanece aberta para novos tipos de carta conforme o desenvolvimento do projeto e a análise do acervo original.

### Coleções

As coleções são agrupamentos organizados de recursos do projeto.

Uma coleção pode conter cartas, outras coleções ou ambos. A estrutura de coleções permanece aberta para novos tipos conforme o desenvolvimento do projeto.

#### Tipos de Coleção

Os tipos identificados atualmente são:

* Deck
* Extra-Deck
* Subdeck
* Deck-Ficha

Esses tipos são formais e podem existir dentro uns dos outros quando a organização do conteúdo exigir.

#### Decks

Um Deck é uma coleção organizada de cartas e recursos relacionados.

Um Deck pode conter cartas diretamente associadas a ele e também outros Decks, Extra-Decks ou Subdecks.

Os Decks podem representar diferentes níveis de organização, incluindo:

* Decks de Classe
* Decks de Perícias
* Decks de Magias
* Decks de Equipamentos
* Outros decks gerais ou específicos

#### Extra-Decks

Extra-Decks são coleções formais utilizadas para reunir conteúdos complementares ou especializados.

Podem existir dentro de outros Decks ou coleções e podem conter cartas ou outras coleções.

#### Subdecks

Subdecks são coleções formais subordinadas a outra coleção e destinadas a organizar conjuntos menores e mais específicos de conteúdo.

#### Deck-Ficha

O Deck-Ficha representa a organização de um personagem específico.

Uma ficha de personagem corresponde a um Deck-Ficha, que pode reunir:

* Carta do Personagem
* Deck do Personagem
* Decks
* Extra-Decks
* Subdecks
* Outros recursos aos quais o personagem tenha ou venha a ter acesso

### Relações

A organização do projeto pode estabelecer relações como:

**Classe → Deck → Coleções → Cartas**

e:

**Personagem → Deck-Ficha → Decks / Extra-Decks / Subdecks → Cartas**

Uma mesma carta pode aparecer em diferentes coleções sem que seja necessário criar uma cópia diferente da carta para cada coleção.

### Combos

Combinações entre cartas que produzem efeitos ou estratégias relevantes.

### Infográficos

Materiais visuais destinados a explicar regras, relações e combos complexos.

### Documentação

Regras, conceitos, decisões de design e documentação técnica do projeto.

## Desenvolvimento

O projeto será desenvolvido de forma incremental, utilizando Git e GitHub para controle de versão.

## Estado atual

O acervo original contém aproximadamente 500 arquivos relacionados às cartas e outros materiais do projeto. O acervo original será preservado durante o processo de organização e desenvolvimento.
