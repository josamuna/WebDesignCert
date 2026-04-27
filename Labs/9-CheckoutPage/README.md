# CheckoutPage

Checkout page project supporting accessibility purposes.

## Source Code

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>Checkout Page</title>
  </head>

  <body>
    <h1>Checkout</h1>
    <section>
      <h2>Your Cart</h2>
      <img
        src="https://cdn.freecodecamp.org/curriculum/labs/cube.jpg"
        alt="A puzzle with lot of color."
      />
    </section>
    <section>
      <h2>Payment Information</h2>
      <form method="GET" action="">
        <label for="card-name"
          >Cardholder Name <span aria-hidden="true">*</span></label
        >
        <input type="text" id="card-name" name="card-name" required /><br />
        <label for="card-number"
          >Card Number <span aria-hidden="true">*</span></label
        >
        <input
          type="text"
          id="card-number"
          name="card-number"
          aria-describedby="card-number-help"
          required
        />
        <p id="card-number-help">
          Please enter your 16 digits Card Number without dashes or spaces
        </p>
        <label for="card-expiry-date"
          >Expiry date <span aria-hidden="true">*</span></label
        >
        <input
          type="text"
          id="card-expiry-date"
          name="card-expiry-date"
          placeholder="MM/YY"
          required
        /><br />
        <label for="card-cvv">CVV <span aria-hidden="true">*</span></label>
        <input type="text" id="card-cvv" name="card-cvv" required /><br />
        <button type="submit" id="submit">Place order</button>
      </form>
    </section>
  </body>
</html>
```

## Output

![Image](https://github.com/user-attachments/assets/3031921e-efa7-4c36-8b0b-0c8bb7af1ad3)
