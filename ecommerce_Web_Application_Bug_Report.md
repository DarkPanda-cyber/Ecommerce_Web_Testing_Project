## Bug Report - E-commerce web app

| Bug ID | Title | Environment | Steps to Reproduce | Expected Result | Actual Result | Severity | Priority | Status |
|:-------|:------|:------------|:-------------------|:----------------|:--------------|:---------|:---------|:-------|
| BUG 001 | Password reset email not received | Chrome (MacOs) / Test Env | 1. Go to Login <br> 2. Click "Forgot Password" <br> 3. Enter valid email <br> 4. Click Continue | Reset email should be sent to user | Success message shown but no email received | Medium | High | Open |
| BUG 002 | Submit button faulty on Product Returns | Chrome (MacOs) / Test Env | 1. Go to Orders <br> 2. Click Return icon <br> 3. Fill details <br> 4. Click Submit | Order should be returned successfully | Submit button is faulty; order not returned | High | High | Open |
| BUG 003 | No payment method for Gift Certificates | Chrome (MacOs) / Test Env | 1. Fill Gift Cert details <br> 2. Checkout <br> 3. Choose payment method | User should be able to select payment and confirm | No payment methods available to select | High | High | Open |
| BUG 004 | Negative quantity accepted in cart | Chrome (MacOs) / Test Env | 1. Go to product page <br> 2. Enter negative quantity <br> 3. Click Add to Cart | System should reject negative values | Negative value accepted and success message shown | Low | Low | Open |
| BUG 005 | Continue button faulty on Product Reviews | Chrome (MacOs) / Test Env | 1. Go to Product Reviews <br> 2. Enter review details <br> 3. Click Continue | Review should be submitted and visible | Review not submitted due to faulty button | Medium | Medium | Open |
