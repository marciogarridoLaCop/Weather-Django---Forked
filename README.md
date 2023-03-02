# 🐍 Aplicativo de clima com Django

![GitHub repo size](https://img.shields.io/github/repo-size/Drack112/Weather-Django?style=for-the-badge)
![GitHub language count](https://img.shields.io/github/languages/count/Drack112/Weather-Django?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/Drack112/Weather-Django?style=for-the-badge)
![Bitbucket open issues](https://img.shields.io/bitbucket/issues/Drack112/Weather-Django?style=for-the-badge)
![Bitbucket open pull requests](https://img.shields.io/bitbucket/pr-raw/Drack112/Weather-Django?style=for-the-badge)

### ⭐ Funções e adeptos

- [x] Verificar clima com o OpenWeatherAPI

## 🚀

```bash
$ pip install -r requirements
```

## ☕ Rodando

Preencha o arquivo `.env.example` com as informações cobradas e depois renomeie para `.env`.

```env
SECRET_KEY=
DEBUG=
HOSTS=127.0.0.1 [::1] localhost
```

Agora realize as migrações necessárias:

```bash
$ make migrations && make migrate
```

E por fim, rode o aplicativo:

```bash
$ python3 manage.py runserver
```
