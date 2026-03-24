# Mapa Interativo CREAS 📍

Este projeto é um mapa interativo desenvolvido com **Leaflet** e **HTMLWidgets** para visualização e busca de áreas de abrangência/bairros do CREAS.

## 🚀 Funcionalidades

- **Busca Avançada**: Inclui uma barra de pesquisa no canto superior esquerdo para localizar bairros específicos no mapa.
- **Interatividade de Zoom**: 
  - **Duplo Clique no Mapa**: Reseta a visualização para a vista panorâmica inicial.
  - **Duplo Clique em Marcadores**: Aproxima o zoom (nível 18) diretamente no ponto selecionado.
- **Visualização Full-Screen**: O mapa ajusta-se automaticamente ao tamanho da janela do navegador.

## 🛠️ Tecnologias Utilizadas

- [Leaflet](https://leafletjs.com/) - Biblioteca JavaScript para mapas interativos.
- [HTMLWidgets](https://www.htmlwidgets.org/) - Framework para integração de bibliotecas JavaScript.
- [jQuery](https://jquery.com/) - Suporte para manipulação de DOM e eventos.

## 💻 Como Visualizar

1. Faça o download do arquivo `Mapa_CREAS.html`.
2. Abra o arquivo em qualquer navegador web moderno.

*Ou, se estiver visualizando via GitHub Pages:*
Acesse: `https://seu-usuario.github.io/seu-repositorio/Mapa_CREAS.html`

## 📖 Estrutura do Arquivo

O arquivo `Mapa_CREAS.html` é autossuficiente e contém:
- Estruturas de CSS para garantir o preenchimento total da tela.
- Dependências JavaScript embarcadas para funcionamento offline (após o carregamento inicial dos tiles do mapa).
- Lógica de busca customizada com mensagens de "Localização não encontrada" e suporte a auto-completar.

---
Desenvolvido para auxílio na gestão territorial do CREAS.
