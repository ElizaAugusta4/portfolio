# portfolio
Repositório criado para demonstrar meu Portfólio com meus projetos e conhecimentos profissionais durante minha carreira.

## Estrutura do Projeto
- **components/**: Contém as seções do portfólio em arquivos HTML.
- **css/**: Contém os estilos CSS utilizados no portfólio.
- **img/**: Contém as imagens utilizadas no portfólio.
- **Dockerfile**: Define a imagem Docker para o projeto.
- **nginx.conf**: Configuração do Nginx para servir o portfólio.
- **index.html**: Ponto de entrada do site do portfólio.
- **.github/workflows/docker.yml**: Configuração do GitHub Actions para automação de build e push da imagem Docker

## Como Executar
1. Clone o repositório.
2. Navegue até o diretório do projeto.
3. Construa a imagem Docker:
   ```
   docker build -t meu-portfolio .
   ```
4. Execute o contêiner:
   ```
   docker run -p 80:80 meu-portfolio
   ```
5. Acesse o portfólio em `http://localhost`.

## Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir um issue ou pull request.
