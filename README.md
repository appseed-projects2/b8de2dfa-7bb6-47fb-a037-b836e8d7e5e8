# Atlantis Lite Flask/Jinja

Open-source **Flask/Jinja Template** generated by `AppSeed` op top of **Atlantis Lite**, a modern `Bootstrap` dashboard design. The project is a super simple Flask project WITHOUT database, ORM, or any other hard dependency. The project can be used as a codebase for future project or to migrate the Jinja files and assets to a legacy Python-based project that uses Jinja as template engine (Flask, Bottle, Django).

- 👉 [Atlantis Dark Flask](https://appseed.us/product/atlantis-dark/flask/) - Product page
- 👉 [Complete documentation](https://docs.appseed.us/boilerplate-code/boilerplate-jinja) - `Learn how to use and update the product`
- ✅ [PRO Version Available](#pro-version) - `enhanced UI` and more `features` 
  
<br />

> Built with [Atlantis Dark Generator](https://appseed.us/generator/atlantis-dark/)

- Timestamp: `2022-07-08 16:48`
- Build ID: `b8de2dfa-7bb6-47fb-a037-b836e8d7e5e8`
- **Free [Support](https://appseed.us/support/)** (registered users) via `Email` and `Discord`

<br />

> Features

- `Up-to-date dependencies`
- Render Engine: Flask / [Jinja2](https://jinja.palletsprojects.com/)

<br />

![Atlantis Dark - Starter generated by AppSeed.](https://user-images.githubusercontent.com/51070104/172799909-4cbc8eed-fdde-4408-ab61-123f235212d0.png)

<br />



## ✨ How to use it

> Download the code 

```bash
$ # Get the code
$ git clone https://github.com/appseed-projects/b8de2dfa-7bb6-47fb-a037-b836e8d7e5e8.git
$ cd b8de2dfa-7bb6-47fb-a037-b836e8d7e5e8
```

<br />

### 👉 Set Up for `Unix`, `MacOS` 

> Install modules via `VENV`  

```bash
$ virtualenv env
$ source env/bin/activate
$ pip3 install -r requirements.txt
```

<br />

> Set Up Flask Environment

```bash
$ export FLASK_APP=run.py
$ export FLASK_ENV=development
```

<br />

> Start the app

```bash
$ flask run
```

At this point, the app runs at `http://127.0.0.1:5000/`. 

<br />

### 👉 Set Up for `Windows` 

> Install modules via `VENV` (windows) 

```
$ virtualenv env
$ .\env\Scripts\activate
$ pip3 install -r requirements.txt
```

<br />

> Set Up Flask Environment

```bash
$ # CMD 
$ set FLASK_APP=run.py
$ set FLASK_ENV=development
$
$ # Powershell
$ $env:FLASK_APP = ".\run.py"
$ $env:FLASK_ENV = "development"
```

<br />

> Start the app

```bash
$ flask run
```

At this point, the app runs at `http://127.0.0.1:5000/`. 

<br />

## ✨ Code-base structure

The project has a simple, intuitive structure presented bellow:

```bash
< PROJECT ROOT >
   |
   |-- apps/__init__.py
   |-- apps/
   |    |-- static/
   |    |    |-- <css, JS, images>         # CSS files, Javascripts files
   |    |
   |    |-- templates/
   |         |
   |         |-- includes/                 # Page chunks, components
   |         |    |
   |         |    |-- navigation.html      # Top bar
   |         |    |-- sidebar.html         # Left sidebar
   |         |    |-- scripts.html         # JS scripts common to all pages
   |         |    |-- footer.html          # The common footer
   |         |
   |         |-- layouts/                  # App Layouts (the master pages)
   |         |    |
   |         |    |-- base.html            # Used by common pages like index, UI
   |         |    |-- base-fullscreen.html # Used by auth pages (login, register)
   |         |
   |      index.html                       # The default page
   |      page-404.html                    # Error 404 page (page not found)
   |      page-500.html                    # Error 500 page (server error)
   |         *.html                        # All other pages provided by the UI Kit
   |
   |-- requirements.txt
   |
   |-- run.py
   |
   |-- ************************************************************************
```

<br />



## PRO Version

> For more components, pages and priority on support, feel free to take a look at this amazing starter:

Black Dashboard is a premium Bootstrap Design now available for download in Flask. Made of hundred of elements, designed blocks, and fully coded pages, Black Dashboard PRO is ready to help you create stunning websites and web apps.

- 👉 [Atlantis Dark PRO Flask](https://appseed.us/product/atlantis-dark-pro/flask/) - product page
  - ✅ `Enhanced UI` - more pages and components
  - ✅ `Priority` on support

<br >

![Atlantis Dark PRO - Starter generated by AppSeed.](https://user-images.githubusercontent.com/51070104/172800034-4d3adb79-d05e-430d-8ffe-f6860fc755f1.png)

<br />

---
Atlantis Lite Flask/Jinja - Open-source starter generated by **[AppSeed Generator](https://appseed.us/generator/)**.
