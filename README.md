[![AWS AI Stack](https://github.com/user-attachments/assets/0550b6d6-5b97-4549-92a0-9c919d8e0b45)](https://awsaistack.com/login)

**AWS AI Stack** – A ready-to-use, full-stack boilerplate project for building serverless AI applications on AWS. A great fit for those seeking a trusted AWS foundation for AI apps and access to powerful LLM models via Bedrock.

**[View the Live Demo](https://awsaistack.com/login)**

Use this as a boilerplate project to create an AI Chat bot, authentication services, business logic, and async workers, all running on AWS Lambda, API Gateway, DynamoDB, and EventBridge.

## Features

- **Full-Stack Application**: React frontend, API Gateway/Lambda backend, DynamoDB database, and AWS Bedrock for AI.
- **AI Chat**: Full serverless architecture for AI chatting with streaming responses.
- **Multiple AI Models**: Claude, Llama, Mistral, and more through Bedrock, ensuring data privacy.
- **100% Serverless**: Pay only for what you use. Auto-scaling out of the box.
- **Built-In Authentication**: Login and Registration APIs with JWT token authentication.
- **Event-Driven**: Includes an Express.js API, worker services, and EventBridge integration.

## Getting Started

### 1. Install dependencies

```bash
npm i -g serverless
npm install
```

### 2. Enable AWS Bedrock Models
Go to the AWS Console and request access to the Bedrock models you intend to use (e.g. `meta.llama3-70b-instruct-v1:0`).

### 3. Deploy
Ensure your AWS credentials are set up, then deploy the stack:

```bash
serverless deploy
```

Once deployed, follow the output URLs to access your API and Frontend services. For local development, run `npm run build` in the website directory after setting your API environment variables.

---
*For the complete architectural overview and production deployment instructions, please refer to the project documentation.*
