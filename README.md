# guiaLinux
 `Aluno : Daniel Bernardo Marques de Melo `

 `Matrícula : 01714611`
## Sumário

- [guiaLinux](#guialinux
  - [🧱 Básicos](#-básicos)
  - [🛜 Comandos de Rede](#-comandos-de-rede)
  - [Gerenciamento de Arquivos](#gerenciamento-de-arquivos)
  - [Permissões e Usuários](#permissões-e-usuários)
  - [Processos e Sistema](#processos-e-sistema)

---

## 🧱 Básicos

| Nº | Comando | Descrição | Exemplo |
|----|---------|-----------|---------|
| 1  | cd      | Muda o diretório atual | `cd /home/user` |
| 2  | ls      | Lista arquivos e diretórios | `ls -l` |
| 3  | cat     | Exibe conteúdo de arquivos | `cat arquivo.txt` |
| 4  | rm      | Remove arquivos/diretórios | `rm arquivo.txt` |
| 5  | mkdir   | Cria diretório | `mkdir novo_dir` |
| 6  | touch   | Cria arquivo vazio | `touch novo.txt` |
| 7  | grep    | Busca por padrões | `grep 'palavra' arquivo.txt` |
| 8  | sudo    | Executa como root | `sudo apt update` |
| 9  | history | Histórico de comandos | `history` |
| 10 | clear   | Limpa o terminal | `clear` |
| 11 | exit    | Sai do terminal | `exit` |
| 12 | rmdir   | Remove diretório vazio | `rmdir pasta` |
| 13 | cp      | Copia arquivos | `cp origem.txt destino.txt` |
| 14 | mv      | Move/renomeia arquivos | `mv velho.txt novo.txt` |
| 15 | find    | Busca arquivos | `find / -name arquivo.txt` |
| 16 | which   | Localiza executáveis | `which python` |
| 17 | locate  | Localiza arquivos | `locate arquivo.txt` |
| 18 | file    | Tipo de arquivo | `file imagem.png` |
| 19 | whereis | Localiza binários/manuais | `whereis gcc` |
| 20 | stat    | Info detalhada de arquivo | `stat arquivo.txt` |
| 21 | chmod   | Altera permissões | `chmod 755 script.sh` |
| 22 | chown   | Altera proprietário | `chown user arquivo.txt` |
| 23 | chgrp   | Altera grupo | `chgrp grupo arquivo.txt` |
| 24 | umask   | Permissão padrão | `umask 022` |
| 25 | ln      | Cria links | `ln -s origem destino` |

## 🛜 Comandos de Rede

| Nº | Comando | Descrição | Exemplo |
|----|---------|-----------|---------|
| 26 | ping    | Testa conexão | `ping google.com` |
| 27 | ifconfig| Exibe config de rede | `ifconfig` |
| 28 | ip      | Gerencia rede | `ip a` |
| 29 | netstat | Info de rede | `netstat -tuln` |
| 30 | ss      | Sockets ativos | `ss -tuln` |
| 31 | traceroute | Rota até destino | `traceroute google.com` |
| 32 | nslookup | Consulta DNS | `nslookup google.com` |
| 33 | dig     | Consulta DNS | `dig google.com` |
| 34 | curl    | Requisições HTTP | `curl https://site.com` |
| 35 | wget    | Baixa arquivos | `wget https://site.com/arquivo.zip` |
| 36 | scp     | Copia via SSH | `scp arquivo.txt user@host:/destino` |
| 37 | ssh     | Conecta via SSH | `ssh user@host` |
| 38 | ftp     | Conecta via FTP | `ftp ftp.site.com` |
| 39 | nmap    | Scanner de rede | `nmap 192.168.0.1` |
| 40 | arp     | Tabela ARP | `arp -a` |

## Gerenciamento de Arquivos

| Nº | Comando | Descrição | Exemplo |
|----|---------|-----------|---------|
| 41 | tar     | Compacta arquivos | `tar -czvf arquivo.tar.gz pasta/` |
| 42 | unzip   | Descompacta zip | `unzip arquivo.zip` |
| 43 | zip     | Compacta em zip | `zip arquivo.zip pasta/` |
| 44 | dd      | Copia blocos | `dd if=/dev/sda of=backup.img` |
| 45 | head    | Mostra início do arquivo | `head arquivo.txt` |
| 46 | tail    | Mostra final do arquivo | `tail arquivo.txt` |
| 47 | sort    | Ordena linhas | `sort arquivo.txt` |
| 48 | uniq    | Remove duplicatas | `uniq arquivo.txt` |
| 49 | wc      | Conta linhas/palavras | `wc -l arquivo.txt` |
| 50 | cut     | Corta colunas | `cut -d':' -f1 /etc/passwd` |
| 51 | paste   | Junta arquivos | `paste arq1 arq2` |
| 52 | diff    | Compara arquivos | `diff arq1 arq2` |
| 53 | sed     | Edita texto | `sed 's/velho/novo/g' arquivo.txt` |
| 54 | awk     | Processa texto | `awk '{print $1}' arquivo.txt` |

## Permissões e Usuários

| Nº | Comando | Descrição | Exemplo |
|----|---------|-----------|---------|
| 55 | passwd  | Altera senha | `passwd user` |
| 56 | useradd | Adiciona usuário | `useradd novo_user` |
| 57 | userdel | Remove usuário | `userdel user` |
| 58 | groupadd| Adiciona grupo | `groupadd grupo` |
| 59 | groups  | Lista grupos | `groups user` |
| 60 | su      | Troca de usuário | `su user` |

## Processos e Sistema

| Nº | Comando | Descrição | Exemplo |
|----|---------|-----------|---------|
| 61 | ps      | Lista processos | `ps aux` |
| 62 | top     | Monitor de processos | `top` |
| 63 | htop    | Monitor avançado | `htop` |
| 64 | kill    | Finaliza processo | `kill 1234` |
| 65 | pkill   | Finaliza por nome | `pkill firefox` |
| 66 | free    | Memória livre | `free -h` |
| 67 | df      | Espaço em disco | `df -h` |
| 68 | du      | Uso de disco | `du -sh pasta/` |
| 69 | uptime  | Tempo ligado | `uptime` |
| 70 | uname   | Info do sistema | `uname -a` |
| 71 | dmesg   | Mensagens do kernel | `dmesg` |
| 72 | journalctl | Logs do sistema | `journalctl` |
| 73 | reboot  | Reinicia sistema | `reboot` |
| 74 | shutdown| Desliga sistema | `shutdown now` |