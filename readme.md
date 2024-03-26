## Getting Started

1. Clone this repository: `git clone https://github.com/RishabhJain0721/DormDeals-Backend.git`
2. Navigate to the project directory: `cd DormDeals-Backend`
3. Install dependencies: `npm install`
4. Copy the contents of `.env.example` to `.env` and change the api with your own:

    ```shell
    cp .env.example .env
    ```
    The following environment variables must be set:

    - `MONGODB_CONNECTION_STRING` - The connection string for the MongoDB database

    - `SECRET_KEY` - The secret key for JWT authentication

    - `ADMIN_EMAIL` - The email address of the admin user

    - `ADMIN_PASSWORD` - The password of the admin user

To obtain `ADMIN_EMAIL` AND `ADMIN_PASSWORD` go to your google accounts manage your google accounts settings then security > 2 step verification (turn it on if off) > App passwords > create and copy that new generated password and paste it in `ADMIN_PASSWORD` environment variable

    

https://github.com/Gourav-21/DormDeals-Backend/assets/107918791/aef2b9a8-0a66-42bc-ba8f-0b0c2322975f


5. Run the app: `npm run dev`
