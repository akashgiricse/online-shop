# Online shop
An online shop webapp powered by Django

## How to use

### 1. Clone this repository
```commandline
git clone https://github.com/akashgiricse/online-shop
```
### 2. Inside *online-shop* directory run the following command to install `pipenv`
```commandline
pip3 install pipenv
```
### 3. Activate `pipenv` virtual environment
```commandline
pipenv shell
```
### 4. Install packages
```commandline
pipenv install
```
### 5. Inside outer `myshop` directory, rename the file `.env.example` to `.env`

### 6. Run database migrations (inside outer `myshop` directory)
```commandline
python manage.py migrate
```
### 7. Create superuser
```commandline
python manage.py createsuperuser
```
### 8. Run development server
```commandline
python manage.py runserver
```
## Contribute
- Issue tracker: [Issues](https://github.com/akashgiricse/online-shop/issues)

## Contributors
- [Akash Giri](https://github.com/akashgiricse/)
