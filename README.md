# O que é o Linux? 
O Linux é um sistema operacional gratuito e de código aberto que oferece uma vasta segurança, flexibilidade e liberdade ao usuário. Ele é amplamente usado por profissionais de TI para gerenciar os diferentes tipos de sistemas em computadores, servidores, celulares, dentre outros dispositivos. 

## Kernel:
O kernel (núcleo) é um programa de computador que conecta hardware e software, permitindo que os usuários gerenciem diferentes componentes do sistema, incluindo redes, sistemas de arquivos, motivadores e muito mais.

Além do kernel, o Linux utiliza diversos componentes, como bibliotecas do sistema e utilitários de espaço, mas todos dependem do kernel para se comunicar e receber comandos do usuário. 

# Comandos básicos

## whoami:
Caso você esteja num computador que tem como sistema operacional o Linux, e quiser saber qual usuário está atualmente autenticado na sessão, digite **whoami**. 

No linux, os usuários são armazenados em grupos. Esses grupos determinam permissões e direitos de acesso que um usuário possui. 

## id
Ao rodar o comando **id**, você terá acesso à informações relacionadas ao usuário que está atualmente autenticado na sessão. 

- **uid:** ID de usuário;
- **gid:** ID principal do grupo;
- **groups:** todos os grupos do usuário.

## id -un
Apresenta o seu nome de usuário e também é responsável por exibir o usuário atual.

## pwd 
**pwd** significa "print working directory". Ele mostra sua localização atual no sistema de arquivos. Esse comando é crucial para se orientar na estrutura de arquivos do Linux. 

## ls
Para ver o conteúdo do seu diretório atual, use **ls**. Isso vai listar os arquivos e diretórios no seu diretório de trabalho atual. 

## ls ~
Este comando lista o conteúdo do seu diretório home, que pode ser diferente do seu diretório atual. 

Entender a distinção entre seu diretório de trabalho atual e seu diretório doméstico é importante para navegar efizcamente pelo sistema de arquivos Linux. 

# Navegando pelo Sistema de Arquivos
O Linux usa o que chamamos de "sistema de arquivos hierárquico". Pense nisso como uma grande árvore com galhos. O tronco principal é chamado de "diretório raiz", representado por única barra transversal. Todos os outros diretórios e arquivos se ramificam a partir dessa raiz. 
