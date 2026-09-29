# 📊 Calculadora de Média de Alunos #

*Este projeto consiste em uma calculadora simples desenvolvida em **Python**, criada para calcular a média de um aluno a partir de suas notas.*
*O programa recebe as notas, realiza o cálculo da média e apresenta o resultado, indicando de forma simples o desempenho do aluno.*
# 🛠️ Tecnologias utilizadas#
- ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
- ![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)

### 🎯 Objetivo
*O projeto foi desenvolvido como uma prática dos conceitos básicos de programação em Python, como variáveis, entrada de dados, operações matemáticas e estruturas condicionais.*

### 🤖 Código da aplicação :
```
def calcular_media(nota1, nota2):
    return (nota1 + nota2) /2
print("=== Sistema de Notas do Aluno ===")
n1= float(input("Digite a primeira nota: "))
n2= float(input("Digite a segunda nota: "))
media= calcular_media(n1, n2)
print(f"A média final é: {media:.2f}")
```
```
if media >= 7.0:
    print("Status: Aprovado!")
else:
 print("Status : Reprovado.")
```
