📅 Dashboard de Aderência ao Calendário Promocional

  Este projeto é um dashboard interativo desenvolvido para acompanhar a aderência das marcas de cerveja ao calendário promocional da Ambev.

➡️ Acesse a versão ao vivo: http://aderenciacalendario.online/

🎯 Sobre o Projeto

O sistema foi criado com o objetivo de fornecer uma visualização clara e em tempo real da performance promocional das marcas.

A principal característica deste projeto é que ele não necessita de um backend tradicional. Ele consome dados diretamente de uma planilha do Google Sheets publicada publicamente como um arquivo CSV. Isso permite que qualquer pessoa com acesso à planilha possa atualizar os dados do dashboard automaticamente, apenas editando a planilha.

✨ Funcionalidades Principais

  Dashboard Interativo: Uma interface moderna (dark mode) com visuais 3D (Globo) para apresentação dos dados.

  Consumo de Google Sheets: Os dados são lidos diretamente de um Google Sheet publicado como CSV.

  Atualização Automática: As informações no site são atualizadas assim que a planilha é modificada (pode haver um pequeno delay de cache).

  Sem Backend: A lógica de leitura e exibição dos dados é feita 100% no front-end (client-side).
  
  Responsivo: Funciona em desktops, tablets e celulares.

🛠️ Tecnologias Utilizadas

  Este projeto foi construído utilizando as seguintes tecnologias:

  HTML5: Estrutura semântica da página.

  Tailwind CSS: Framework CSS para estilização rápida e responsiva.

  JavaScript (ES6+): Para a lógica de negócios, interatividade e o globo 3D.

  Three.js: Biblioteca 3D para a criação do globo interativo.

  GitHub Pages: Para hospedagem gratuita do site.

🖼️ Screenshot

<img width="1182" height="811" alt="image" src="https://github.com/user-attachments/assets/1ae84805-48b3-4662-8ade-55d99d2bae46" />


🚀 Como Funciona a Atualização de Dados

  Google Sheets: Crie uma planilha no Google Sheets com os dados.

  Publicar na Web: Vá em Arquivo > Compartilhar > Publicar na Web.

  Formato CSV: Escolha publicar a aba desejada como "Valores separados por vírgula (.csv)".

  Link: Pegue o link gerado e insira no código JavaScript do projeto (na função fetch ou similar).
  
  Pronto! O JavaScript irá buscar esse CSV e popular o dashboard.
