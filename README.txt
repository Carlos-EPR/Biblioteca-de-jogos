# Aplicação Flask de Login e Cadastro de Jogos

Esta é uma aplicação desenvolvida com o framework Flask que permite aos usuários realizar login, cadastrar novos jogos e visualizar uma lista de jogos cadastrados.

## Estrutura do Projeto

- `app.py`: Contém o código principal da aplicação, incluindo as rotas, a definição das classes `Jogo` e `Usuario`, e a lógica de autenticação de usuários.
- `lista.html`: Template para exibir a lista de jogos cadastrados.
- `novo.html`: Template para cadastrar um novo jogo.
- `login.html`: Template para realizar o login.

## Funcionalidades

### 1. Visualização da Lista de Jogos
   - A página inicial exibe uma lista de jogos cadastrados, mostrando o nome, categoria e console de cada jogo.
   - Os jogos são exibidos a partir de uma lista pré-definida no código.

### 2. Cadastro de Novos Jogos
   - Os usuários podem acessar a página de cadastro de novos jogos através da rota `/novo`.
   - Podem inserir informações como nome, categoria e console do jogo e salvá-las na lista de jogos.

### 3. Login de Usuários
   - A aplicação permite o login de usuários registrados.
   - Os usuários podem acessar áreas restritas da aplicação, como a página de cadastro de jogos, após o login.
   - A autenticação é feita comparando o nome de usuário (nickname) e senha fornecidos com os registros armazenados.

### 4. Autenticação e Logout
   - Após o login bem-sucedido, o usuário é redirecionado para a página anteriormente solicitada.
   - O logout é realizado ao acessar a rota `/logout`, encerrando a sessão do usuário.

## Utilização

### Execução da Aplicação
1. Execute o arquivo `app.py` para iniciar o servidor Flask.
2. Acesse a aplicação em um navegador web através do endereço `http://localhost:5000/`.

## Pré-requisitos
- Python 3.x instalado no sistema.
- Instalação do framework Flask.

## Execução
1. Abra um terminal.
2. Navegue até o diretório onde os arquivos do projeto estão localizados.
3. Execute o seguinte comando para iniciar o servidor Flask:
   ```
   python app.py
   ```

## Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para abrir um problema ou enviar um pull request para sugerir melhorias ou correções.

## Autores
Carlos Eduardo Peres Rocha

## Licença
Este projeto está licenciado sob a [Licença MIT](https://opensource.org/licenses/MIT).