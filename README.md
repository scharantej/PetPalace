## Flask Application: Pet Product Sales Website

### HTML Files:

1. **index.html**:
   - This is the homepage of the website.
   - It contains an attractive banner image, a brief introduction to the website, and a link to the products page.

2. **products.html**:
   - This page displays all the pet products available for sale.
   - Each product includes its image, title, price, and a brief description.
   - It also includes a button for adding the product to the shopping cart.

3. **cart.html**:
   - This page shows the products added to the shopping cart.
   - It allows users to modify the quantity and remove items from their cart.
   - It includes a button for proceeding to checkout.

4. **checkout.html**:
   - This page collects the user's details, including name, address, and payment information.
   - It also displays the total cost of the order and provides a button to confirm the purchase.

5. **confirmation.html**:
   - This page shows a confirmation message once the purchase is complete.
   - It includes the order details and a link to the user's account page.

### Routes:

1. **Homepage**:
   - Route: `'/'`
   - HTTP Method: `GET`
   - Purpose: Display the homepage (index.html).

2. **Products**:
   - Route: `'/products'`
   - HTTP Method: `GET`
   - Purpose: Display the list of products available for sale (products.html).

3. **Add to Cart**:
   - Route: `'/add_to_cart/<product_id>'`
   - HTTP Method: `POST`
   - Purpose: Add a product to the shopping cart by incrementing the quantity.

4. **Update Cart**:
   - Route: `'/update_cart'`
   - HTTP Method: `POST`
   - Purpose: Update the quantity of a product in the shopping cart.

5. **Remove from Cart**:
   - Route: `'/remove_from_cart/<product_id>'`
   - HTTP Method: `POST`
   - Purpose: Remove a product from the shopping cart.

6. **Checkout**:
   - Route: `'/checkout'`
   - HTTP Method: `GET`
   - Purpose: Display the checkout page (checkout.html).

7. **Process Checkout**:
   - Route: `'/process_checkout'`
   - HTTP Method: `POST`
   - Purpose: Process the user's checkout details and payment information.

8. **Confirmation**:
   - Route: `'/confirmation'`
   - HTTP Method: `GET`
   - Purpose: Display the confirmation page after a successful purchase (confirmation.html).