# Cafe-Explorer-App

Cafe Explorer is a web application built with Flask that allows users to discover and manage cafes. Users can add new cafes, update coffee prices, delete closed cafes, and search for cafes based on location.

## Features

- Add new cafes with details such as name, location, map URL, and more.
- Update coffee prices for existing cafes.
- Delete closed cafes from the database.
- Search for cafes by location.
- Get random cafe recommendations.

## Setup

1. Clone this repository to your local machine.

```bash
git clone https://github.com/amnullh/Cafe-Explorer-App.git
```

2. Install the required dependencies:

```bash
pip install -r requirements.txt
```

3. Create a SQLite database named `cafes.db` in the project directory:

```bash
touch cafes.db
```

4. Run the Flask application:

```bash
python app.py
```

5. Access the web app at [http://localhost:5000](http://localhost:5000).

## Endpoints

- `GET /`: Home page of the web app.
- `POST /add`: Add a new cafe to the database.
- `PATCH /update-price/<int:cafe_id>`: Update the coffee price for a cafe.
- `DELETE /report-closed/<int:cafe_id>`: Delete a closed cafe from the database.
- `GET /all`: Retrieve all cafes from the database.
- `GET /search`: Search for cafes by location.
- `GET /random`: Get a random cafe recommendation.

## Usage

1. Visit the home page and explore cafes.
2. Add new cafes using the "Add a New Cafe" form.
3. Update coffee prices for existing cafes.
4. Delete closed cafes to keep the database up to date.
5. Search for cafes by location to find cafes in your area.
6. Get a random cafe recommendation for your next visit.

## Postman Documentation

For detailed API documentation and examples, please refer to the [Postman Documentation](https://documenter.getpostman.com/view/28841570/2s9Xxtxaq5).
