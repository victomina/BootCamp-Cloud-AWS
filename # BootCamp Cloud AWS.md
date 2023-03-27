# BootCamp AWS Cloud
### Anotações importantes

- Listar os usuários de um grupo
    -- cat /etc/passwd

- sshd
    -- fazer acessor a arquivos de forma remota;
    -- ssh protocolo de acesso remoto;

- Identificando partições em um disco:
    -- comandos:
        --- lbslk      ==>irá mostrar os discos rígidos na máquina;
        --- f disc -l  ==>irá mostrar os discos e listar;
        --- mkfs.ext4  ==>irá criar uma partição com formato ext4

- Copiando arquivos
    - cp --help  ==> ajuda do copiar

- Servidores
    - systemctl restart smbd ==> reiniciar o sistema
    - systemctl status       ==> verificar o status
    - systemctl enabled      ==> para quando o sistema reiniciar , o sewrviço será executado automaticamente

## Servidor de Banco de Dados com Linux

- Hospedando um banco de dados

-  MySQL em um servidor:
    - buscando o mySQL server para um servidor Linux:
    `apt search mysql-server`
    - Instalando o servidor mysql
    `apt install mysql-server-8.0 -y`  