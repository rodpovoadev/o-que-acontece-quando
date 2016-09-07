O que acontece quando...
=============================

Este repositório é uma tentativa para responder uma velha questão de entrevista: O que acontece quando você escreve www.google.com.br no seu browser e pressiona a tecla enter?

Deixando de lado as respostas prontas para essa pergunta, vamois tentar responder com o maior detalhe possível, sem deixar nada de fora.

Este é um processo colaborativo, por isso você pode colaborar também. Há muitos detalhes que vão faltar, espero que você nos ajude com eles. Assim, envie seu pull request para nós, por favor.

Tudo está licenciado pelo termos de licença Creative Commons Zero

Leia este mesmo artigo em 简体中文 (Chines Simplificado )


Conteúdo
==============================

* A tecla "g" é pressionada
* A tecla "enter" é pressionada
* Interrupt fires ( EXCETO para teclados USB)
* (Windows) Uma mensagem ``WM_KEYDOWN`` é enviada para um app
* (No OS X)Uma ``KeyDown`` NSEvent é enviado para o app
* ( No GNU/Linux) O Servidor Xorg escuta os códigos chave
* Parse de URL
* É uma URL ou um termo de pesquisa
* Lista de verificação HSTS
* Converter carateres não-ASCII no nome do host
* Pesquisa de DNS
* Processo de ARP
* Abertura de um Socket
* Conexão TLS
* Protocolo HTTP
* Solicitação HTTP ao servidor
* Nos bastidores de um navegador
* Navegadores
* Parse HTML
* Interpretação de um CSS
* Renderização de uma página
* renderização GPU
* Windows Server
* Pós renderização e execução de um usuário

A tecla "g" é pressionada
==========================


