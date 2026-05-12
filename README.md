# Reserva de Voo RPA

Este projeto é uma automação desenvolvida em UiPath para simular o processo de reserva de voos e o armazenamento desses dados em um arquivo de texto.

## Funcionalidades

- Solicita ao usuário o destino do voo.
- Solicita ao usuário a data de partida.
- Solicita ao usuário a data de retorno.
- Armazena as informações coletadas em um Array de Strings.
- Registra os dados no arquivo local reservas.txt.
- Exibe uma confirmação de conclusão ao final do processo.

## Estrutura do Projeto

- `Main.xaml`: Fluxo principal contendo a lógica de entrada de dados, manipulação de array e escrita de arquivo.
- `project.json`: Arquivo de configuração com as dependências do projeto (UiPath.System, UIAutomation, Excel e Mail Activities).
- `reservas.txt`: Arquivo de saída onde os dados das reservas são salvos.

## Requisitos

- UiPath Studio 2025.10.8 ou superior.
- .NET Desktop Runtime compatível com o target framework Windows.

## Como usar

1. Abra o projeto no UiPath Studio através do arquivo `project.json`.
2. Execute o fluxo `Main.xaml`.
3. Responda às caixas de entrada de texto com as informações solicitadas.
4. Verifique o resultado no arquivo reservas.txt gerado no diretório do projeto.
