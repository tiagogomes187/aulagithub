# Aula Github - Nélio Alves

https://www.youtube.com/watch?v=HrMb2oZgujE&list=PLNuUvBZGBA8nDTr8QRMgoT_l3XNt_BbWj&index=4 

## Passos para configuração do git.

$ git init
$ git config --global user.name "Tiago Gomes"
$ git config --global user.email "tiagogomes187@gmail.com"
$ git --list
$ git config --list
$ git add .
$ git status
$ git commit -m "Criadas páginas index e vendas"
$ git log
$ git add .
$ git commit -m "Acrecentado valor das vendas"
$ echo "# aulagithub" >> README.md
$ git add README.md
$ git commit -m "Adcionei o README."
$ git branch -M main
$ git remote add origin https://github.com/tiagogomes187/aulagithub.git
$ git push -u origin main
$ git remote -v


## Gerar uma nova chave SSH
https://docs.github.com/pt/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent 

Abra Git Bash.

Cole o texto abaixo, substituindo o endereço de e-mail pelo seu GitHub.

$ ssh-keygen -t ed25519 -C "your_email@example.com"


Observação: Se você estiver usando um sistema legado que não é compatível com o algoritmo Ed25519, use:

$ ssh-keygen -t rsa -b 4096 -C "your_email@example.com"

O comando criará uma nova chave SSH, usando o e-mail fornecido como uma etiqueta.

> Generating public/private ed25519 key pair.

Quando aparecer a solicitação "Enter a file in which to save the key" (Insira um arquivo no qual salvar a chave), presssione Enter. O local padrão do arquivo será aceito.
> Enter a file in which to save the key (/c/Users/you/.ssh/id_ed25519):[Press enter]


Digite uma frase secreta segura no prompt. Para obter mais informações, consulte "Trabalhar com frases secretas da chave SSH".

> Enter passphrase (empty for no passphrase): [Type a passphrase]
> Enter same passphrase again: [Type passphrase again]





