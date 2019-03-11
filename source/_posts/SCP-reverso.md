---
title: SCP reverso
date: 2019-03-11 11:23:39
tags:
---
## Obtendo arquivo de um server remoto via scp

Um dia precisei baixar um arquivo de um dos meus servidores remoto e então eu pensei: "Será que é possível 
fazer um scp reverso?"

Dei um google e achei rs(não lembro onde, mas acho que foi no stackoverflow)

Se vc já faz upload via scp o processo é bem simples veja abaixo.

```
user@ip-server-remoto:/home/arquivo.backup /home/atila/

```
para configurar o scp veja [aqui](https://blogdoatila.wordpress.com/2018/02/23/login-sem-senha-com-sshusando-chaves-ssh/)