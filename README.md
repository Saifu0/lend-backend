# LenD 
LenD will help you to lend money with lowest interest rate.
This is repo contains the backend of the application.

## Installation
1. Create a virtual environment
```
virtualenv -p /usr/bin/python2.7 env
```

2. Switch to the virtual environment
```
source env/bin/activate
```

3. Install all the dependencies
```
pip install -r requirements.txt
```

4. Migrate the database
```
python manage.py migrate
```

5. Create a superuser
```
python manage.py createsuperuser
```

6. Run the development environment
```
python manage.py runserver
```

## Contributing 

- Setup the environment variables and source them
```
source .env
```

- Clone the repository
```
git clone git@github.com:Saifu0/lend-backend.git
```

- Pull the latest changes from `main` branch
```
git pull origin main
```

- Create a branch
```
git branch <BRANCH_NAME>
```

- Switch to the branch
```
git checkout <BRANCH_NAME>
```

- After doing changes and after committing, pull the latest changes once again and resolve merge conflict if these is any.
- Then push you branch and ask for review.
