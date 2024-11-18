# **Collaboration entre Agentes: Pesquisador e Gerador de Gráficos**

## Descrição

Este projeto apresenta uma arquitetura de colaboração entre dois agentes distintos: um agente pesquisador, com acesso à internet, e um agente gerador de gráficos. A interação entre eles tem como objetivo solucionar entradas fornecidas pelo usuário de forma eficiente e visualmente informativa. 

Ao receber uma entrada, o agente pesquisador coleta informações relevantes através de pesquisas na internet, que são então analisadas e compartilhadas com o agente gerador de gráficos. Este, por sua vez, transforma os dados em visualizações gráficas apropriadas para entregar uma resposta estruturada ao usuário. Essa colaboração maximiza o potencial dos agentes, combinando a capacidade de pesquisa e coleta de informações em tempo real com a criação de outputs visuais claros e precisos.

## Base de Implementação

O projeto foi inspirado e desenvolvido com base no exemplo `Collaboration` disponível na documentação oficial do LangGraph. Ele demonstra como a interação sinérgica entre agentes especializados pode ser aplicada para resolver problemas complexos e fornecer soluções robustas e integradas.

## Arquitetura dos Agentes

- **Agente Pesquisador**: 
  - Realiza buscas na internet para coletar informações relevantes.
  - Analisa e estrutura os dados coletados para serem utilizados na próxima etapa.
- **Agente Gerador de Gráficos**: 
  - Recebe os dados do agente pesquisador.
  - Gera visualizações gráficas, como gráficos de barras, linhas ou outros formatos adequados, para apresentar os resultados.

Os agentes interagem de maneira contínua até que uma solução satisfatória seja encontrada para a entrada do usuário.

## Funcionalidades Principais

- **Colaboração Dinâmica**: Os agentes trabalham juntos para solucionar problemas de maneira colaborativa e eficiente.
- **Pesquisa em Tempo Real**: O agente pesquisador utiliza seu acesso à internet para buscar informações atualizadas.
- **Geração de Visualizações**: O agente gerador de gráficos transforma os dados em representações visuais claras e informativas.
- **Adaptabilidade**: A colaboração é ajustada conforme a entrada do usuário e os resultados parciais obtidos.

## Como Usar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu_usuario/agent-collaboration.git

2. Navegue até o diretório do projeto:
   ```bash
   cd agent-collaboration

3. Execute o notebook ou script fornecendo uma entrada que os agentes irão processar colaborativamente.

## Contribuindo

Contribuições são bem-vindas! Se você encontrar problemas ou tiver sugestões para melhorar o projeto, sinta-se à vontade para abrir uma issue ou enviar um pull request.
