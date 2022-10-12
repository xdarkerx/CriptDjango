# CriptDjango

Projeto feito para tarefa de pesquisas de Criptografias. Front feito com Framework de Bootstrap e Back rodando com Django.

## Rodar Projeto

Abra o cmd e execute Python3, caso não tiver isntalado, procure pela ultima versão na Microsoft Store.

Para rodar o projeto usando Django:

Vá até o caminho do projeto e execute

```bash
python3 -m venv env
```

Depois rode o ambiente virtualizado (Windows):

```bash
cd env

cd Scripts

activate.bat

cd ../..
```
Após isso execute o comando para instalar as dependências na máquina.

```bash
pip3 install -r requirements.txt
```

Para rodar o projeto:

```bash
python3 manage.py runserver
```

Caso ocorra alguma mensagem de erro execute:

```bash
pip3 uninstall django
pip3 install django
python3 manage.py migrate
```

pip3 uninstall django

## License
[MIT](https://choosealicense.com/licenses/mit/)
