# FeatureSelectionPage

Designing a Feature Selection Page Project.

## Source Code

```html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <title>Selection Feature Page</title>
    <link rel="stylesheet" href="./styles.css" />
  </head>

  <body>
    <h1>Feature Selection</h1>
    <div class="feature-card-container">
      <label class="feature-card">
        <input type="checkbox" />
        <span>Cloud Storage</span>
        <p class="item-label">100 Gigabyte secure storage</p> </label
      ><label class="feature-card">
        <input type="checkbox" />
        <span>Dedicated Support</span>
        <p class="item-label">24/7 customer help</p> </label
      ><label class="feature-card">
        <input type="checkbox" />
        <span>Advanced Analytics</span>
        <p class="item-label">Insights & reports</p> </label
      ><label class="feature-card">
        <input type="checkbox" />
        <span>Custom User Themes</span>
        <p class="item-label">Personalized dashboard design</p> </label
      ><label class="feature-card">
        <input type="checkbox" />
        <span>Multi-User Collab</span>
        <p class="item-label">Team access and sharing</p> </label
      ><label class="feature-card">
        <input type="checkbox" />
        <span>API Access</span>
        <p class="item-label">Integrate with your custom built tools</p>
      </label>
    </div>
  </body>
</html>
```

```css
* {
  margin: 0;
  padding: 0;
}

body {
  font-family: Arial, Tahoma, sans-serif;
  background-color: #fafafa;
}

h1 {
  text-align: center;
  margin-top: 50px;
}

.feature-card-container {
  margin: 5px auto;
  padding: 20px;
  max-width: 600px;
  min-width: 400px;
}

.feature-card {
  border: 2px solid #d3d3d3;
  border-radius: 10px;
  display: inline-block;
  width: 44.5%;
  height: 15vh;
  padding: 10px;
  margin-bottom: 3%;
}

.feature-card:hover {
  cursor: pointer;
  box-shadow: 1px 1px 8px 2px #ffdc8a;
  border: 2px solid #ffcb63;
}

.feature-card span {
  display: block;
  font-size: 1.1rem;
  font-weight: 600;
  text-align: center;
}

.item-label {
  text-align: center;
  margin-top: 10px;
  font-size: 0.87rem;
}

.feature-card:nth-child(odd) {
  margin-right: 3%;
}

input[type='checkbox'] {
  appearance: none;
  width: 20px;
  height: 20px;
  border: 2px solid #d3d3d3;
  border-radius: 4px;
  cursor: pointer;
  transition: all 0.3s;
}

input[type='checkbox']:checked {
  background-color: #ffb752;
  border-color: #ffbd33;
}

input[type='checkbox']::after {
  content: '✓';
  display: block;
  color: white;
  text-align: center;
  font-weight: bold;
}
```

## Output

![Image](https://github.com/user-attachments/assets/290215ec-81ff-48aa-a348-8cf363640dc3)
