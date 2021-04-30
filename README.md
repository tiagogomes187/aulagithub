# Aula Github - Nélio Alves

https://www.youtube.com/watch?v=HrMb2oZgujE&list=PLNuUvBZGBA8nDTr8QRMgoT_l3XNt_BbWj&index=4 

## Passos para configuração do git.
<p>
$ git init <br/>
$ git config --global user.name "Tiago Gomes"<br/>
$ git config --global user.email "tiagogomes187@gmail.com"<br/>
$ git --list<br/>
$ git config --list<br/>
$ git add .<br/>
$ git status<br/>
$ git commit -m "Criadas páginas index e vendas"<br/>
$ git log<br/>
$ git add .<br/>
$ git commit -m "Acrecentado valor das vendas"<br/>
$ echo "# aulagithub" >> README.md<br/>
$ git add README.md<br/>
$ git commit -m "Adcionei o README."<br/>
$ git branch -M main<br/>
$ git remote add origin https://github.com/tiagogomes187/aulagithub.git<br/>
$ git push -u origin main<br/>
$ git remote -v<br/>
</p>


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