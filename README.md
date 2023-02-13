# Sobre
Projeto ASP.NET Core MVC (Model-View-Controller) que consiste em uma aplicação onde o usuário pode realizar o upload de arquivos (enviando-os para a aplicação) e, posteriormente, sendo possível realizar o download. Tudo isso apenas com poucos cliques.

# Como utilizar
Não é preciso realizar algum tipo de configuração, apenas realize a compilação do projeto. Para realizar o upload de arquivos, o usuário pode selecionar manualmente e ao final clicar no botão "Upload" ou, simplesmente, arrastar e soltar um arquivo na área demarcada.

# Importante
Utilizei o pacote NuGet chamado de MimeTypeMapOffical para obter o "contentType" de arquivos enviados para a aplicação (upload). Isto é necessário para ser possível realizar o download do arquivo enviado, onde é preciso obter o seu contentType. Por exemplo: se o arquivo enviado for de extensão ".pdf", o seu contentType será "application/pdf" e assim por diante.

# Tecnologias utilizadas
- Ajax Jquery: utilizado para realizar o envio de arquivos para a aplicação (upload);
- Bootstrap;
- JavaScript;
