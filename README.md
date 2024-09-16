# Codificação para Back End - SENAI

Este repositório contém o código desenvolvido para a atividade de Codificação para Back End do SENAI. O projeto é construído utilizando .NET 8 e segue as melhores práticas para desenvolvimento de software.

## Estrutura do Projeto

A estrutura do projeto é organizada da seguinte forma:

- **bin/Debug/net8.0/**: Diretório que contém os arquivos compilados do projeto.
- **obj/**: Diretório utilizado para arquivos temporários durante o processo de construção.
- **Atividade.csproj**: Arquivo de projeto do .NET que define as configurações e dependências do projeto.
- **Clientes.cs**: Arquivo de código que contém a implementação da classe `Clientes`.
- **Pessoa_fisica.cs**: Arquivo de código que define a classe `PessoaFisica`.
- **Pessoa_Juridica.cs**: Arquivo de código que define a classe `PessoaJuridica`.
- **Program.cs**: Arquivo principal que contém o ponto de entrada para a aplicação.

## Instruções para Execução

Para executar o projeto, siga as etapas abaixo:

1. **Clonar o Repositório**

   ```bash
   git clone <URL_DO_REPOSITORIO>
   ```
2. **Navegar até o Diretório do Projeto**

   ```bash
   cd <DIRETORIO_DO_PROJETO>
   ```
3. **Restaurar as Dependências**

   ```bash
   dotnet restore
   ```
4. **Compilar o Projeto**

   ```bash
   dotnet build
   ```
5. **Executar o Projeto**
   
   ```bash
   dotnet run
   ```
## Descrição das Classes

- **Clientes.cs**: 
  - Implementa a lógica relacionada aos clientes no sistema. 
  - Contém métodos para gerenciar e operar sobre os dados dos clientes.

- **Pessoa_fisica.cs**: 
  - Define a estrutura e comportamento de uma pessoa física. 
  - Inclui propriedades e métodos específicos para representar uma pessoa física no sistema.

- **Pessoa_Juridica.cs**: 
  - Define a estrutura e comportamento de uma pessoa jurídica. 
  - Inclui propriedades e métodos específicos para representar uma pessoa jurídica no sistema.

- **Program.cs**: 
  - Contém o código principal para iniciar a aplicação. 
  - Configura o ambiente e inicia a execução da aplicação.

## Testes

Se o projeto inclui testes, você pode executá-los com o seguinte comando:

```bash
dotnet test
```
## Contribuição

Se você deseja contribuir para este projeto, siga as diretrizes de contribuição a seguir:

1. **Fork o Repositório**: Crie uma cópia do repositório para suas próprias modificações.
2. **Crie uma Branch para sua Feature**: Crie uma branch a partir da branch principal para suas alterações.
3. **Faça as Alterações Necessárias**: Realize as alterações e faça commits.
4. **Submeta um Pull Request**: Envie um pull request para a branch principal do repositório.


