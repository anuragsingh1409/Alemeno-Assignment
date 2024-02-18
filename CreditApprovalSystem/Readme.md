Credit Approval System project built with Django and Django Rest Framework.
### Running the Application

To run the entire application and its dependencies, execute the following Docker Compose command:

```bash
docker-compose up --build
```
## 1. Register a Customer

**Endpoint:** `/api/customers/register/`

**Method:** `POST`

## 2. Check Loan Eligibility of Customer

**Endpoint:** `/api/customers/check-eligibility/`

**Method:** `POST`

## 3. Create a Loan for Customer

**Endpoint:** `/api/loans/create-loan/`

**Method:** `POST`

## 4. View Loan by Loan ID

**Endpoint:** `/api/loans/view-loan/<loan_id>/`

**Method:** `GET`

## 5. View Loans of a Customer

**Endpoint:** `/api/loans/view-loans/<customer_id>/`

**Method:** `GET`