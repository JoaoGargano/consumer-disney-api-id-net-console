# ConsumerDisneyIdApi

Aplicação console em C# (.NET) que consome a [Disney API](https://disneyapi.dev/) para buscar e exibir os dados de um personagem específico (ID 423 - Big Bad Wolf) no terminal.

## 🌐 API Utilizada

- **Endpoint:** `https://api.disneyapi.dev/character/423`
- **Método:** GET
- **Retorno:** JSON com os dados do personagem (nome, imagem, filmes, etc)

## 🛠️ Tecnologias

- C# / .NET
- `HttpClient` — para realizar a comunicação HTTP com a API
- `Newtonsoft.Json` — para transformar (desserializar) o texto JSON em objetos C#
