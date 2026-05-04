# Book Store API

This project contains RAML specification for an online book store API.

# Structure:
- dataTypes
- traits
- resourceTypes
- securitySchemes
- examples

# Modular specification structure

api/
│
├── api.raml
├── traits/
│   ├── paginated.raml
│   ├── secured.raml
│
├── resourceTypes/
│   ├── collection.raml
│   ├── item.raml
│
├── dataTypes/
│   ├── User.raml
│   ├── Book.raml
│   ├── Order.raml
│   ├── ErrorResponse.raml
│
├── securitySchemes/
│   ├── oauth2.raml
│
├── examples/
│   ├── user-example.json
│   ├── order-example.json