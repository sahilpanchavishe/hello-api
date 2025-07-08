# 🌱 Hello API - Spring Boot

This is a simple REST API built using Spring Boot that returns greeting messages via `GET` and `POST` requests. It demonstrates use of `@RestController`, `@GetMapping`, `@PostMapping`, and `@PathVariable`.

## 🔧 Tech Stack
- Java 17
- Spring Boot
- Maven

## 📌 API Endpoints

| Method | Endpoint         | Description                         |
|--------|------------------|-------------------------------------|
| GET    | `/hello`         | Returns `"Hello world"`             |
| GET    | `/hello/{name}`  | Returns `"Hello {name}"`            |
| POST   | `/hello`         | Request body: name → `"Hello {name} !"` |


