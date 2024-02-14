#Step 1: Clone the project

#Step 2: Open client directory and run the following command to install the packages.

### `npm init`

#Step 3: Open server directory and run the following command to install the packages.

### `npm init`

#Step 4: Create a database named 'budget-buddy' using MongoDB.

#Step 5: Create .env file in both /client directory and /server directory

In client's .env add the following:

### `REACT_APP_API = http://localhost:8080`

In server's .env add the following:

### `PORT = 8080`

### `MONGO_URL = <YOUR_MONGODB_CONNECTIONSTRING>`

### `JWT_SECRET_KEY = <STRONG_KEY>`

#Step 6: Run the app in developer mode

### `npm run dev`
