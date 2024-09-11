pip install pip setuptools wheel --upgrade
pip install pytest
pip install django
# Verificar a instalação do django
django-admin --version


# baixar o git
git --version
git config --list
https://git-scm.com/download/win


git config --global user.name "cpm1163"
git config --global user.email "carlos.mahet@gmail.com"
git config --global init.defaultbranch main
# configurar o git no desktop


# criar a chave SSH
ssh-keygen

Your identification has been saved in C:\Users\carlo/.ssh/id_rsa

Your public key has been saved in C:\Users\carlo/.ssh/id_rsa.pub
cat C:\Users\carlo/.ssh/id_rsa.pub
copiar a chave
ir no setting do github
https://github.com/settings/keys
add SSH

# NO REPOSITORIO
# Quick setup — if you’ve done this kind of thing before
selecionar botão SSH e copiar o endereço
git@github.com:cpm1163/projeto1.git



git remote add origin git@github.com:cpm1163/projeto1.git

# ver se acatou o comando
git remote -v

# verificar se existe algo no git por fazer
git status 

# Dar o commit manual
git commit -m "o que esta no commit"
git push