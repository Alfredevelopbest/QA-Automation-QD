# QueenDreams API Automation Testing

Automated CRUD API testing project developed for the QueenDreams mattress management system.

## Project Overview

This project demonstrates automated REST API testing using Postman for a mattress e-commerce backend developed in ASP.NET Core 8.

The automation covers the complete CRUD workflow for the Product module.

---

## Technologies Used

- ASP.NET Core 8
- PostgreSQL
- Postman
- REST API Testing
- JSON
- Swagger

---

## Automated Endpoints

### Product Module

| Method | Endpoint |
|---|---|
| GET | /api/Product |
| POST | /api/Product |
| PUT | /api/Product |
| DELETE | /api/Product |

---

## Automated Test Validations

The automated tests validate:

- HTTP status codes
- Response time
- JSON structure
- Dynamic ID generation
- CRUD workflow execution
- Data persistence validation

---

## Automation Workflow

The collection executes automatically in the following order:

1. GET Products
2. CREATE Product
3. UPDATE Product
4. DELETE Product

The product ID generated during creation is automatically stored and reused in subsequent requests.

---

## Postman Files

The repository includes:

- Postman Collection
- Postman Environment
- Automated CRUD workflow
- Dynamic variables

Location:

```txt
/postman
```

---

## Demo Video

Google Drive demo link:

PASTE_YOUR_VIDEO_LINK_HERE

---

## Author

Alfredo

---

## Academic Purpose

This project was developed for educational and academic purposes.
