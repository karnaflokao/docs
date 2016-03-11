Instalando Skype no Fedora 23


Para instalarmos o Skype no Fedora 23, primeiramente devemos adicionar o repositório "negativo17.org" à nossa lista de sources.

Para adicionar o repositório abra o terminal como root e insira o comando:

# dnf config-manager --add-repo=http://negativo17.org/repos/fedora-skype.repo

Para instalar o Skype insira o comando:

# dnf -y install skype

Pronto! Seu Skype está instalado 
