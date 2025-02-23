# Introdução ao Python 🐍

## Comandos Básicos

### 1. Entrada e Saída

- **Entrada**: Usamos a função `input()` para receber dados do usuário.

  ```python
  nome = input("Qual é o seu nome? ")
  ```

- **Saída**: Usamos a função `print()` para exibir dados na tela.

  ```python
  print("Olá,", nome)
  ```

### 2. Tipos de Dados 📊

Python possui diferentes tipos de dados, incluindo:

- **Inteiros** (`int`): Números inteiros.
  
  ```python
  idade = 25  # int
  ```

- **Ponto Flutuante** (`float`): Números decimais.
  
  ```python
  altura = 1.75  # float
  ```

- **Strings** (`str`): Texto.
  
  ```python
  cidade = "São Paulo"  # str
  ```

- **Booleano** (`bool`): Verdadeiro ou Falso.
  
  ```python
  ativo = True  # bool
  ```

### 3. Conversões de Tipos 🔄

Podemos converter tipos de dados usando funções integradas:

- **Converter para inteiro**: `int()`
  
  ```python
  numero = int("10")
  ```

- **Converter para float**: `float()`
  
  ```python
  numero_float = float("10.5")
  ```

- **Converter para string**: `str()`
  
  ```python
  numero_str = str(10)
  ```

### 4. Usando `print()` de Diferentes Modos 🖨️

#### 4.1. Método Básico

- Exibindo texto simples:

  ```python
  print("Olá, mundo!")
  ```

#### 4.2. Usando `sep` e `end`

- **Separador**: Use o parâmetro `sep` para definir como os elementos são separados.

  ```python
  print("Olá", "mundo", sep="-")  # Olá-mundo
  ```

- **Fim de linha**: Use o parâmetro `end` para definir o que vem após a mensagem.

  ```python
  print("Olá", end=" ")
  print("mundo!")  # Olá mundo!
  ```

#### 4.3. Formatação com F-Strings

- **F-strings**: Usando f-strings para interpolação de variáveis.

  ```python
  idade = 25
  print(f"Eu tenho {idade} anos.")  # Eu tenho 25 anos.
  ```

#### 4.4. Formatação com `str.format()`

- Usando o método `str.format()` para formatação.

  ```python
  nome = "Maria"
  print("Olá, {}!".format(nome))  # Olá, Maria!
  ```

#### 4.5. Formatação com o operador `%`

- Usando o operador `%` para formatação.

  ```python
  idade = 30
  print("Você tem %d anos." % idade)  # Você tem 30 anos.
  ```

### 5. Operadores

Python suporta diversos operadores:

- **Aritméticos**: `+`, `-`, `*`, `/`, `%`
  
  ```python
  soma = 10 + 5  # 15
  ```

- **Comparação**: `==`, `!=`, `>`, `<`, `>=`, `<=`
  
  ```python
  is_maior = 10 > 5  # True
  ```

- **Lógicos**: `and`, `or`, `not`
  
  ```python
  resultado = (10 > 5) and (5 < 8)  # True
  ```

### 6. Variáveis

- Uma variável é um espaço na memória que armazena um valor. Os nomes das variáveis devem ser significativos e seguir algumas regras:

  - Não podem começar com um número.
  - Não podem conter espaços ou caracteres especiais (exceto `_`).
  
  ```python
  nome_usuario = "João"  # Variável válida
  ```

### 7. Indentação

A indentação é crucial em Python e define blocos de código. Utilize 4 espaços ou um tab para indentar.

```python
if idade >= 18:
    print("Você é maior de idade.")  # Indentação correta
```

---



