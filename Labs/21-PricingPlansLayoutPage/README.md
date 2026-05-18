# PricingPlansLayoutPage

Building a Pricing Plans LayoutPage Project.

## Source Code

```html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>Pricing Plans Layout Page</title>
    <link rel="stylesheet" href="./styles.css" />
  </head>
  <body>
    <h1>Pricing Plans</h1>
    <div class="pricing-container">
      <div class="pricing-card basic-plan">
        <h2>Basic</h2>
        <p class="pricing">$9/month</p>
        <ul>
          <li class="checked">Access to our core features</li>
          <li class="checked">Email support</li>
          <li class="unchecked">Advanced analytics</li>
          <li class="unchecked">Custom integrations</li>
          <li class="unchecked">Priority support</li>
        </ul>
        <a href="#">Choose Plan</a>
      </div>
      <div class="pricing-card pro-plan">
        <h2>Pro</h2>
        <p class="pricing">$19/month</p>
        <ul class="package">
          <li class="checked">Access to our core features</li>
          <li class="checked">Email support</li>
          <li class="checked">Advanced analytics</li>
          <li class="checked">Custom integrations</li>
          <li class="unchecked">Priority support</li>
        </ul>
        <a href="#">Choose Plan</a>
      </div>
      <div class="pricing-card premium-plan">
        <h2>Premium</h2>
        <p class="pricing">$29/month</p>
        <ul class="package">
          <li class="checked">Access to our core features</li>
          <li class="checked">Email support</li>
          <li class="checked">Advanced analytics</li>
          <li class="checked">Custom integrations</li>
          <li class="checked">Priority support</li>
        </ul>
        <a href="#">Choose Plan</a>
      </div>
    </div>
  </body>
</html>
```

```css
.pricing-container {
  display: flex;
  flex-wrap: wrap;
  border: 2px solid black;
  margin: 10px auto;
  padding: 20px;
  gap: 20px;
}

h1,
h2 {
  text-align: center;
}

h2 {
  margin-bottom: 10px;
}

.pricing {
  font-size: 1.3rem;
  text-align: center;
  color: #4e4c4c;
  font-weight: 700;
  margin: 0 30px;
  padding-bottom: 5px;
  border-bottom: 1px solid #6d6161;
}

.pricing-card {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  flex: 0 0 200px;
  border: 2px solid black;
  width: 220px;
}

.pricing-card:hover {
  transform: scale(1.05);
  transition: all 0.4s;
  box-shadow: 2px 2px 2px 2px #6d6161;
}

.pricing-card:not(:hover) {
  transition: all 0.4s;
}

.basic-plan {
  order: 0;
  background-color: #f7f7f7;
}

.pro-plan {
  order: 1;
  flex-grow: 2;
  background-color: #f0f8ff;
}

.premium-plan {
  order: 2;
  background-color: #fdf2f2;
}

ul li {
  list-style-position: outside;
  line-height: 2;
  padding: 0 10px 0;
}

li.checked::marker {
  content: '✓';
  font-weight: 600;
  color: #219c54;
}

li.unchecked::marker {
  content: '✗';
  font-weight: 600;
  color: #dd143c;
}

a {
  display: inline-block;
  text-decoration: none;
  cursor: pointer;
  align-items: center;
  background-color: #f1be32;
  width: 8em;
  margin: 20px auto 20px;
  text-align: center;
  padding: 10px 20px;
  color: black;
  font-size: 1.1rem;
  font-weight: 600;
  border-radius: 4px;
}

a:hover {
  background-color: #f1cf54;
}
```

## Output

### Initial State with Small View

![Image](https://github.com/user-attachments/assets/3ea41cc9-df35-4134-a52d-715a4e3e5472)

### State When Hovered over With Small View

![Image](https://github.com/user-attachments/assets/0a7ccac8-03f9-461c-a5fb-1da114e23d89)

### Initial State with Big View

![Image](https://github.com/user-attachments/assets/7b949e2e-002d-4d7c-8155-f4718867b4d6)

### State When Hovered over With big View

![Image](https://github.com/user-attachments/assets/6c55aa1a-902d-4c04-b131-80b9223c35eb)
