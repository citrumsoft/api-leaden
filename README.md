# API Documentation

## Overview
This document describes the usage of the API endpoints for user authentication and lead generation in the Citrumsoft project. The API is consumed via JavaScript using Axios for HTTP requests.

## Base URL
- **URL**: `https://citrumsoft.com/api/`

## Endpoints

### Authentication
- **Endpoint**: `/auth-api`
- **Method**: `POST`
- **Headers**:
  - `X-Api-Key`: `your_api_key`
- **Payload**:
  ```json
  {
    "email": "user@example.com",
    "id": "user_id"
  }
