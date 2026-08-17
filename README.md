# e-commerce-page
Fetching data from database about user information and user cart 

# E-Commerce Backend with Microservices

This project demonstrates how to build and manage backend tasks using a **microservices architecture**. Each microservice is designed to handle a specific domain (such as products, users, orders, or payments), and they communicate with each other to provide a seamless API experience.

## 🔧 Features
- Multiple microservices: Independent services for different backend tasks
- Data aggregation: Collects and combines data from multiple microservices
- API endpoints: Exposes REST APIs to fetch and display aggregated data
- Scalability: Each service can be scaled independently
- Loose coupling: Services are modular and maintainable

## 📂 Project Structure
- **User Service** → Manages user data and authentication
- **Product Service** → Handles product catalog and inventory
- **Order Service** → Processes customer orders
- **Payment Service** → Manages transactions and billing
- **API Gateway** → Routes requests and aggregates responses

## 🚀 How It Works
1. Client hits an API endpoint  
2. The API Gateway forwards the request to relevant microservices  
3. Each microservice processes its part and returns data  
4. Gateway aggregates the responses and sends back a unified result  

## 📌 Use Cases
- Building scalable e-commerce platforms  
- Learning microservices communication patterns  
- Practicing API design and integration
