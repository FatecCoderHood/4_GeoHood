# <p align = "center"> Coderhood - API 4º Semestre - BD 2025

<p align="center">
  <img src="https://github.com/user-attachments/assets/31805bfb-677f-4777-9824-651643cc0aac" width="400" height="400" />
</p>

<p align="center">
  <a href ="#mortar_board-integrantes"> Integrantes </a>  •
  <a href ="#dart-objetivo"> Objetivo </a>  •
  <a href="#page_facing_up-requisitos-funcionais"> Requisitos Funcionais </a> •
  <a href="#page_with_curl-requisitos-não-funcionais"> Requisitos Não Funcionais </a>
</p>
<p align="center">
  <a href ="#calendar-cronograma"> Cronograma </a>  •
  <a href="#date-product-backlog"> Product Backlog </a> •
  <a href="#bookmark-tecnologias-utilizadas"> Tecnologias Utilizadas </a>
</p>


## :mortar_board: Integrantes:

| **Nome**                   | **Função**            | **LinkedIn**                                                  |
|:----------------------:|:-----------------:|:----------------------------------------------------------:|
| Rafael Trevizoli       | Product Owner    | [![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?style=flat-square&logo=linkedin&labelColor=blue)](https://www.linkedin.com/in/rafael-trevizoli)|
| Juan Cursino           | Scrum Master      | [![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?style=flat-square&logo=linkedin&labelColor=blue)](http://www.linkedin.com/in/juan-cursino)|
| Gustavo Robert        | Desenvolvedor     | [![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?style=flat-square&logo=linkedin&labelColor=blue)](https://www.linkedin.com/in/alexandre-jonas-de-souza-fonseca-989920181)|
| Caique Almeida         | Desenvolvedor     | [![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?style=flat-square&logo=linkedin&labelColor=blue)](https://www.linkedin.com/in/caique-almeida-privado)|
| Cristiane Alvares      | Desenvolvedor     | [![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?style=flat-square&logo=linkedin&labelColor=blue)](https://www.linkedin.com/in/cristiane-alvares)|
| Jean César             | Desenvolvedor     | [![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?style=flat-square&logo=linkedin&labelColor=blue)](https://www.linkedin.com/in/jean-rodrigues-0569a0251)|
| Rodrigo Antonio          | Desenvolvedor     | [![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?style=flat-square&logo=linkedin&labelColor=blue)](https://www.linkedin.com/in/michel-momosemichel-momose-b78a04203)|
| Aline Ramos            | Desenvolvedor      | [![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?style=flat-square&logo=linkedin&labelColor=blue)](https://www.linkedin.com/in/aline-ramos-3186b130)|
| Rennerson Vasconcelos  | Desenvolvedor     | [![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?style=flat-square&logo=linkedin&labelColor=blue)](https://www.linkedin.com/in/rennerson-vasconcelos-afonso-136107169/)|


## :dart: Objetivo

Criar um sistema para cadastro, análise e visualização de áreas agrícolas, permitindo a gestão eficiente dessas áreas por meio de dashboards interativos e mapas. O sistema suportará diferentes tipos de usuários com permissões específicas e possibilitará o cadastro de geometrias via upload de arquivos `.geojson`. No futuro, poderá ser expandido com inteligência artificial e machine learning para aprimorar as análises e recomendações.

## :page_facing_up: Requisitos Funcionais

| **Descrição** | **Requisito** |
|-------- | :--------: |
| Cadastro de usuários (Administrador, Analista e Consultor) | 1 |
| Cadastro de áreas agrícolas | 2 |
| Upload de geometria via arquivo .geojson | 3 |
| Edição e aprovação de áreas pelo Analista | 4 |
| Dashboards interativos com filtros de dados | 5 |
| Exibição de áreas agrícolas no mapa | 6 |
| Ferramenta de desenho para edição de geometria | 7 |

## :page_with_curl: Requisitos Não Funcionais

| **Descrição** | **Requisito** |
|-------- | :--------: |
| Prever um grande volume de notícias armazenadas | 8 |
| Utilizar softwares livres | 9 |
| Java (linguagem de programação, frameworks e APIs) | 10 |
| Deverá ser uma aplicação web | 11 |
| O front-end deve ser desenvolvido de forma minimalista | 12 |
| Documentação: manual de usuário, diagrama entidade-relacionamento e instruções de instalação | 13 |


## :calendar: Cronograma

| Sprint  | Nome | Data inicio  | Data Fim | Status |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| --  | KickOff   | 24/02   | 28/02 | Ok |
|  1  | Sprint 1   | 10/03   | 30/03 |  |
|  2  | Sprint 2   | 07/04   | 27/04 |  |
|  3  | Sprint 3   | 05/05   | 25/05 |  |
|  4  | Feira de Soluções  | 29/05 |    | 



## :date: Product BackLog
<table>
    <thead>
        <tr>
            <th>ID</th>
            <th>User Stories</th>
            <th>Épico</th>
            <th>Sprint</th>
            <th>Prioridade</th>
            <th>Requisito do Parceiro</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>1</td>
            <td>Eu como administrador, quero cadastrar, editar e excluir usuários para gerenciar o acesso ao sistema.</td>
            <td>Cadastro de Usuários</td>
            <td>1</td>
            <td>Alta</td>
            <td>1</td>
        </tr>
        <tr>
            <td>2</td>
            <td>Eu como administrador, quero definir permissões para cada tipo de usuário, garantindo que apenas usuários autorizados acessem determinadas funcionalidades.</td>
            <td>Controle de Acesso</td>
            <td>1</td>
            <td>Alta</td>
            <td>3</td>
        </tr>
        <tr>
            <td>3</td>
            <td>Eu como administrador, quero visualizar métricas e estatísticas sobre o sistema para monitorar o desempenho dos usuários.</td>
            <td>Acesso aos Dashboards</td>
            <td>1</td>
            <td>Média</td>
            <td>4</td>
        </tr>
        <tr>
            <td>4</td>
            <td>Eu como consultor, quero cadastrar novas áreas no sistema, informando seus atributos, para manter o banco de dados atualizado.</td>
            <td>Cadastro de Áreas</td>
            <td>1</td>
            <td>Alta</td>
            <td>9</td>
        </tr>
        <tr>
            <td>5</td>
            <td>Eu como consultor, quero importar arquivos .geojson para cadastrar áreas georreferenciadas de maneira mais rápida.</td>
            <td>Upload de Arquivos GeoJSON</td>
            <td>1</td>
            <td>Alta</td>
            <td>11</td>
        </tr>
        <tr>
            <td>6</td>
            <td>Eu como analista, quero visualizar os talhões agrícolas no mapa para analisar sua distribuição e status.</td>
            <td>Visualização de Talhões</td>
            <td>2</td>
            <td>Alta</td>
            <td>5</td>
        </tr>
        <tr>
            <td>7</td>
            <td>Eu como analista, quero editar e ajustar os polígonos das áreas no mapa para corrigir possíveis imprecisões.</td>
            <td>Edição de Geometria</td>
            <td>2</td>
            <td>Alta</td>
            <td>6</td>
        </tr>
        <tr>
            <td>8</td>
            <td>Eu como analista, quero aprovar ou rejeitar áreas cadastradas no sistema para garantir que apenas dados validados sejam utilizados.</td>
            <td>Aprovação ou Rejeição de Áreas</td>
            <td>2</td>
            <td>Média</td>
            <td>7</td>
        </tr>
        <tr>
            <td>9</td>
            <td>Eu como analista, quero modificar os dados das áreas (cultura, produtividade, tipo de solo) para manter as informações atualizadas.</td>
            <td>Atualização de Informações da Área</td>
            <td>2</td>
            <td>Média</td>
            <td>8</td>
        </tr>
        <tr>
            <td>10</td>
            <td>Eu como consultor, quero visualizar gráficos e métricas sobre as áreas cadastradas para acompanhar a evolução da produtividade.</td>
            <td>Acesso a Dashboards</td>
            <td>3</td>
            <td>Média</td>
            <td>10</td>
        </tr>
    </tbody>
</table>



## :bookmark: Tecnologias Utilizadas
<h4 align="center">

![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJIDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![Vue.js](https://img.shields.io/badge/vuejs-%2335495e.svg?style=for-the-badge&logo=vuedotjs&logoColor=%234FC08D)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)
![Stack Overflow](https://img.shields.io/badge/-Stackoverflow-FE7A16?style=for-the-badge&logo=stack-overflow&logoColor=white)
![Discord](https://img.shields.io/badge/Discord-%235865F2.svg?style=for-the-badge&logo=discord&logoColor=white)
![Slack](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white)
