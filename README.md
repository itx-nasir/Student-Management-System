# Django-School-Management-System

This app is meant to be used by school manager to manage their school records:
 - student data
 - staff
 - results and
 - finances.

It currently doesn't allow students/staff to login.


## Demo
Live demo available at: https://student-management-system-gfln.onrender.com

Note: The app may take a few seconds to wake up if it hasn't been accessed recently (Render free tier spins down after inactivity).

## Usage
Install in a Virtual Environment. Once you have set up a VE, clone this project
```bash
git clone git@github.com:itx-nasir/Student-Management-System.git
```
Then

```bash
cd Django-School-Management-System
```
Run

```python
pip install -r requirements.txt #install required packages
python manage.py migrate # run first migration
python manage.py runserver # run the server
```
Then locate http://172.0.0.1:8000

## Admin Login
When you run migrate, a superuser is created.
```bash
username: admin
password: admin123
```

## Roadmap
To build a fully fledged open source school management.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## Coding Standards
```bash
isort .
black .
```

## Test
```base
python manage.py test
```

## Author
Nasir Iqbal

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Actively under development


