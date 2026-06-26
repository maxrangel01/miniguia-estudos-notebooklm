# Este repositório reúne materiais, exemplos e boas práticas para aprender a utilizar o NotebookLM de forma eficiente.

O objetivo é mostrar como transformar documentos em uma base de conhecimento inteligente, permitindo realizar pesquisas, resumos, perguntas e gerar conteúdos com apoio da IA.

Assunto: Programação orientada a objeto

Curadoria de Fontes:
- Python_3_Object-Oriented_Programming_(en).pdf
- https://docs.python.org/3/tutorial/classes.html
- https://realpython.com/python3-object-oriented-programming/
- https://python-textbok.readthedocs.io/en/latest/Classes.html

Engenharia de Prompts e "Cicatrizes":
  -Comporte-se como um professor de programação de python
  -quais sao os pilares da programação orientada a objeto
  -Por onde começar a programar com orientação a obheto com python
  -crie um exemplo simples de uma classe Pessoa
  -o que e necessario para virar um bom programador

Resumos:
A aprendizagem de Programação Orientada a Objetos (POO) com Python fundamenta-se na compreensão de que, nesta linguagem, tudo é tratado como um objeto
. Este paradigma permite que desenvolvedores modelem entidades do mundo real em código, agrupando dados e comportamentos de forma lógica e organizada
.
Abaixo, apresento um resumo dos conceitos e estruturas centrais para dominar POO em Python:
1. Blocos de Construção Fundamentais
Classes e Objetos: Uma classe funciona como um projeto ou molde que define a estrutura de um tipo de objeto
. Um objeto é uma instância física desse molde, contendo dados específicos
.
Atributos e Métodos: Atributos representam as características (dados) do objeto, enquanto métodos são as ações (funções) que ele pode realizar
.
O Método __init__ e o self: O inicializador __init__ é executado automaticamente ao criar um objeto para definir seu estado inicial
. O parâmetro self é obrigatório em métodos de instância e representa o objeto específico que está sendo manipulado
.
2. Os Quatro Pilares da POO
Encapsulamento: Consiste em agrupar dados e métodos, protegendo a integridade do objeto
. Em Python, o controle de acesso é feito por convenções: um sublinhado (_) indica uso interno e dois sublinhados (__) ativam a desconfiguração de nomes (name mangling) para evitar colisões
. O uso de propriedades (@property) permite validar dados com uma sintaxe limpa
.
Abstração: Foca em esconder detalhes complexos e expor apenas o essencial
. É implementada através do módulo abc (Abstract Base Classes), que define contratos para subclasses
.
Herança: Permite que uma classe filha herde atributos e métodos de uma classe pai, promovendo o reuso de código
. Python suporta herança múltipla, utilizando o algoritmo C3 Linearization para determinar a Ordem de Resolução de Métodos (MRO)
.
Polimorfismo: Permite que diferentes classes respondam à mesma chamada de método de maneiras específicas
. É fortemente ligado ao conceito de Duck Typing: se um objeto se comporta como o esperado (tem os métodos necessários), ele é aceito independentemente de sua herança
.
3. Mecanismos Avançados e Boas Práticas
Métodos Especiais (Dunders): Métodos iniciados e terminados com duplo sublinhado (como __len__ ou __str__) permitem que classes customizadas interajam nativamente com operadores e funções da linguagem
.
Composição vs. Herança: Recomenda-se frequentemente favorecer a composição (ter um objeto como atributo de outro) em detrimento de hierarquias de herança muito profundas para evitar rigidez no sistema
.
Princípios SOLID e DRY: Um bom programador aplica os princípios SOLID para criar sistemas modulares e segue a máxima DRY (Don't Repeat Yourself), evitando a duplicidade de lógica no código
.
Dominar esses conceitos transforma a escrita de scripts básicos na construção de aplicações robustas, escaláveis e de fácil manutenção
