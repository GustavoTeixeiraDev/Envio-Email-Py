# Envio-Email-py App

Uma aplicação simples de envio de e-mails usando Tkinter e smtplib.

## Descrição

Este projeto consiste em uma interface gráfica básica construída com Tkinter para enviar e-mails usando o módulo smtplib do Python. A aplicação permite ao usuário inserir as informações necessárias, como endereço do remetente, senha, endereço do destinatário e corpo do e-mail, e enviar a mensagem através do servidor SMTP do Gmail.

## Funcionalidades

- **Interface Gráfica Amigável:** Desenvolvida com Tkinter para uma experiência do usuário intuitiva.
- **Autenticação Segura:** Utiliza o protocolo TLS para autenticação segura no servidor SMTP.
- **Feedback ao Usuário:** Fornece mensagens de feedback na interface sobre o status do login e do envio de e-mails.
- **Limpeza de Campos:** Após o envio bem-sucedido, os campos são limpos para uma nova entrada.

## Pré-requisitos

Certifique-se de ter o Python instalado em seu sistema.

## Instalação

1. Clone o repositório:

    ```bash
    git clone https://github.com/seu-usuario/email-sender-app.git
    ```

2. Navegue até o diretório do projeto:

    ```bash
    cd email-sender-app
    ```

3. Instale as dependências:

    ```bash
    # Certifique-se de ter um ambiente virtual ativado, se estiver usando um.
    pip install -r requirements.txt
    ```

## Executando a Aplicação

1. Execute o script Python:

    ```bash
    python main.py
    ```

    (ou `python3 main.py` se estiver usando Python 3)

2. A interface gráfica será aberta. Preencha os campos necessários e clique no botão "Send Message".

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir problemas e enviar solicitações de pull.


**Nota:** Certifique-se de proteger suas credenciais e respeitar as políticas de segurança ao usar este aplicativo para enviar e-mails.
