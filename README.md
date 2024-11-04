-- Sistema de Comunicação Cliente-Servidor (TCP e UDP) --

Este projeto implementa um sistema de comunicação cliente-servidor em Python usando os protocolos TCP e UDP. Ele inclui servidores para ambos os protocolos e clientes que se conectam e enviam mensagens ao servidor conforme o protocolo escolhido.

-- Estrutura dos Arquivos --

- `servidor.py`: Servidor principal, que suporta conexões TCP e UDP simultaneamente.
- `servidor_tcp.py`: Servidor dedicado exclusivamente ao protocolo TCP.
- `servidor_udp.py`: Servidor dedicado exclusivamente ao protocolo UDP.
- `client.py`: Cliente que permite escolher entre TCP ou UDP para enviar uma mensagem ao servidor.
- `client_desafio.py`: Versão alternativa do cliente, permitindo envio contínuo de mensagens até o encerramento.

-- Pré-requisitos --

- Python 3.x instalado no sistema.
- Editor de texto ou IDE, como Visual Studio Code (VS Code), para visualizar e editar os scripts.

-- Instruções de Execução --

-- 1. Executar o Servidor --

-- Opção 1: Executar o Servidor Principal (TCP e UDP) --

1. Abra o terminal na pasta do projeto.
2. Execute o comando:
   ```bash
   python3 servidor.py
'''
