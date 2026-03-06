# 🧮 Projeto Calculadora com .NET CLI

Neste projeto desenvolvi uma aplicação de **calculadora no terminal utilizando C# e .NET CLI**.  
A aplicação permite que o usuário digite dois números e escolha uma operação matemática para calcular o resultado.

O objetivo foi praticar a criação de projetos via **linha de comando**, além de aplicar conceitos básicos de programação como **entrada de dados, estruturas condicionais e operações matemáticas**.

---

# 🛠️ Comandos de Construção Utilizados

- `dotnet new console`  
  Utilizado para criar a estrutura base de um projeto console em C#.

- `dotnet build`  
  Responsável por **compilar o código**, transformando o programa em um executável que o computador consegue rodar.

- `dotnet run`  
  Executa o programa diretamente no terminal após a compilação.

---

# 📦 Estrutura do Projeto

Arquivos principais gerados pelo .NET:

1. `Program.cs`  
   Arquivo onde está o código da aplicação da calculadora.

2. `Calculadora.csproj`  
   Arquivo de configuração do projeto .NET, onde ficam as definições como framework utilizado e propriedades do projeto.

---

# ⚙️ Funcionamento da Calculadora

O programa executa o seguinte fluxo:

1. Solicita ao usuário o **primeiro número**
2. Solicita o **segundo número**
3. Mostra as opções de operação matemática:
   - Adição
   - Subtração
   - Multiplicação
   - Divisão
4. O usuário escolhe a operação
5. O sistema calcula e mostra o resultado

Caso o usuário tente **dividir por zero**, o programa exibe uma mensagem de erro.

---

# 🧪 Atividade Prática 3

Durante a atividade também foram utilizados os seguintes comandos do .NET CLI:

**1 - Criação dos projetos**
- `dotnet new webapi`
- `dotnet new xunit`

**2 - Status**
- Projetos criados com sucesso.

**3 - Framework utilizado**
- `.NET 10.0 (net10.0)`

---

# 💻 Tecnologias Utilizadas

- C#
- .NET CLI
- .NET 10.0
- Console Application
