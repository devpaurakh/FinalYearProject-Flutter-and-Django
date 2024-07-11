
# Hi, I'm Paurakh Saud! 👋


## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://www.paurakhsaud.com.np/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/paurakh-saud-17b4021a3/)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/_itsmeace01)


## 🛠 Skills
HTML, CSS, JAVASCRIPT,FLUTTER, DJANGO, ANDROID, IOS


# PartyPal Nepal

This project is a mobile application built with Flutter for the frontend and Django REST framework for the backend. It facilitates connections and planning for parties in Nepal.


## Authors

- [@Paurakh Saud](https://www.github.com/devpaurakh)


## Getting Started
1. Prerequisites:
 - [**Flutter**: Ensure you have Flutter installed and configured](https://docs.flutter.dev/get-started/install)
 - [**Python**: Download and install Python from](https://www.python.org/downloads/.)

- [**Django**: Install Django using](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project) `pip install django`

- [**PostgreSQL**: Install PostgreSQL from your system's package manager or follow the official guide]( https://www.postgresql.org/download/)

- [**Ngrok**: Download and install Ngrok to expose your local server publicly:](https://ngrok.com/)


## Clone the Repository:

I have two Repository for this Project One for the backend and for the Frontend 

1. Backend
```bash
  git clone https://github.com/devpaurakh/finalfinalbackend.git
```

2. Frontend
```bash
  git clone https://github.com/devpaurakh/finalfinalFrontend.git
```
## Set up the Backend

Navigate to the project's root directory.
Create a virtual environment (recommended):

1. Create Virtual Environment If needed
```bash
  python -m venv venv 
```
2. For Linux/macOS
```bash
  source venv/bin/activate
```
3. For Windows
```bash
  venv\Scripts\activate.bat
```
4. After creating Virtual Environemnt and Activate it.

```bash
  cd finalbackend
```
4. Then Install project dependencies:

```bash
  pip install -r requirements.txt
```
6. Run database migrations:

```bash
python manage.py makemigrations
python manage.py migrate
```

7. Start the Django development server:

```bash
  python manage.py runserver
```

8. Start the Django development server:

```bash
  add ngrok url in the setting.py  ALLOWS_SOST [ your-ngrok-subdomain.ngrok.io ]
```

```bash
  python manage.py runserver 
```

Copy the provided forwarding URL (e.g., https://your-ngrok-subdomain.ngrok.io) and use it in the Flutter app's baseURL variable for API calls.


9. Run the Flutter app:
```bash
  flutter run 
```
or
```bash
If your are using VScode got to top menu bar find Run inside the run click "Run Without Debugging"
  ```





## API Reference

#### Get all Party Palace

2. Main url Auth side:- api/user/

```http
  POST api/user/register/
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `User Detail` | `string` | **Required**. User Detail |


```http
  POST api/user/login/
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `email, password` | `string` | **Required**. email, password |



```http
  GET api/user/login/user_profile/
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `Access_Token` | `string` | **Required**. Access_Token|


```http
  PATCH api/user/login/update_user_profile/
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `Image Path` | `string` | **Required**. - |


```http
  POST api/user/login/change_password/
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `Password, Password2` | `string` | **Required**. Password, Password2|

```http
  POST api/user/login/change_password/
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `Password, Password2` | `string` | **Required**. Password, Password2|



2. Main url Venue Side:- api/partypalace/

```http
  GET api/partypalace/party-palace/
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `Auth_token`      | `string` | **Required**. Access_Token |




```http
  POST api/partypalace/party-palace/create/
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `Auth_token, Partypalace`      | `string` | **Required**. Access_Token |



```http
  GET api/partypalace/bookings/
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `Auth_token`      | `string` | **Required**. Access_Token |




```http
  POST api/partypalace/bookings/create/
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `Owner_name, Venue_name`      | `string` | **Required**. Access_Token |


## ScreenShots
<img width="324" alt="Screenshot 2024-07-11 at 11 34 31 AM" src="https://github.com/devpaurakh/KHArCHA/assets/100192320/2a83ce47-5988-43a2-8fdd-1a0ffd6845ae">
<img width="324" alt="Screenshot 2024-07-11 at 11 34 25 AM" src="https://github.com/devpaurakh/KHArCHA/assets/100192320/2a89d97a-f30c-4f36-a906-991e6bec292c">
<img width="326" alt="Screenshot 2024-07-11 at 11 34 16 AM" src="https://github.com/devpaurakh/KHArCHA/assets/100192320/678f0fff-5e42-4def-9c56-264fbd9deac6">
<img width="321" alt="Screenshot 2024-07-11 at 11 34 08 AM" src="https://github.com/devpaurakh/KHArCHA/assets/100192320/c6d657a4-2b68-4076-a7ea-98f06aa36b33">
<img width="321" alt="Screenshot 2024-07-11 at 11 34 01 AM" src="https://github.com/devpaurakh/KHArCHA/assets/100192320/30121031-e4d2-4353-849a-3260733d4551">
<img width="323" alt="Screenshot 2024-07-11 at 11 33 55 AM" src="https://github.com/devpaurakh/KHArCHA/assets/100192320/88f598cd-8e95-4a25-842e-e53136ef4bc5">
<img width="321" alt="Screenshot 2024-07-11 at 11 33 47 AM" src="https://github.com/devpaurakh/KHArCHA/assets/100192320/04ba4cee-f2e9-4541-b01e-3c2ade4ca447">
<img width="312" alt="Screenshot 2024-07-11 at 11 33 42 AM" src="https://github.com/devpaurakh/KHArCHA/assets/100192320/dc151376-2c28-4397-a0a8-3afad2ddf71a">
<img width="326" alt="Screenshot 2024-07-11 at 11 33 35 AM" src="https://github.com/devpaurakh/KHArCHA/assets/100192320/c442d7cd-50ed-40a8-b28e-01da03182837">
<img width="324" alt="Screenshot 2024-07-11 at 11 33 29 AM" src="https://github.com/devpaurakh/KHArCHA/assets/100192320/bed4b01b-9c9a-4b9b-a447-4bb84420df02">




