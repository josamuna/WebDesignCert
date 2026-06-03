# AvailabilityTable

Building a Availability Table Project.

## Source Code

```html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Availability Table</title>
    <link rel="stylesheet" href="./styles.css" />
  </head>

  <body>
    <main id="container">
      <table>
        <thead>
          <tr class="sharp">
            <th></th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
          </tr>
        </thead>
        <tbody>
          <tr class="half">
            <th rowspan="2" class="time">9 AM</th>
            <td class="available-0"></td>
            <td class="available-1"></td>
            <td class="available-2"></td>
            <td class="available-2"></td>
            <td class="available-5"></td>
          </tr>
          <tr class="sharp">
            <td class="available-3"></td>
            <td class="available-3"></td>
            <td class="available-3"></td>
            <td class="available-5"></td>
            <td class="available-5"></td>
          </tr>
          <tr class="half">
            <th rowspan="2" class="time">10 AM</th>
            <td class="available-3"></td>
            <td class="available-3"></td>
            <td class="available-5"></td>
            <td class="available-5"></td>
            <td class="available-5"></td>
          </tr>
          <tr class="sharp">
            <td class="available-0"></td>
            <td class="available-1"></td>
            <td class="available-4"></td>
            <td class="available-4"></td>
            <td class="available-0"></td>
          </tr>
          <tr class="half">
            <th rowspan="2" class="time">11 AM</th>
            <td class="available-3"></td>
            <td class="available-4"></td>
            <td class="available-1"></td>
            <td class="available-5"></td>
            <td class="available-5"></td>
          </tr>
          <tr class="sharp">
            <td class="available-5"></td>
            <td class="available-5"></td>
            <td class="available-3"></td>
            <td class="available-2"></td>
            <td class="available-0"></td>
          </tr>
          <tr class="half">
            <th rowspan="2" class="time">12 PM</th>
            <td class="available-3"></td>
            <td class="available-0"></td>
            <td class="available-4"></td>
            <td class="available-5"></td>
            <td class="available-5"></td>
          </tr>
          <tr class="sharp">
            <td class="available-1"></td>
            <td class="available-3"></td>
            <td class="available-3"></td>
            <td class="available-2"></td>
            <td class="available-0"></td>
          </tr>
          <tr class="half">
            <th rowspan="2" class="time">1 PM</th>
            <td class="available-3"></td>
            <td class="available-4"></td>
            <td class="available-4"></td>
            <td class="available-5"></td>
            <td class="available-5"></td>
          </tr>
          <tr class="sharp">
            <td class="available-0"></td>
            <td class="available-3"></td>
            <td class="available-4"></td>
            <td class="available-4"></td>
            <td class="available-4"></td>
          </tr>
          <tr class="half">
            <th rowspan="2" class="time">2 PM</th>
            <td class="available-3"></td>
            <td class="available-4"></td>
            <td class="available-4"></td>
            <td class="available-5"></td>
            <td class="available-5"></td>
          </tr>
          <tr class="sharp">
            <th></th>
            <td class="available-3"></td>
            <td class="available-3"></td>
            <td class="available-4"></td>
            <td class="available-5"></td>
            <td class="available-4"></td>
          </tr>
          <tr class="half">
            <th rowspan="2" class="time">3 PM</th>
            <td class="available-3"></td>
            <td class="available-4"></td>
            <td class="available-4"></td>
            <td class="available-5"></td>
            <td class="available-5"></td>
          </tr>
          <tr class="sharp">
            <td class="available-5"></td>
            <td class="available-5"></td>
            <td class="available-5"></td>
            <td class="available-4"></td>
            <td class="available-4"></td>
          </tr>
          <tr class="half">
            <th rowspan="2" class="time">4 PM</th>
            <td class="available-3"></td>
            <td class="available-0"></td>
            <td class="available-4"></td>
            <td class="available-2"></td>
            <td class="available-5"></td>
          </tr>
          <tr class="sharp">
            <td class="available-2"></td>
            <td class="available-5"></td>
            <td class="available-1"></td>
            <td class="available-5"></td>
            <td class="available-5"></td>
          </tr>
          <tr class="half">
            <th rowspan="2" class="time">5 PM</th>
            <td class="available-5"></td>
            <td class="available-0"></td>
            <td class="available-4"></td>
            <td class="available-4"></td>
            <td class="available-2"></td>
          </tr>
        </tbody>
      </table>
      <div id="legend">
        <span class="legend-availability">Availability </span>
        <div id="legend-line">
          <span>0</span>
          <div id="legend-gradient"></div>
          <span>5+</span>
        </div>
      </div>
    </main>
  </body>
</html>
```

```css
:root {
  --color0: #fff;
  --color1: #cdfecd;
  --color2: #9bfc9b;
  --color3: #51fb51;
  --color4: #05c705;
  --color5: #037c03;
  --solid-border: 1px solid #000;
  --dashed-border: 1px dashed #000;
}

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family: Arial, sans-serif;
  background-color: #acd2bf;
}

#container {
  display: flex;
  flex-direction: column;
  justify-content: center;
  gap: 50px;
  align-items: center;

  max-width: 768px;
  width: 100%;
}

.sharp {
  border-bottom: var(--solid-border);
}

.half {
  border-bottom: var(--dashed-border);
}

.sharp td {
  border-bottom: var(--solid-border);
}

.half td {
  border-bottom: var(--dashed-border);
}

.available-0 {
  background-color: var(--color0);
}

.available-1 {
  background-color: var(--color1);
}

.available-2 {
  background-color: var(--color2);
}

.available-3 {
  background-color: var(--color3);
}

.available-4 {
  background-color: var(--color4);
}

.available-5 {
  background-color: var(--color5);
}

#legend {
  display: flex;
  flex-direction: column;
  align-items: center;
  margin: 4rem 1rem 1rem;
}

table {
  border-collapse: collapse;
  width: 42rem;
  margin-top: 5rem;
  /*table-layout: fixed;*/
}

th {
  font-size: 1.12rem;
}

th,
tr {
  height: 1.5rem;
}

td:not(:first-child) {
  border-left: var(--solid-border);
  border-right: var(--solid-border);
}

/* 
Make items inside the first flex 
aligns in on column become inligned
*/
#legend-line {
  display: flex;
  align-items: center;
}

#legend-line span {
  width: 2rem;
  text-align: center;
}

#legend-gradient {
  width: 10rem;
  height: 1.6rem;
  border: 1px solid #000;
  background-image: linear-gradient(
    90deg,
    var(--color0) 0% 18%,
    var(--color1) 18% 34%,
    var(--color2) 34% 50%,
    var(--color3) 50% 66%,
    var(--color4) 66% 82%,
    var(--color5) 82% 100%
  );
}

.legend-availability {
  padding: 5px;
  font-size: 1.2rem;
}
```

## Output

![Image](https://github.com/user-attachments/assets/4b2904dd-f02a-4510-a1e3-a892c0ee86cc)
