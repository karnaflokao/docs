# .bashrc

# Source global definitions
if [ -f /etc/bashrc ]; then
	. /etc/bashrc
fi

# Uncomment the following line if you don't like systemctl's auto-paging feature:
# export SYSTEMD_PAGER=

# User specific aliases and functions


if [ -f ~/.bash_profile ]; then
	source ~/.bash_profile
fi

alias pa-homol="ssh -l root 187.191.98.54"
alias pa-sp="ssh -l soliveira 177.70.100.5"
alias pa-r1="ssh -l sergio parj01.mandic.net.br"
alias pa-r2="ssh -l sergio parj02.mandic.net.br"
alias kratos-cli="/home/sergio/workspace/kratosCli/kratos-cli.py"
alias kratos-test="/home/sergio/workspace/kratosCli/kratos-test.py"

# .bash_profile

parse_git_branch() {
git branch 2> /dev/null | sed -e '/^[^*]/d' -e 's/* \(.*\)/ (\1)/'
}

# Bash colorido
Normal="\[\\033[0m\]"
Vermelho="\[\\033[1;31m\]"
Verde="\[\\033[1;32m\]"
Amarelo="\[\\033[1;33m\]"
Azul="\[\\033[1;34m\]"
Roxo="\[\\033[1;35m\]"
Ciano="\[\\033[1;36m\]"
Branco="\[\\033[1;37m\]"
export PS1="$Normal$Azul[$Branco(\t) $Verde\u$Vermelho@$Amarelo\h$Verde $Ciano\w$Azul$Vermelho\$(parse_git_branch)$Azul]$Branco\\$ $Normal"
