# git aliases
git config --global --remove-section alias;
git config --global alias.s "status";
git config --global alias.aa "add .";
git config --global alias.j "checkout";
git config --global alias.jb "checkout -b";
git config --global alias.jj "switch -";
git config --global alias.b "branch";
git config --global alias.com "commit";
git config --global alias.comm "commit -m";
git config --global alias.coma "commit --amend";
git config --global alias.come "commit --allow-empty";
git config --global alias.l "log --graph --pretty=format:'%C(#f1a729)%h%C(reset) %s%n%C(cyan)%d%C(reset) %n%w(72,3,3)%C(#777)%cr - %cn %n'";
git config --global alias.la "log --all --graph --pretty=format:'%C(#f1a729)%h%C(reset) %s%n%C(cyan)%d%C(reset) %n%w(72,3,3)%C(#777)%cr - %cn %n'";
git config --global alias.lb "log --graph --pretty=format:'%C(#f1a729)%h%C(reset) %s%n%C(cyan)%d%C(reset) %n%w(72,3,3)%b%C(#777)%cr - %cn %n'";
git config --global alias.lab "log --all --graph --pretty=format:'%C(#f1a729)%h%C(reset) %s%n%C(cyan)%d%C(reset) %n%w(72,3,3)%b%C(#777)%cr - %cn %n'"