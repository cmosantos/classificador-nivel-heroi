# Classificador de Nível de Herói

Projeto desenvolvido como parte de um desafio de lógica de programação da DIO.

## Objetivo

O programa armazena o nome e a quantidade de experiência de um herói e, com base no valor de XP, determina o nível correspondente.

## Conceitos utilizados

- Variáveis
- Operadores
- Estruturas condicionais
- Laços de repetição
- Funções
- Arrays e objetos

## Classificação

| Experiência | Nível |
|---|---|
| Até 1.000 XP | Ferro |
| De 1.001 a 2.000 XP | Bronze |
| De 2.001 a 5.000 XP | Prata |
| De 5.001 a 7.000 XP | Ouro |
| De 7.001 a 8.000 XP | Platina |
| De 8.001 a 9.000 XP | Ascendente |
| De 9.001 a 10.000 XP | Imortal |
| A partir de 10.001 XP | Radiante |

## Como executar

É necessário ter o Node.js instalado.

Clone o repositório:

```bash
git clone URL_DO_SEU_REPOSITORIO
```

Entre na pasta do projeto:

```bash
cd classificador-nivel-heroi
```

Execute o programa:

```bash
node index.js
```

## Exemplo de saída

```text
O Herói de nome Cláudio está no nível de Ascendente
```

## Personalização

Para testar outro nome ou valor de experiência, altere o objeto localizado no início do arquivo `index.js`:

```javascript
const herois = [
  { nome: "Cláudio", xp: 8500 }
];
```

Também é possível adicionar outros heróis ao array:

```javascript
const herois = [
  { nome: "Cláudio", xp: 8500 },
  { nome: "Atena", xp: 10500 }
];
```

## Autor

Cláudio Menezes de Oliveira Santos
