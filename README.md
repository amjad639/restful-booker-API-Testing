# Restful Booker API Testing

API testing project for the [Restful Booker](https://restful-booker.herokuapp.com) platform using Postman.

## Project Structure

- `auth.postman_collection.json` — Create Token request
- `books.postman_collection.json` — All booking requests
- `New Environment.postman_environment.json` — Environment variables

## Requests

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | /auth | Create authentication token |
| GET | /booking | Get all bookings |
| GET | /booking/:id | Get booking by ID |
| POST | /booking | Create new booking |
| PUT | /booking/:id | Update full booking |
| PATCH | /booking/:id | Partial update booking |
| DELETE | /booking/:id | Delete booking |

## How to Use

1. Import the collection files into Postman
2. Import the environment file into Postman
3. Run `Create Token` request first to generate the token
4. Run the requests in order

## Environment Variables

| Variable | Description |
|----------|-------------|
| base_url | https://restful-booker.herokuapp.com |
| token | Authentication token (auto-saved) |
| booking_id | Booking ID (auto-saved) |
