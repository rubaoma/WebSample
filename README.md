# WebSample

Este é um exemplo simples de um projeto web com navegação entre páginas HTML.

## Estrutura do Projeto

- `index.html`: Página inicial do projeto.
- `page2.html`: Segunda página com navegação para a terceira página.
- `page3.html`: Terceira página com botão para voltar.

## Como Executar

Para executar este projeto, você pode usar um servidor HTTP simples fornecido pelo Python. Siga os passos abaixo:

1. Certifique-se de que você tem o Python instalado em sua máquina. Você pode verificar isso executando o comando:

   ```sh
   python --version
   ```

   ou

   ```sh
   python3 --version
   ```

2. Navegue até o diretório do projeto no terminal:

   ```sh
   cd /Users/rubensmouraaugusto/Documents/android\ Study/POC\ Web\ View\ compose/web
   ```

3. Inicie um servidor HTTP com Python:

   - Para Python 3:

     ```sh
     python3 -m http.server
     ```

   - Para Python 2:

     ```sh
     python -m SimpleHTTPServer
     ```

4. O servidor será iniciado e estará disponível no endereço:

   ```
   http://localhost:8000
   ```

5. Abra o navegador e acesse o endereço acima para visualizar o projeto.

## Observação

Certifique-se de que todas as páginas HTML estão no mesmo diretório para que os links funcionem corretamente.