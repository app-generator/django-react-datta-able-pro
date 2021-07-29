# [Django React Datta PRO](https://appseed.us/product/django-react-datta-able-pro)

**Datta Able** is a premium **React Dashboard** that provides a colorful and modern design. Datta Able React PRO is the most stylized React Free Admin Template, around all other admin templates in the market. It comes with high feature-rich pages and components with fully developer-centric code. The product comes with a simple JWT authentication flow: login/register/logout.

<br />

> Features

- Modern aesthetics UI design - Designed by [CodedThemes](https://codedthemes.com/)
- React, Redux, Redux-persist
- Authentication: JWT Login/Register/Logout
- (Optional) - can be used with a [Django API Server](https://github.com/app-generator/api-server-django) for a complete full-stack experience 

<br />

> Links

- [Django React Datta PRO](https://appseed.us/product/django-react-datta-able-pro) - product page
- [Django React Datta PRO](https://django-react-datta-able-pro.appseed-srv1.com) - LIVE Demo
- [Django API Server](https://github.com/app-generator/api-server-server) - the backend server 
- Support via **Github** (issues tracker) and [Discord](https://appseed.us/support) - LIVE Assistance 

<br >

![Django React Datta Able - Open-source full-stack seed project crafted by CodedThemes and AppSeed.](https://user-images.githubusercontent.com/51070104/125737710-834a9e6f-c39b-4f3b-a42a-9583ce2ce1da.png)

<br />

## Start Django API Server

Simple starter built with Python / Django Rest / Sqlite3 and JWT Auth. The authentication flow is based on [json web tokens](https://jwt.io).

> Requirements

- Django==3.2.5
- djangorestframework==3.12.4
- PyJWT==2.1.0
- django-cors-headers==3.7.0 

<br />

> How to use the code

**Clone the sources**

```bash
$ git clone https://github.com/app-generator/api-server-django.git
$ cd api-server-django
```

**Create a virtual environment**

```bash
$ virtualenv -p python3 venv
$ source venv/bin/activate
```

**Install dependencies** using pip

```bash
$ pip install -r requirements.txt
```

**Start the API server** 

```bash
$ python manage.py migrate
$ python manage.py runserver 5000
```

The API server will start using the default port `5000`. 

<br />

## Start React UI 

To use the product Node JS (>= 12.x) is required and GIT to clone/download the project from the public repository.

**Step #1** - Clone the project

```bash
$ git clone https://github.com/app-generator/priv-react-datta-able-dashboard-pro.git
$ cd priv-react-datta-able-dashboard-pro
```

<br >

**Step #2** - Install dependencies via NPM or yarn

```bash
$ npm i
// OR
$ yarn
```

<br />

**Step #3** - Start in development mode

```bash
$ npm run start 
// OR
$ yarn start
```

<br />

## Configure the backend server

The product comes with a usable JWT Authentication flow that provides only the basic requests: login/logout/register. 

**API Server URL** - `src/config/constant.js` 

```javascript
const config = {
    ...
    API_SERVER: 'http://localhost:5000/api/'  // <-- The magic line
};
```

<br />

---
[Django React Datta PRO](https://appseed.us/product/django-react-datta-able-pro) - Provided by [CodedThemes](https://codedthemes.com/) and **AppSeed [App Generator](https://appseed.us/app-generator)**.
