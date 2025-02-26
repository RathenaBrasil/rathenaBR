<img src="doc/logo.png" align="right" height="90" />

# rAthenaBR
![clang](https://img.shields.io/github/actions/workflow/status/rathena/rathena/build_servers_clang.yml?label=clang%20build&logo=llvm) ![cmake](https://img.shields.io/github/actions/workflow/status/rathena/rathena/build_servers_cmake.yml?label=cmake%20build&logo=cmake) ![gcc](https://img.shields.io/github/actions/workflow/status/rathena/rathena/build_servers_gcc.yml?label=gcc%20build&logo=gnu) ![ms](https://img.shields.io/github/actions/workflow/status/rathena/rathena/build_servers_msbuild.yml?label=ms%20build&logo=visualstudio) ![GitHub](https://img.shields.io/github/license/rathena/rathena.svg) ![commit activity](https://img.shields.io/github/commit-activity/w/rathena/rathena) ![GitHub repo size](https://img.shields.io/github/repo-size/rathena/rathena.svg)
> rAthena é um projeto colaborativo de desenvolvimento de software que gira em torno da criação de um pacote de servidor robusto de jogo de RPG online multijogador massivo (MMORPG). Escrito em C++, o programa é muito versátil e oferece NPCs, warps e modificações. O projeto é gerenciado conjuntamente por um grupo de voluntários localizados em todo o mundo, bem como por uma enorme comunidade que fornece controle de qualidade e suporte. rAthena é uma continuação do projeto eAthena.

[Forum Oficial](https://rathena.org/board)|[Discord](https://rathena.org/discord)|[Wiki](#)|[Crowdfunding](#)|

### Índice
1. [Prerequisites](#1-prerequisites)
2. [Installation](#2-installation)
3. [Troubleshooting](#3-troubleshooting)
4. [More Documentation](#4-more-documentation)
5. [How to Contribute](#5-how-to-contribute)
6. [License](#6-license)

## 1. Pré-requisitos
Antes de instalar o rAthena, há certas ferramentas e aplicativos necessários, que variam de acordo com o sistema operacional utilizado.

### Hardware
Tipo de Hardware | Recomendado
------|------
CPU | 2 Cores
RAM | 2 GB
Disk Space | 500 MB

### Sistema Operacional e Compilador Preferido
Sistema Operacional | Compilador
------|------
Linux  | [gcc-9 or newer](https://www.gnu.org/software/gcc/gcc-6/) / [Make](https://www.gnu.org/software/make/)
Windows | [MS Visual Studio 2022 or newer](https://www.visualstudio.com/downloads/)

### Required Applications
Application | Name
------|------
Database | [MariaDB 1.6 or newer](https://downloads.mariadb.org/)
Git | [Windows](https://gitforwindows.org/) / [Linux](https://git-scm.com/download/linux)

### Optional Applications
Application | Name
------|------
Database | [MySQL Workbench 5 or newer](http://www.mysql.com/downloads/workbench/)

## 2. Installation 

### Full Installation Instructions
  * [Windows](#)
  * [AlmaLinux8](#)
  * [Ubuntu22](#)

## 3. Solução de problemas

Se você estiver tendo problemas para iniciar seu servidor, a primeira coisa que deve fazer é verificar 
o que está acontecendo nos consoles. Na maioria dos casos, os problemas podem ser resolvidos simplesmente 
analisando as mensagens de erro exibidas. Consulte a [wiki](#)
ou [Discord](#) se precisar de mais suporte para a resolução de problemas.

## 4. Mais documentação
O rAthena possui uma vasta coleção de arquivos de ajuda e scripts de NPC de exemplo localizados 
no diretório /doc/. Esses arquivos incluem explicações detalhadas sobre comandos de script para NPCs, 
comandos administrativos (@), permissões de grupo, bônus de itens e estruturas de pacotes, entre muitos 
outros tópicos. Recomendamos que todos os usuários dediquem um tempo para revisar esse diretório 
antes de buscar assistência em outros lugares.

## 5. Licença
Copyright (c) Equipe de Desenvolvimento rAthena - 
Licenciado sob [GNU General Public License v3.0](https://github.com/rathena/rathena/blob/master/LICENSE)
