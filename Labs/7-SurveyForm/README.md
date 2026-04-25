# Survey Form

A Survey Form to get user data.

## Source Code

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Survey Form</title>
  </head>
  <body>
    <h1 id="title">Survey Form of AI Usage</h1>
    <p id="description">This survey has the role of knowing more about people's AI usage.</p>
    <form id="survey-form">
      <label id="name-label">Name:</label>
      <input type="text" id="name" name="name" placeholder="Enter your name" required><br>
      <label id="email-label">Email:</label>
      <input type="email" id="email" name="email" placeholder="Enter your email" required><br>
      <label id="number-label">Age (Optional):</label>
      <input type="number" id="number" name="number" min="3" max="100" placeholder="Age"><br>
      <p>
        <label for="dropdown">What is your favorite AI Tool:</label>
      </p>
      <p>

        <select id="dropdown" name="dropdown">
          <option value="" selected disabled>Select your favorite AI tool</option>
          <option value="chatgpt">ChatGPT</option>
          <option value="gemini">Gemini</option>
          <option value="Grok">Grok</option>
          <option value="deepseek">DeepSeek</option>
          <option value="claude">Claude</option>
          <option value="other">Other</option>
        </select>
      </p>Would you recommend AI tools to someone?</p>
      <input type="radio" id="option1" name="group" value="definitely" checked>
      <label for="option1">Definitely</label>
        <input type="radio" id="option2" name="group" value="maybe">
        <label for="option2">Maybe</label>
        <input type="radio" id="option3" name="group" value="notsure">
        <label for="option3">Notsure</label>

      <p>In which context could you use AI Tool?</p>
      <input type="checkbox" id="programming" name="choice" value="programming">
      <label for="programming">Programming</label>
      <input type="checkbox" id="learning" name="choice" value="learning" checked>
      <label for="learning">Learning</label>
      <input type="checkbox" id="designing" name="choice" value="designing">
      <label for="designing">Designing</label>
      <input type="checkbox" id="job" name="choice" value="job">
      <label for="job">Job</label>
      <p>Have you additional comments?</p>
      <textarea cols="40" rows="5" id="comment" name="comment" placeholder="Add your comments here."></textarea><br>

      <button type="submit" id="submit">Submit</button>
    </form>
  </body>
</html>
```

## Output

![Image](https://github.com/user-attachments/assets/95d05626-6459-4fab-b5d6-8d4809ae08ab)
