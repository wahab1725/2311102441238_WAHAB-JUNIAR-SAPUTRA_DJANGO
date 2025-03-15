# Personal Portfolio

[Python](#) [Django](#)

Website ini merupakan portfolio pribadi saya yang berisi tentang informasi diri saya, project yang pernah saya kerjakan. Website ini dibuat menggunakan Django.

**Ada apa saja di website ini?**

- **apps pengguna**: membuat model pengguna
- **apps berita**: membuat model berita

## Prerequisites

- Python 3.8 or higher
- pip (Python package installer)
- Git

## Installation

1. buka command prompt
2. Arahkan ke folder tempat web kita berada
3. setelah itu kita buat venv
```
py -m venv .venv
```
4. untuk mengaktifkannya, kita masuk ke folder env, masuk lagi ke folder Scripts, setelah itu kita ketik 
```
.venv\Scripts\activate
```
5. dan kemudian kita membuat project baru django 
```
django-admin startproject portofolio
```
6. setelah itu jika ingin membuat apps kita bisa mengetik
```
python manage.py startapp pengguna
python manage.py startapp berita
```
7. serelah itu, untuk membuat migration kita dapat mengetikkan
```
python manage.py makemigrations pengguna
python manage.py makemigrations berita
```
8. Setelah project dan apps telah dibuat dan untuk mengeceknya kita bisa mengetik 
```
py manage.py runserver
```


