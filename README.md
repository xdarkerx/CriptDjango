# CriptDjango

Projeto feito para tarefa de pesquisas de Criptografias. Front feito com Framework de Bootstrap e Back rodando com Django.

## Rodar Projeto

Abra o cmd e execute Python3, caso não tiver instalado, procure pela ultima versão na Microsoft Store.
Use o comando abaixo para atualizar o PIP:

```bash
pip install --upgrade pip
´´´

Após tudo instalado e atualizado, rode o comando dentro do caminho do projeto para criação do ambiente virtualizado.

```bash
python3 -m venv env
```

Depois rode os seguintes comandos para ativar o ambiente (Windows):

```bash
cd env

cd Scripts

activate.bat

cd ../..
```

Instale as dependências na máquina:

```bash
pip3 install -r requirements.txt
```

Para rodar o Localhost e acessar a plataforma via http:

```bash
python3 manage.py runserver
```

Caso ocorra alguma mensagem de erro após a execução do comando acima, remova as dependencias do Django, instale novamente e realise uma migração das variaveis:

```bash
pip3 uninstall django
pip3 install django
python3 manage.py migrate
```

pip3 uninstall django

## License
[MIT](https://choosealicense.com/licenses/mit/)
