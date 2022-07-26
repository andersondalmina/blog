---
title: "Script para setup do meu ambiente no Ubuntu"
date: 2022-07-12T18:00:00-03:00
author: "Ânderson Dalmina"
---

Recentemente, durante a escrita do meu TCC, tive problema ao atualiza o sistema operacional (Ubuntu) da minha máquina. Alguns pacotes foram corrompidos e a máquina não iniciava mais.
Precisei formatar a máquina e reinstalar o sistema. Contudo, todos meus programas e configurações foram removidos, sendo necessário instalar e configurar tudo novamente. Esse processo consumiu 1 dia do meu final semana, 1 dia precioso para a escrita do meu TCC.

Pensando nisso, decidi implementar alguns scripts para automatizar a instalação dos programas que mais utilizo e configurações de preferências pessoais. Levantei algumas funcionalidades que esse conjunto de scripts deveria implementar:

- Atualizar os pacotes do sistema, já que uma nova instalação sistema não contém a última versão de muitas dependências.
- Instalar alguns programas essenciais para meu dia a dia como: VSCode, Brave Browser, Spotify ...
- Instalar as linguagem de programação que utilizo: Nodejs, Golang, PHP e Python.
- Configurar visualmente o sistema com minhas preferências
  - Alterar papel de parede.
  - Alterar posição e exibição do dock.
  - Utilizar tema escuro.

Dessa forma, estou trabalhando em um Makefile com os scripts necessários para cada uma das funcionalidades.

Os scripts podem ser encontrados em: https://github.com/andersondalmina/ubuntu-setup
