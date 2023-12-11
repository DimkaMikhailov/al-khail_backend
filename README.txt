
git clone

python -m venv VENV_NAME

pip install -r req.txt

ручками создаем файл .env и добавляем данные, удаляем README.txt:
    SECRET_KEY=django-insecure-0d+i$9s1$y9^38q%x_25$nyh==4!-i!(8mgmd(wnrd63a_r8yp
    DEBUG=True

    PG_NAME=alkhail_backend_test
    PG_USER=alkhail_backend_admin
    PG_PASSWORD=alkhail_backend_1234
    PG_HOST=localhost
    PG_PORT=5432