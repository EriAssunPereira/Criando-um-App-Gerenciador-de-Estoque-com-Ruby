# **Criando um App Gerenciador de Estoque com Ruby**

## **Introdução**
Neste artigo, vamos explorar a criação de um aplicativo gerenciador de estoque utilizando a linguagem Ruby. Vamos focar na organização procedural do projeto, que se baseia no uso de procedimentos e funções para realizar tarefas específicas, garantindo uma sequência lógica de instruções e facilitando a manutenção do código.

## **1. Estrutura do Projeto**
A organização clara do projeto é essencial. Vamos dividir nosso aplicativo em módulos específicos:

### **1.1. Módulo de Produtos**
Responsável por gerenciar os produtos em estoque.

### **1.2. Módulo de Vendas**
Gerencia as vendas e atualiza o estoque.

### **1.3. Módulo de Relatórios**
Fornece relatórios sobre o estado atual do estoque e histórico de vendas.

## **2. Solução Procedural em Ruby**
Ruby é uma linguagem que suporta tanto paradigmas orientados a objetos quanto procedurais. Vamos utilizar o paradigma procedural para este projeto.

### **2.1. Definição de Funções**
Cada tarefa será realizada por uma função específica, tornando o código reutilizável e fácil de entender.

### **2.2. Exemplo de Função de Adição de Produto**
```ruby
def adicionar_produto(nome, quantidade)
    # Lógica para adicionar produto ao estoque
end
```

## **3. Implementação dos Módulos**

### **3.1. Módulo de Produtos**
```ruby
# produtos.rb

def adicionar_produto(nome, quantidade)
    # Adiciona um novo produto ao estoque
end

def remover_produto(nome)
    # Remove um produto do estoque
end

def atualizar_quantidade(nome, nova_quantidade)
    # Atualiza a quantidade de um produto específico
end
```

### **3.2. Módulo de Vendas**
```ruby
# vendas.rb

def registrar_venda(produto, quantidade)
    # Registra uma venda e atualiza o estoque
end

def calcular_total_vendas
    # Calcula o total de vendas realizadas
end
```

### **3.3. Módulo de Relatórios**
```ruby
# relatorios.rb

def gerar_relatorio_estoque
    # Gera um relatório do estoque atual
end

def gerar_relatorio_vendas
    # Gera um relatório das vendas realizadas
end
```

## **4. Execução do Programa**
O programa principal irá interagir com os módulos e executar as funções necessárias.

### **4.1. Programa Principal**
```ruby
# main.rb

require_relative 'produtos'
require_relative 'vendas'
require_relative 'relatorios'

# Exemplo de execução de funções
adicionar_produto('Teclado', 50)
registrar_venda('Teclado', 1)
gerar_relatorio_estoque
```

## **Conclusão**
A abordagem procedural em Ruby permite criar um aplicativo gerenciador de estoque de forma estruturada e organizada. Com funções claras e reutilizáveis, o desenvolvimento e a manutenção do software se tornam mais eficientes. Este projeto pode ser um excelente aditivo ao seu portfólio, demonstrando sua habilidade em organizar e implementar soluções de software.

Espero que este artigo tenha sido útil e que você se sinta inspirado a criar seu próprio gerenciador de estoque em Ruby.
