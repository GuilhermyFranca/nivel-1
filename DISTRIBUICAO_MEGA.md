# Distribuição pelo MEGA

## Finalidade

O MEGA é utilizado como meio de distribuição dos materiais do projeto Nível 1 aos jogadores.

Enquanto o GitHub é utilizado principalmente para desenvolvimento, documentação e versionamento do projeto, o MEGA funciona como o espaço onde os materiais destinados à utilização no jogo são disponibilizados.

---

## Pasta principal

A distribuição do projeto é centralizada em uma pasta principal:

```text
Nível 1/
```

Essa pasta funciona como o ponto de entrada dos materiais disponibilizados aos jogadores.

---

## Organização por classe

A organização atual do MEGA é feita principalmente por classe.

Cada classe possui sua própria pasta dentro de `Nível 1`.

Exemplo:

```text
Nível 1/
├── Guerreiro/
├── Ladino/
├── Mago/
├── Monge/
└── Ranger/
```

Novas classes podem receber suas próprias pastas conforme forem incorporadas ao projeto.

Não é necessário criar antecipadamente pastas para classes ou categorias que ainda não possuam materiais a serem distribuídos.

---

## Cartas das classes

As cartas destinadas a uma determinada classe são colocadas na pasta correspondente àquela classe.

A organização tem como objetivo facilitar o acesso dos jogadores aos materiais que podem ser utilizados por seus personagens.

A quantidade e o tipo de cartas podem variar entre as classes.

Não é necessário que todas as classes possuam a mesma estrutura ou a mesma quantidade de materiais.

---

## Cartas arquivadas

Cada pasta de classe possui uma pasta:

```text
Arquivadas/
```

Essa pasta é utilizada para conservar versões descartadas ou substituídas das cartas.

Exemplo:

```text
Nível 1/
└── Guerreiro/
    ├── carta-atual.png
    └── Arquivadas/
        ├── carta-versao-anterior.png
        └── carta-versao-teste.png
```

As versões arquivadas não representam o material atualmente destinado aos jogadores.

Sua preservação permite manter um histórico das versões produzidas e possibilita recuperar ou consultar materiais anteriores quando necessário.

---

## Processo de distribuição

O processo atual é incremental.

Quando uma carta é produzida e considerada adequada para distribuição, ela pode ser colocada na pasta correspondente à classe no MEGA.

Quando uma carta é substituída por uma versão mais recente, a versão anterior pode ser transferida para `Arquivadas/`.

O processo geral é:

```text
Produção
   ↓
Revisão
   ↓
Carta pronta
   ↓
Cópia para o MEGA
   ↓
Pasta da classe
   ↓
Disponibilização aos jogadores
```

Quando uma versão é substituída:

```text
Nova versão
   ↓
Pasta da classe

Versão anterior
   ↓
Arquivadas/
```

---

## Organização incremental

A estrutura do MEGA não precisa ser planejada integralmente antes da produção dos materiais.

Novas classes, pastas ou formas de organização podem ser criadas conforme surgirem necessidades concretas durante o desenvolvimento e a utilização do jogo.

A organização deve permanecer simples e prática, priorizando a facilidade de acesso aos materiais pelos jogadores.

---

## Relação com o GitHub

O MEGA e o GitHub possuem funções diferentes.

**GitHub:**

* desenvolvimento;
* documentação;
* versionamento;
* registros de decisões;
* histórico do projeto;
* arquivos necessários ao desenvolvimento.

**MEGA:**

* distribuição;
* materiais destinados aos jogadores;
* versões atualmente disponibilizadas;
* organização prática para utilização durante o jogo.

Nem todo arquivo existente no GitHub precisa ser colocado no MEGA.

Da mesma forma, o MEGA não precisa reproduzir a estrutura interna do repositório GitHub.

---

## Estado atual

A estrutura atual do MEGA consiste em uma pasta principal `Nível 1`, subdividida por classe.

Cada pasta de classe possui uma pasta `Arquivadas/` para versões descartadas ou substituídas.

A estrutura poderá ser modificada conforme o projeto evoluir e novas necessidades forem identificadas.
