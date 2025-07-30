# API Test Task – Postman

This repository contains a Postman collection created for the Collabera assessment task. The collection includes basic API tests using dynamic data generation and built-in test scripts.

## 📂 Collection Contents

1. **Create User (POST)**
   - Dynamically generates a unique name and email using timestamp
   - Randomizes `gender` (male/female) and `status` (active/inactive)
   - Validates that the returned `id` is a number

2. **Get Users (GET)**
   - Retrieves a list of users
   - Validates that the `status` of the first entry is either `active` or `inactive`

## ▶️ How to Run

1. **Import the Collection**
   - Open [Postman](https://www.postman.com/)
   - Import `Collabera Assessment Test.postman_collection.json` into your workspace

2. **Run the Tests**
   - Use the **Collection Runner**, or manually send each request
   - No need to modify request data; dynamic values are auto-generated via Pre-request Scripts

## 🔐 Authorization
- The POST request uses a Bearer Token in the header.
- Make sure the token is valid if you are modifying or running against a different environment.

## 🛠 Environment
- This collection does not require a separate Postman environment file.
