# linux_alias
Common aliases for linux

alias serverl='ssh -i ~/CHAVE.pem ubuntu@IP'
alias addar='git add -A'
alias pushar='git push origin develop'
alias pullar='git pull origin develop'
alias preparar='rake db:prepare'

comitar() {
    git commit -m "$1"
}
