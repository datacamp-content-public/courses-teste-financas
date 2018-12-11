---
title: 'Introdução ao ggplot2'
description: 'Primeira abordagem ao pacote ggplot e suas funcionalidades.'
---

## Insert exercise title here

```yaml
type: VideoExercise
key: d12e3704df
xp: 50
```

`@projector_key`
f0192db45a169d2339d8575a23c36899

---

## Example coding exercise

```yaml
type: NormalExercise
key: 2bafef99a3
lang: r
xp: 100
skills: 1
```

Se você já sabe o básico do R **vai ser moleza** usar o ggplot para plotar seus gráficos de forma rápida **e sem usar Excel**.

Para contextualizar nossos estudos, vamos usar como ponto de partida o primeiro gráfico de barra de que se tem notícia. Em 1785 William Playfair fez esse gráfico aqui:

![](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e0/1786_Playfair_-_Exports_and_Imports_of_Scotland_to_and_from_different_parts_for_one_Year_from_Christmas_1780_to_Christmas_1781.jpg/500px-1786_Playfair_-_Exports_and_Imports_of_Scotland_to_and_from_different_parts_for_one_Year_from_Christmas_1780_to_Christmas_1781.jpg)

Vamos reproduzi-lo!

`@instructions`
Já carregamos o dataset que contém os dados que playfair usou. Você precisa checar se está tudo em ordem, confira o valor da variável **playfair4**

`@hint`
Essa é fácil. Basicamente digite o nome da variável na console e você vai ver o valor dela.

`@pre_exercise_code`
```{r}
playfair4 <- c(1:100)
```

`@sample_code`
```{r}
______
```

`@solution`
```{r}
playfair4
```

`@sct`
```{r}

```

---

## Insert exercise title here

```yaml
type: NormalExercise
key: bc03177aa1
xp: 100
```

Agora que você já viu que a variável trata-se de um vetor de 100 posições, vamos multiplicar esse vetor todo por 1000.

`@instructions`
Essa é bem simples. Para multiplicar no R usamos o comando *.
Basta chamar a variável playfair4 e multiplica-la por 1000.

`@hint`
escreva o nome da variável, o sinal de multiplicação e o valor 1000.

`@pre_exercise_code`
```{r}
playfair4 <- c(1:100)
```

`@sample_code`
```{r}
________ * ____
```

`@solution`
```{r}
playfair4 * 1000
```

`@sct`
```{r}

```
