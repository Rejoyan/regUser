# User Registration API

## Setup and Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Rejoyan/regUser.git 

2. Navigate into the project directory:

cd user-registration-api


3. Install dependencies:

composer install

4. Set up your .env file and configure the database connection

5. php artisan migrate


6. php artisan serve


  API Endpoint

POST /api/register

    Request Body:

    {
    "name": "",
    "email": "@",
    "password": ""
}

    Response:

    {
    "id": 1,
    "name": " ",
    "email": ""
    "created_at": "2024-12-18T10:00:00Z"
}
