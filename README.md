# Curso digital: Git/versionamento

## Comandos básicos:

* O comando "git status" mostra situação atual do arquivo;
* O comando "git add" adiciona o arquivo na área de staged changes, ou seja, está pronto para dar um commit caso queira;
* O comando "git diff" mostra as mundaças feitas no aquivo;
* O comando "git commit -m "mesenge of changes" aceita as mudanças feitas no arquivo;
* O comando "git log" mostra o historico dos commit;
* O comando "git restore" remove uma alteração já salva na área de changes;
* O comando "git remote" mostra todos os nossos remotos
* O comando "git push origin 'branch' " posta as atualizações feitas no arquivo no seu repositório remoto;
* O comando "git fetch" permite ver as mundaças feitas no aquivo remoto antes de baixar para o seu diretório local, mas é preciso usar o comando abaixo em seguida;
* O comando "git diff origin/branch " mostra as mundaças feitas no aquivo remoto antes de baixar para o seu diretório local;
* O comando "git pull origin 'branch' " baixa as atualizações feitas no aquivo remoto para o seu diretório local.
* O comando "git branch 'name' " cria uma nova branch;
* O comando "git log --oneline --decorate" indica onde o nosso HEAD (seta que indica onde nosso branch está atualmente) está apontando atualmente;
* O comando "git checkout 'branch name' " muda para a branch que a gente quer ir;
* O comando "git merge 'branch name' " traz a branch que vc quer trazer para a branch atual