# 🔐 crAPI API Security Testing Lab

## 📌 Objective

Performed API security testing against crAPI using Burp Suite to identify authentication, authorization, business logic, and input validation weaknesses.

---

## 🛠 Tools Used

- Burp Suite Community Edition
- Kali Linux
- Firefox Browser
- crAPI Vulnerable API Application

---

## 🔍 Areas Tested

- JWT Authentication
- API Request Manipulation
- Business Logic Testing
- Parameter Tampering
- Input Validation Testing
- Error Handling Assessment

---

## 🚨 Key Findings

### 1. JWT Authentication Enforcement

Protected API endpoints correctly rejected requests without valid JWT tokens.

### 2. Business Logic Manipulation

Modified order quantity values using Burp Repeater to analyze application behavior and credit deduction logic.

### 3. Weak Input Validation

Supplying invalid product IDs triggered HTTP 500 Internal Server Error responses instead of proper validation handling.

### 4. API Workflow Analysis

Successfully analyzed:
- Login flow
- JWT token generation
- Order processing
- Community API responses

---

# 📷 Screenshots

## Login Request & JWT Token Response

![Login Request](screenshots/login-request.png)

---

## JWT Token Decoding

![JWT Token](screenshots/jwt-token-decoding.png)

---

## JWT Authentication Enforcement

![JWT Enforcement](screenshots/jwt-authentication-enforced.png)

---

## Successful Order Request

![Successful Order](screenshots/successful-order-request.png)

---

## Quantity Manipulation Testing

![Quantity Manipulation](screenshots/quantity-manipulation.png)

---

## Invalid Product ID Triggering HTTP 500 Error

![500 Error](screenshots/invalid-product-500-error.png)

---

## Community API Response Analysis

![Community API](screenshots/community-api-response.png)

---

## 📚 Skills Demonstrated

- API Security Testing
- Burp Suite Repeater
- JWT Analysis
- Business Logic Testing
- HTTP Request Manipulation
- Input Validation Testing
- Security Assessment Methodology

---

## ⚠ Disclaimer

This project was performed in a controlled lab environment using intentionally vulnerable applications for educational purposes only.
