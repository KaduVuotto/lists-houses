# Homes

## Descrição
"Homes" é um aplicativo Angular que lista casas para alugar e mostra os detalhes de cada casa. Este aplicativo utiliza recursos comuns a muitos aplicativos Angular. O projeto consiste em lições que apresentam os conceitos Angular necessários para começar a codificar em Angular.

## Instalação
Para instalar o Angular e configurar o projeto "Homes" em sua máquina, siga os passos abaixo:

1. **Instale o Node.js**:
   - Baixe e instale o Node.js a partir do [site oficial](https://nodejs.org/).

2. **Instale o Angular CLI**:
   - Após instalar o Node.js, execute o seguinte comando para instalar o Angular CLI globalmente:
     ```sh
     npm install -g @angular/cli
     ```

3. **Clone o Repositório**:
   - Clone este repositório em sua máquina local usando o comando:
     ```sh
     git clone https://github.com/KaduVuotto/homes.git
     cd homes
     ```

4. **Instale as Dependências**:
   - Navegue até o diretório do projeto e instale as dependências do Angular:
     ```sh
     npm install
     ```

5. **Instale o json-server**:
   - Para iniciar o servidor local, instale o `json-server` globalmente:
     ```sh
     npm install -g json-server
     ```

## Uso
Para usar este projeto, siga os passos abaixo:

1. **Inicie o Servidor json-server**:
   - Rode o comando abaixo para iniciar o servidor local:
     ```sh
     json-server --watch db.json
     ```

2. **Inicie o Servidor Angular**:
   - Rode o comando abaixo para iniciar o servidor de desenvolvimento do Angular:
     ```sh
     ng serve
     ```
   - Abra o navegador e acesse `http://localhost:4200/` para ver a aplicação em execução.

## Tecnologias Utilizadas
Este projeto foi construído com as seguintes tecnologias:

- [Angular](https://angular.io/) - Framework para construção de aplicações web.
- [TypeScript](https://www.typescriptlang.org/) - Superset do JavaScript que adiciona tipagem estática.
- [Angular CLI](https://cli.angular.io/) - Ferramenta de linha de comando para Angular.
- [json-server](https://github.com/typicode/json-server) - Fake REST API para desenvolvimento rápido.

## Funcionalidades Principais
- Listar casas para alugar.
- Mostrar os detalhes de casas individuais.

## Contribuição
Se você deseja contribuir para este projeto, siga os passos abaixo:

1. Faça um fork do projeto.
2. Crie uma branch para sua feature (`git checkout -b feature/nova-feature`).
3. Commit suas mudanças (`git commit -am 'Adiciona nova feature'`).
4. Faça push para a branch (`git push origin feature/nova-feature`).
5. Crie um novo Pull Request.

## Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

