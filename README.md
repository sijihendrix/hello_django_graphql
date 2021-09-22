# Django api with Graphql endpoint

### Run to reproduce:

- Clone the project

```bash
 git clone
cd ecommerce/
```

- Set up the virtual env

```bash
pip install virtualenv
virtualenv env
source env/bin/activate

```

- Install django

```bash
pip install django

```

- Run migrations of the models to DB

```bash
python manage.py makemigrations
python manage.py migrate

```

- Run the api and use http://120.0.0.1:8000/graphql to access the endpoint

```bash
python manage.py runserver
```
