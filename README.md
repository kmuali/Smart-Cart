# Smart Cart

*Smart cart for supermarkets that provides the best shopping experience*

Customers need no cash money, no cashiers, nor printed invoices.
They just scan the QR code in cart's screen with their phone, pick their needs, 
and go, all automated via online payment!
That can significantly decrease labor cost in the long run 
and eliminates queues in rush hours.

The cart detects what a customer puts in or removes from the basket.
It displays what products are picked, their prices and total.
It also displays QR code to confirm payment from the phone's browser.

![Cart Example](./docs/cart-real-example.jpg)
![QR Example](./docs/cart-qr-example.jpg)


## Specific Requirements 
### Components

### Functional Requirements

- Mobile App functions:
  - User Sign in/Sign up
  - Making a shopping list (NOTE Type)
  - Receive invoice id (through NFC module)
  - Add payment method (GPAY)
    
- Raspberry PI functions:
  - Send the invoice id (through NFC module)
  - Show The cart content
  - proceed the payment 
  - Initiating invoice in database 
  - check if the token payment is added to the invoice 
  - Send invoice to the user email


## Timeline

> 4 Weeks time line

- Week 1:
  - The first half of the API 
  - Most of Interface  
  - Most Mobile Application
- Week 2:
  - Finish The first half of the API 
  - Finish Most of Interface 
  - Finish Most Mobile Application
- Week 3:
  - TESTING
- Week 4:
  - FOR ANY DELAYS



## Documentation
### Software Requirements Specification

[SRS](https://www.canva.com/design/DAF8CRP1bgE/U058Kk-7zvLUVRiLpafPwg/view?utm_content=DAF8CRP1bgE&utm_campaign=designshare&utm_medium=link&utm_source=editor "title")
