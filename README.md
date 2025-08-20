# Challenge-conversor-de-moedas
O Conversor de Moedas é uma aplicação em console que permite realizar conversões entre diferentes moedas de forma simples e prática. As taxas são obtidas em tempo real pela Exchange Rate API, garantindo precisão. Conta ainda com histórico e logs das conversões, oferecendo maior controle e transparência ao usuário.
Requisitos do Projeto

No decorrer do curso, desenvolvi um Conversor de Moedas em Java, um exercício que me permitiu explorar desde a configuração de ambiente até a integração com serviços externos. A proposta foi criar um programa interativo, executado no console, capaz de converter valores entre diferentes moedas utilizando informações atualizadas a partir de uma API de câmbio.

Etapas do Desenvolvimento

1. Preparação do Ambiente
Configurei o JDK, utilizei a biblioteca Gson para lidar com dados em JSON e adotei o IntelliJ IDEA como IDE principal. O Postman foi um recurso essencial para inspecionar as respostas da API e validar requisições antes de implementá-las no código.

2. Comunicação com a API
A conexão com a Exchange Rate API foi implementada através da classe HttpClient, o que tornou simples enviar solicitações e receber respostas. Já a classe HttpRequest possibilitou personalizar os parâmetros das requisições, garantindo flexibilidade no consumo dos dados.

3. Tratamento das Respostas
As respostas retornadas em formato JSON foram processadas por meio da Gson, permitindo transformar os dados em objetos Java e tornando-os acessíveis para uso no sistema. A partir disso, filtrei apenas as moedas relevantes para os usuários, o que deixou o programa mais útil e objetivo.

4. Lógica de Conversão
Implementei funções específicas para o cálculo da conversão entre moedas, deixando o código modular, legível e de fácil manutenção. Essa etapa representou o núcleo da aplicação, responsável por gerar os valores finais a partir das taxas recebidas.

5. Interatividade com o Usuário
A interface textual do console foi projetada para exibir menus e opções de escolha. Além de algumas conversões pré-definidas, o sistema também permitiu que o usuário digitasse as moedas desejadas, oferecendo maior liberdade e personalização.

Estrutura do Sistema

Classe Principal: Gerencia o menu e direciona o usuário para os próximos passos da conversão.

Classe Conversor: Executa a lógica de conversão, utilizando as taxas obtidas pela API.

Classe DigitarMoeda: Recebe a entrada do usuário via console e realiza a chamada para os métodos de conversão.

Conclusão

O desenvolvimento do Conversor de Moedas foi um desafio que uniu teoria e prática de maneira significativa. Trabalhar com APIs e dados em tempo real ampliou minha visão sobre a importância da integração entre sistemas e sobre a necessidade de escrever código limpo, organizado e modular.

O resultado foi um aplicativo funcional, capaz de oferecer múltiplas opções de conversão de moedas e de permitir inserções manuais. Mais do que o programa em si, o aprendizado adquirido com esse projeto fortaleceu minha base em Java, integração de serviços externos, manipulação de JSON e boas práticas de programação.
