# CLI bilíngue para correção automatizada de gabaritos

Idiomas disponíveis: Português (Brasil) e Guineense


## 🚀 Instalando

- Requisito: compilador C++ ou IDE com suporte a esta linguagem. Recomendamos o compilador g++ do GCC (GNU Compiler Collection)
- Salve apenas o arquivo `corretor.cpp` em sua máquina
- A seguir, compile o arquivo e execute o programa gerado

Compilação e execução em Linux com g++:

```
g++ corretor.cpp -o corretor.exe
./corretor.exe
```

Compilação e execução em Windows com g++:

```
g++ corretor.cpp -o corretor.exe
corretor.exe
```

## ☕ Como usar

1. Ao iniciar o programa, você deve escolher entre as duas linguagens disponíveis: Português ou Guineense

2. A seguir, você deve escolher entre o modo manual ou randômico.

  - No **Modo Manual** você irá manualmente inserir o gabarito e as respostas de cada candidato.

  - No **Modo Randômico** são gerados automaticamente dados mock para teste.

![Menu Inicial](https://github.com/juhachmann/correcao_gabaritos/blob/main/menu_inicial.png) 

3. Após inserir os dados solicitados, o programa irá corrigir os gabaritos dos candidatos e gerará alguns relatórios e o ranking de classificação.
  
Para gabaritos com até 10 questões, o ranking de classificação é exibido em formato de tabela.

 ![Ranking](https://github.com/juhachmann/correcao_gabaritos/blob/main/relatorio.png) 


Para corrigir outro gabarito, reinicie a execução do programa. 


## ‼️ Disclaimer

Este pequeno projeto foi desenvolvido como trabalho final na disciplina de Lógica de Programação (2022.2) - Curso Técnico em Desenvolvimento de Sistemas/IFSC. 

Este código não segue nenhuma boa prática, não faz ideia do que é gerenciamento de memória e tem apenas uma leve noção de que iterar muitas vezes por uma lista longa pode ser uma má ideia. Não nos responsabilizamos por danos em sua máquina. 🧯

O desafio foi apenas aplicar os conceitos básicos de programação e produzir um código de arquivo único, utilizando as bibliotecas mais fundamentais da linguagem, tipos primitivos e de estilo procedural. Foi uma atividade para exercitar lógica básica de programação, além de tópicos como vetores, ponteiros, sobrecarga de função e Bubble Sort. 


## Equipe: 
Charles Parpineli<br>
Juliana Hachmann<br>
Mamadú Saliu<br>

