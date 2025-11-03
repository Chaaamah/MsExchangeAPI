# Microservices Integration Project with Exchange API

## Overview
This project demonstrates the integration between a Product microservice and Chat microservice, with currency conversion capabilities using Exchange API. The system allows for CRUD operations on products while maintaining real-time currency conversions for international transactions.

## Architecture
- Product Microservice: Handles product management
- Chat Microservice: Manages communication features
- Exchange API Integration: Provides real-time currency conversion

## Prerequisites
- Java 17+
- Spring Boot 3.x
- Exchange API credentials

## Setup Instructions
1. Clone the repository
2. Configure environment variables:
   ```
   EXCHANGE_API_KEY=your_api_key
   ```
3. Start each microservice:
   ```

## API Documentation

### Product Service Endpoints
```
GET /api/products - List all products
POST /api/products/add - Create new product
GET /api/products/{id} - Get product details
PUT /api/products/{id} - Update product
DELETE /api/products/{id} - Delete product
```

### Achat Service Endpoints
```
GET /api/achats - List all achats
POST /api/achats/add - Create new achat
GET /api/achats/{id} - Get chat details
```