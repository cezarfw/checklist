# Checklist-desafio

Checklist-desafio são instruções escritas em ansible e que servem para provisionar o ambiente solicitado por e-mail, incluindo ldap, cms, etc..

## Pré-Requisitos

1) Ubuntu 18.04 Bionic
2) Ansible >= 2.8
3) Python >= 3

```bash
sudo apt update
sudo apt install software-properties-common
sudo apt-add-repository ppa:ansible/ansible
sudo apt update
sudo apt install ansible
```

## Modo de uso

1) cd /opt
2) git clone https://github.com/cezarfw/checklist.git
3) cd checklist
4) Alterar o IP do servidor alvo no arquivo hosts ou passar como parâmetro.
5) Executar o comando abaixo:

```bash
ansible-playbook desafio.yml
```

Esse projeto foi construido sem uma base de testes e não está finalizado, isto é, não é recomendado em qualquer ambiente, incluindo de desenvolvimento.

## Autor
[Cezar Augusto Roggia](https://www.linkedin.com/in/cezar-augusto-roggia/)
