# rn-assignment6-11065060
## 11065060
![alt text](<WhatsApp Image 2024-07-02 at 22.29.36_1f4674d0.jpg>)
![alt text](<WhatsApp Image 2024-07-02 at 22.29.36_064f2329.jpg>)
![alt text](<WhatsApp Image 2024-07-02 at 22.29.36_c8a4c66d.jpg>)
## Home Page
The homepage component of this React Native application serves as the primary interface for browsing and selecting products. It allows customers to view various clothing items, along with their details, and add them to their shopping cart.

### Product Display
- **Grid Layout:** Products are presented in a responsive grid format with flexwrap to ensure they adapt to different screen sizes.
- **Product Cards:** Each product is displayed in a card-like layout, clearly showcasing the image, name, description, and price.

## Implementation of Data Storage
- **AsyncStorage:** 
  - **Stores** the user's cart data locally on the device.
  - **Updates** the cart with new products using AsyncStorage, ensuring data persistence across app sessions for a seamless shopping experience.