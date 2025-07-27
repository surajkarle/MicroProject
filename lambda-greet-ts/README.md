# AWS Lambda Greeting Function (TypeScript)

A simple AWS Lambda function written in TypeScript that greets the user based on the query parameter.

## 🛠️ Tech Stack

- TypeScript
- AWS Lambda
- Node.js (Runtime 20.x)
- AWS Console

## 📋 How It Works

The Lambda function reads the query parameter `name` from the API Gateway or test event, and returns a greeting message.

### Sample Response:

```json
{
  "statusCode": 200,
  "headers": {
    "Content-Type": "application/json"
  },
  "body": "{\n  \"message\": \"Hello, Suraj! Welcome to AWS Lambda with TypeScript.\"\n}"
}
🚀 Deployment Steps
Clone the repo

Run npm install

Run npx tsc

Zip the dist folder

Upload to AWS Lambda

Set handler: index.handler

🔗 Connect with Me
Made with 💻 by Suraj Karle

yaml
Copy
Edit

---

Let me know if you want help generating the GitHub repo name or writing your LinkedIn post.