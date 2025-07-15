# Invoice Spring Boot Application

A simple Spring Boot REST API to manage invoices with CRUD operations.

## Features
- Create Invoice
- Read All Invoices
- Update Invoice
- Delete Invoice
- Integrated with MySQL

## Tech Stack
- Java 17
- Spring Boot
- Spring Data JPA
- MySQL
- Postman (for testing)

## API Endpoints
| Method | Endpoint              | Description           |
|--------|------------------------|------------------------|
| GET    | /api/invoices         | Get all invoices       |
| GET    | /api/invoices/{id}    | Get invoice by ID      |
| POST   | /api/invoices         | Create a new invoice   |
| PUT    | /api/invoices/{id}    | Update an invoice      |
| DELETE | /api/invoices/{id}    | Delete an invoice      |

## Sample JSON for POST
```json
{
  "customerName": "Vishnu Kanth",
  "amount": 1999.99,
  "date": "2025-07-15"
}
