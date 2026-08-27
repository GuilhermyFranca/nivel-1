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

As cartas são as unidades visuais e funcionais fundamentais do sistema.

Uma carta apresenta ao jogador uma informação, regra, habilidade, recurso ou outro elemento do sistema de forma organizada e visual.

#### Tipos de Carta

Os tipos de carta identificados atualmente são:

* Perícia
* Habilidade de Classe
* Magia
* Infusão
* Equipamento
* Personagem

Esta classificação permanece aberta para novos tipos de carta conforme o desenvolvimento do projeto e a análise do acervo original.

#### Informações e características das cartas

As cartas podem apresentar diferentes informações conforme seu tipo e finalidade, incluindo:

* Título
* Subtítulo
* Tipo de Carta
* Nível de acesso
* Relações de acesso com Classes e Personagens
* Deck, Subdeck ou Extra-Deck em que está organizada
* Valores importantes
* Ataque
* Efeito
* Duração
* Quantidade de turnos
* Tabelas
* Regras
* Outras informações específicas do tipo de carta

Nem todas as cartas possuem os mesmos campos. As informações apresentadas dependem do tipo e da finalidade da carta.

#### Frente e verso

As cartas são projetadas para utilização em frente e verso.

A frente prioriza a apresentação visual e as informações mais importantes para identificação e consulta rápida, podendo incluir:

* Imagem
* Título
* Subtítulo
* Valores ou informações essenciais

O verso pode conter informações complementares, regras detalhadas, tabelas e outras informações necessárias para a utilização da carta.

#### Séries de cartas

Uma informação ou regra pode ser distribuída por uma sequência de cartas quando seu conteúdo não couber adequadamente em uma única carta.

Cartas relacionadas podem formar uma série identificada por numerais ou outras marcações de continuidade, como:

* I
* II
* III
* IV

Essas cartas podem representar continuações, níveis, desdobramentos ou partes de um mesmo conteúdo.

Uma série pode utilizar o mesmo título ou títulos relacionados, podendo também utilizar subtítulos diferentes para distinguir suas partes.

#### Versões e personalização

Uma mesma carta ou conteúdo pode possuir diferentes versões visuais ou editoriais.

Uma versão pode ser preparada especificamente para um Deck de Classe ou para um personagem, sem que isso signifique que o conteúdo seja exclusivo daquela classe ou personagem.

A personalização pode incluir, entre outros elementos:

* Imagem do personagem
* Arte específica
* Identificação do Deck
* Outras adaptações visuais

Uma mesma carta pode, portanto, possuir representações diferentes para diferentes Decks ou personagens.

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
* Decks de Personagem
* Outros decks gerais ou específicos

Um Deck pode possuir cartas diretamente associadas a ele e também utilizar coleções subordinadas para organizar conteúdos mais gerais ou especializados.

#### Extra-Decks

Extra-Decks são tipos formais de coleção utilizados para reunir conteúdos complementares ou especializados.

Podem existir dentro de outros Decks ou coleções e podem conter cartas ou outras coleções.

Um Extra-Deck pode, por exemplo, organizar cartas de uma área específica de conteúdo que seja compartilhada ou utilizada por diferentes Decks.

#### Subdecks

Subdecks são tipos formais de coleção subordinados a outra coleção e destinados a organizar conjuntos menores e mais específicos de conteúdo.

Um Subdeck pode ser utilizado quando uma coleção possui um conjunto pequeno, temático, específico ou suplementar de cartas.

#### Deck-Ficha

O Deck-Ficha é uma coleção associada a um personagem específico.

Ele pode reunir a Carta do Personagem, o Deck do Personagem e outros Decks, Extra-Decks, Subdecks e recursos aos quais o personagem tenha ou venha a ter acesso.

O Deck-Ficha pode crescer ou ser modificado conforme a evolução do personagem no jogo.

### Relações

A organização do projeto pode estabelecer relações entre diferentes elementos.

Uma relação geral pode ser representada como:

**Classe → Deck → Coleções → Cartas**

A organização de um personagem pode ser representada como:

**Personagem → Deck-Ficha → Decks / Extra-Decks / Subdecks → Cartas**

Essas relações não formam necessariamente uma árvore rígida. Uma mesma carta pode estar incluída em diferentes coleções quando for compatível com elas.

O acesso de uma classe ou personagem a uma carta depende das regras do sistema e das relações estabelecidas entre seus respectivos Decks e coleções.

Uma magia, por exemplo, pode ser incluída no Deck de Magias de diferentes Decks de Classe quando essas classes possuem acesso à magia segundo as regras do jogo.

Uma mesma carta não precisa ser duplicada conceitualmente apenas porque aparece em diferentes coleções.

### Combos

Combinações entre cartas que produzem efeitos ou estratégias relevantes.

Os combos podem envolver cartas pertencentes ao mesmo Deck ou cartas provenientes de diferentes coleções compatíveis.

### Infográficos

Materiais visuais destinados a explicar regras, relações, progressões e combos complexos.

Infográficos podem ser organizados em coleções próprias ou associados a Decks, personagens e outros elementos do projeto.

### Fichas

As fichas representam personagens e seus respectivos estados, informações e recursos.

Uma ficha está associada a um Deck-Ficha, que organiza os recursos e coleções relacionados ao personagem.

### Miniaturas

Miniaturas são recursos visuais associados a personagens ou outras entidades representadas no projeto.

Podem ser organizadas dentro de coleções relacionadas a personagens, Decks ou outros elementos.

### Documentação

Regras, conceitos, decisões de design e documentação técnica do projeto.

## Desenvolvimento

O projeto será desenvolvido de forma incremental, utilizando Git e GitHub para controle de versão.

As decisões conceituais importantes serão documentadas e versionadas ao longo do desenvolvimento.

## Estado atual

O acervo original contém aproximadamente 500 arquivos relacionados às cartas e outros materiais do projeto.

O acervo inclui cartas de diferentes tipos, versões visuais, arquivos de trabalho e outros recursos relacionados ao desenvolvimento do sistema.

O acervo original será preservado durante o processo de organização e desenvolvimento.

A classificação dos tipos de cartas, coleções e demais elementos permanece aberta para expansão conforme a análise do acervo e o desenvolvimento do projeto.
