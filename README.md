# Smart Cart

###### *Smart cart which provides the best shopping experience*

Customers need no cash money, no cashiers, nor printed invoices.
They just scan the QR code in cart's screen with their phone, pick their needs, 
and go, all automated via online payment!
That can significantly decrease labor cost in the long run 
and eliminates queues in rush hours.

The cart detects what a customer puts in or removes from the basket.
It displays what products are picked, their prices and total.
It also displays QR code to confirm payment from the phone's browser.

<!-------------------------------------------------------------------->

![Cart Example](./docs/cart-real-example.jpg)
![QR Example](./docs/cart-qr-example.jpg)

<!-------------------------------------------------------------------->
<!-------------------------------------------------------------------->
## Overall Description
### Product Perspective
The product has two core features, objects detection model, 
and main application. The project is divided into two sections, two teams, 
a team for each feature of them.

In this repository, we are concerned with the second, the main application. 
It is a web application which has two user interfaces, Cart interface and  
customer's phone interface.

<!-------------------------------------------------------------------->
### Product Features
- Automatic detection of products in cart's basket
- Display product details, quantities, prices, and total price
- Display QR code to confirm payment from web browser in customer's phone
- Send digital invoice to customer's account
- Create account for customer's to save payment method and previous invoices

<!-------------------------------------------------------------------->
### User Classes and Characteristics
The cart is made for single user, 
a customer who is in the market, has a payment method, and a smart phone.

<!-------------------------------------------------------------------->
<!-------------------------------------------------------------------->
## Specific Requirements
### Hardware Requirements
#### Components (Draft)

| # | Item | Description | Link | Required for | 
| - |:--------- |:----- | ---- | ------- |
| 1 | Raspberry Pi | Main controler and includes Wi-Fi | - | Development
| 2 | Camera | Detects produts inside the cart's basket | - | Development
| 3 | LCD Touch Screen | Displays products details and QR code of payment link | - | Production
| 4 | HDMI Cable | Connects touch screen with Raspberry Pi | - | Production 
| 5 | White torch(es) | Light the basket for the camera | - | Production
| 6 | Power Bank | Provides power for all components | - | Production
| 7 | Cart body | Has a suitable basket and holds torches and other components | - | Production

<!-------------------------------------------------------------------->
<!-- ### Software Requirements -->
<!-------------------------------------------------------------------->
<!-- #### Cart Application Functions  -->
<!--   - Send the invoice id (through NFC module) -->
<!--   - Show The cart content -->
<!--   - proceed the payment  -->
<!--   - Initiating invoice in database  -->
<!--   - check if the token payment is added to the invoice  -->
<!--   - Send invoice to the user email -->
<!--   - sdf -->
<!---->
<!-- #### Mobile App Functions (Web) -->
<!--   - User Sign in/Sign up -->
<!--   - Making a shopping list (NOTE Type) -->
<!--   - Receive invoice id (through NFC module) -->
<!--   - Add payment method (GPAY) -->
<!---->

<!-- ## Timeline -->
<!---->
<!-- > 4 Weeks time line -->
<!---->
<!-- - Week 1: -->
<!--   - The first half of the API  -->
<!--   - Most of Interface   -->
<!--   - Most Mobile Application -->
<!-- - Week 2: -->
<!--   - Finish The first half of the API  -->
<!--   - Finish Most of Interface  -->
<!--   - Finish Most Mobile Application -->
<!-- - Week 3: -->
<!--   - TESTING -->
<!-- - Week 4: -->
<!--   - FOR ANY DELAYS -->
<!---->
<!-- ## Documentation -->
<!-- ### Software Requirements Specification -->
<!---->
<!-- [SRS](https://www.canva.com/design/DAF8CRP1bgE/U058Kk-7zvLUVRiLpafPwg/view?utm_content=DAF8CRP1bgE&utm_campaign=designshare&utm_medium=link&utm_source=editor "title") -->
