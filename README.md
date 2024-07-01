# Gerenciador de Posts

Desafie suas habilidades em C# criando um Gerenciador de Posts dinâmico que consome a API JSONPlaceholder! Desenvolva uma aplicação backend completa que inicialmente popula sua base de dados com informações da API JSONPlaceholder, mas que, em seguida, realiza todas as operações (exibição, adição, deleção) diretamente a partir do banco de dados. Aprimore suas habilidades de integração com APIs e demonstre suas capacidades em arquitetura de software e boas práticas de programação. Participe e mostre seu talento em desenvolvimento backend!

## Objetivo
Implementar uma aplicação backend RESTful em C# que gerencie uma lista de posts. A aplicação deve:
- Consumir a API JSONPlaceholder para buscar e exibir dados.
- Popular sua base de dados com os dados da API JSONPlaceholder inicialmente.
- Realizar todas as operações subsequentes diretamente a partir do banco de dados e não da API.

## Tarefas do Projeto

### 1. Configuração Inicial
- Configure um novo projeto em C# (console app, web API, etc.).
- Utilize bibliotecas populares para chamadas HTTP (ex.: HttpClient) e ORM (ex.: Entity Framework).

### 2. Consumir a API JSONPlaceholder
- Faça uma requisição à API `https://jsonplaceholder.typicode.com/posts` para obter a lista de 100 posts iniciais.
- Armazene os dados completos (`id`, `title` e `body`) dos posts em um banco de dados usando Entity Framework.
- Todo o restante das operações (leitura, criação, atualização, exclusão) deve ser feito no banco de dados e não diretamente na API.

### 3. Exibir Lista de Posts
- Crie um endpoint que exiba a lista de posts armazenados no banco de dados.
- Cada item da lista deve mostrar apenas o `id` e o `title` do post.

### 4. Adicionar Novo Post
- Implemente um endpoint para adicionar um novo post e salvá-lo no banco de dados.
- Atualize a lista de posts localmente após adicionar o novo post.

### 5. Deletar Post
- Implemente um endpoint para deletar um post do banco de dados.
- Atualize a lista de posts localmente após deletar o post.

### 6. Detalhes do Post
- Implemente um endpoint para visualizar os detalhes de um post ao clicar em um item da lista.
- Mostre informações detalhadas do post, incluindo `id`, `title` e `body`, diretamente do banco de dados.

### 7. Arquitetura em Camadas
- Organize o código da aplicação em camadas: Presentation, Application, Domain, Infrastructure.
- Utilize boas práticas de programação e padrões de projeto (por exemplo, Repository Pattern, Dependency Injection).

### 8. Implementação de Validações e Boas Práticas
- Implemente validações adequadas para as entradas de dados (por exemplo, validação de campos obrigatórios, limites de comprimento).
- Siga princípios SOLID e outras boas práticas de engenharia de software.

## Funcionalidades Implementadas
- **Lista de Posts:** Exibe uma lista de posts obtida da API JSONPlaceholder e armazenada no banco de dados.
- **Adicionar Post:** Permite adicionar um novo post e salvá-lo no banco de dados.
- **Deletar Post:** Permite deletar um post selecionado do banco de dados.
- **Detalhes do Post:** Exibe detalhes de um post ao clicar em um item da lista, recuperando todas as informações do banco de dados.

## Capturas de Tela / Vídeo
Adicione aqui capturas de tela ou um vídeo curto demonstrando a funcionalidade da aplicação.

## Critérios de Avaliação
- Correção e completude das funcionalidades implementadas.
- Organização e clareza do código.
- Uso correto de padrões de projeto e boas práticas de programação.
- Documentação e clareza das instruções fornecidas.
- Uso de uma arquitetura em camadas.
- Implementação de validações adequadas.

## Instruções do Candidato
Explique claramente como instalar e rodar sua aplicação. Inclua todos os passos necessários, desde a clonagem do repositório até a execução final da aplicação. Certifique-se de que qualquer pessoa seguindo suas instruções consiga configurar e rodar a aplicação sem dificuldades.

---

**Nota:** Este projeto é apenas para fins de teste e aprendizado. A API JSONPlaceholder é uma ferramenta pública destinada a testes e não deve ser usada em produção.

---

✨ **Boa sorte!** ✨ Estamos ansiosos para ver sua criatividade e habilidades em ação. Lembre-se, este é um espaço para você brilhar e mostrar seu melhor trabalho. Divirta-se e boa codificação! 🚀
