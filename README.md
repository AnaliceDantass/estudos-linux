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

# Explorando a Hierarquia de Diretórios

No Linux, o conceito de unidades, como visto no Windows (Ex. C:, D:, etc.), não se aplica. Em vez disso, há um diretório raiz (“/”), do qual se ramificam vários subdiretórios, que descrevemos abaixo:

- **/bin:** O diretório bin armazena executáveis de comandos básicos do sistema (su, tar, cat, rm, pwd, etc).
- **/boot:** Arquivos para inicialização do sistema.
- **/dev:** Arquivos para dispositivos. Contém os dispositivos (links para dispositivos do sistema, como CD, HD, disquetes, etc).
- **lib:** Bibliotecas para o sistema. Contém as bibliotecas (similar às DLLs do Windows) usadas pelos programas. Existem dois tipos de bibliotecas: as usadas por um único programa (extensão .a) e as compartilhadas por vários programas (extensão .so).
- **/mnt e /media:** Pontos de montagem de dispositivos. É o subdiretório utilizado como ponto de montagem para dispositivos externos.
- **/proc:** Informações sobre o Kernel e processos.
- **/sbin:** Ferramentas de administração do sistema.
- **/tmp:** Arquivos temporários.
- **/usr:** Conteúdo para usuários.É onde se encontra a maior parte dos programas instalados. O subdiretório /usr/bin é o mais povoado (com cerca de 2000 programas). Se você está em busca de um programa, esse subdiretório é um bom ponto de partida.
- **/var:** Dados variáveis do sistema.

# Listando arquivos e diretórios 

- **ls -l:** Fornece uma listagem no formato "longo". Você verá detalhes adicionais como permissões de arquivo, proprietário, tamanho e data de modificação.

## ls
Para ver o conteúdo do seu diretório atual, use **ls**. Isso vai listar os arquivos e diretórios no seu diretório de trabalho atual. 

## ls ~
Este comando lista o conteúdo do seu diretório home, que pode ser diferente do seu diretório atual. 

Entender a distinção entre seu diretório de trabalho atual e seu diretório doméstico é importante para navegar efizcamente pelo sistema de arquivos Linux. 

