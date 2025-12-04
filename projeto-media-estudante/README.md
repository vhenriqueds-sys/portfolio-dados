# 📘 Projeto: Média do Estudante

Este projeto calcula a **média das notas de um estudante**, usando um dicionário em Python que contém as notas de cada trimestre.

---

## 🎯 Objetivo do Projeto

Aprender a:

* Utilizar **dicionários** em Python.
* Acessar valores usando `.values()`.
* Fazer somas utilizando loops.
* Calcular média com **uma casa decimal**.

---

## 🧠 Como funciona

As notas vêm em um dicionário nesse formato:

```python
notas = {
    '1º Trimestre': 8.5,
    '2º Trimestre': 7.5,
    '3º Trimestre': 9
}
```

O programa percorre os valores desse dicionário, soma tudo e divide pelo número de itens.

---

## 🧩 Código do Projeto

```python
notas = {'1º Trimestre': 8.5, '2º Trimestre': 7.5, '3º Trimestre': 9}

soma = 0
for nota in notas.values():
    soma += nota

media = round(soma / len(notas), 1)
print(f"A média do estudante é: {media}")
```

---

## 📎 Exemplo de saída

```
A média do estudante é: 8.3
```

---

## 🛠️ Tecnologias utilizadas

* Python 3
* Google Colab

---

## 📚 Aprendizados

Durante este projeto, foi possível aprender:

* Como trabalhar com dicionários.
* Como iterar com loops `for`.
* Como usar `round()` para formatar casas decimais.
* Lógica básica de programação.

---

## 🚀 Próximos Passos

Ideias para evoluir este projeto:

* Permitir inserir notas manualmente.
* Calcular médias de vários alunos.
* Gerar um relatório automático.

---

## ✨ Autor

Projeto desenvolvido por **Vitor Henrique** como parte do seu portfólio de estudos em Python.
