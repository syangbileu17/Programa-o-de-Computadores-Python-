# 🎓 Elite Way School - Sistema de Gestão Acadêmica

## 📖 Sobre o Projeto

O **Elite Way School** é um sistema acadêmico desenvolvido em **Python** com o objetivo de simular o gerenciamento de notas e frequência de estudantes da Educação Básica.

O projeto foi criado para aplicar conceitos fundamentais de programação, lógica computacional e estruturação de sistemas, permitindo o cadastro e acompanhamento do desempenho escolar dos alunos de forma simples e eficiente.

Ao final da execução, o sistema gera um **boletim escolar completo**, contendo médias, frequência e situação final de cada disciplina.

---

## 🚀 Funcionalidades

* 👤 Cadastro do nome do estudante;
* 📝 Registro de notas (**A1** e **A2**) por disciplina;
* ✅ Validação de notas (0 a 10);
* 📊 Registro e validação da frequência escolar (0% a 100%);
* 🧮 Cálculo automático da média por disciplina;
* 📌 Verificação da frequência mínima exigida;
* 🎯 Classificação automática da situação do aluno:

  * ✅ Aprovado
  * ❌ Reprovado por Nota
  * ❌ Reprovado por Frequência
* 📄 Geração de boletim escolar detalhado;
* 📈 Exibição de resumo geral do desempenho acadêmico.

---

## 📚 Disciplinas Avaliadas

O sistema contempla as seguintes disciplinas:

* Português
* Matemática
* Geografia
* História
* Ciências
* Artes

---

## 📋 Regras de Aprovação

Para ser aprovado em uma disciplina, o estudante deve atender aos seguintes critérios:

* Média final **maior ou igual a 6,0**;
* Frequência **maior ou igual a 75%**.

### Critérios de Resultado

| Situação                   | Condição                                     |
| -------------------------- | -------------------------------------------- |
| ✅ Aprovado                 | Média ≥ 6,0 e Frequência ≥ 75%               |
| ❌ Reprovado por Nota       | Média < 6,0 e Frequência ≥ 75%               |
| ❌ Reprovado por Frequência | Frequência < 75%, independentemente da média |

---

## 🛠️ Tecnologias Utilizadas

* Python 3
* Funções
* Listas
* Dicionários
* Estruturas de decisão (`if`, `elif`, `else`)
* Estruturas de repetição (`while`)
* Validação de entrada de dados

---

## 📂 Estrutura do Projeto

```bash
elite-way-school/
│
├── main.py
└── README.md
```

---

## ▶️ Como Executar

### 1️⃣ Clone o repositório

```bash
git clone https://github.com/seu-usuario/elite-way-school.git
```

### 2️⃣ Acesse a pasta do projeto

```bash
cd elite-way-school
```

### 3️⃣ Execute o programa

```bash
python main.py
```

---

## 🎯 Objetivos de Aprendizagem

Este projeto foi desenvolvido para praticar:

* Programação em Python;
* Modularização através de funções;
* Manipulação de listas e dicionários;
* Tratamento e validação de entradas;
* Organização e legibilidade de código;
* Desenvolvimento de sistemas acadêmicos básicos.

---

## 💡 Conceitos Aplicados

Durante o desenvolvimento foram trabalhados conceitos importantes como:

* Entrada e saída de dados;
* Estruturas condicionais;
* Estruturas de repetição;
* Funções reutilizáveis;
* Manipulação de coleções de dados;
* Lógica de negócios para aprovação escolar.

---

## 👨‍💻 Autor

Projeto desenvolvido para fins acadêmicos e educacionais, aplicando conceitos de programação e lógica computacional na construção de um sistema de gestão escolar.

**Desenvolvido com Python ❤️**
