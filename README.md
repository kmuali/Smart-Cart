# Smart-Cart
IEEE HSB - Smart Cart

![Example](./docs/cart-real-example.jpg)

##  Product Perspective
The Amazon cart will be added system to supermarket where user can serve himself, interact with cart interface presented on 
TFT display and paying by google pay by his phone

## Product Features
Real time tracking of added and removed products from the cart
Easy way for payment using GPAY

## References
1. [Google Pay API](https://developers.google.com/pay/api/android/guides/test-and-deploy/integration-checklist)
2. [Flutter Payment Integration, Google Pay](https://dhruvnakum.xyz/flutter-payment-integration-google-pay)
3. [Google Pay and Apple Pay Integration in Flutter Apps](https://medium.com/vijay-r/google-pay-and-apple-pay-integration-in-flutter-apps-payments-in-flutter-app-mobile-payments-9fcfe6b4c7da)
4. [IEEE Std 830-1998 for SRS](http://www.math.uaa.alaska.edu/~afkjm/cs401/IEEE830.pdf)

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
