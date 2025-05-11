# Мои команды

<!-- 
Идеи для git

git status => git s

лог граф только хедеров коммита
лог граф хедера и тела коммита
^
тоже самое но для всех веток или только одной

пофиксить первую строчку боди коммита


 -->

## Быстрая настройка
git config --global --remove-section alias;
git config --global alias.s "status";
git config --global alias.aa "add .";
git config --global alias.j "checkout";
git config --global alias.br "branch";
git config --global alias.com "commit";
git config --global alias.coma "commit --amend";
git config --global alias.come "commit --allow-empty";
git config --global alias.l "log --graph --pretty=format:'%C(#f1a729)%h%C(reset) %s%C(cyan)%d %n %C(dim)%b %n %C(dim)%cr - %cn %n'";
git config --global alias.la "log --all --graph --pretty=format:'%C(#f1a729)%h%C(reset) %s%C(cyan)%d %n %C(dim)%b %n %C(dim)%cr - %cn %n'";
git config --global alias.lb ""
git config --global alias.lba ""

git config --global alias.refhis "log --reflog --graph --pretty=format:'%C(#f1a729)%h%C(reset) %s%C(cyan)%d %n %C(dim)%b %n %C(dim)%cr - %cn %n'"
