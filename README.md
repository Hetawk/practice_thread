# Building and Deploying a Full Stack MERN Next.js 13 Threads App | React, Next JS, TypeScript, MongoDB with JavaScript Mastery
![Threads](https://github.com/Hetawk/practice_thread/blob/master/practice.jpg)


## Getting Started
To download the repo and run the Next.js app, follow these steps:

1. Clone the repo:
`git clone https://github.com/Hetawk/practice_thread.git`

2. Install the dependencies:
`npm install`
4. Create a .env.local file in the root directory of the project and add the following environment variables:
- NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
- CLERK_SECRET_KEY=
- NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
- NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
- NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
- NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/
- MONGODB_URL=
- UPLOADTHING_SECRET=
- UPLOADTHING_APP_ID=
- NEXT_CLERK_WEBHOOK_SECRET=

4. Start the development server:
   The app will now be running on http://localhost:3000.

Environment Variables
The following environment variables are required to run the app:
```
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=Your Clerk publishable key
CLERK_SECRET_KEY=Your Clerk secret key
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/
MONGODB_URL=Your MongoDB connection URL
UPLOADTHING_SECRET=Your UploadThing secret key
UPLOADTHING_APP_ID=Your UploadThing app ID.
NEXT_CLERK_WEBHOOK_SECRET=Next Clerk webhook secret
```
You can obtain these values from your respective accounts.

### Deployment
You can deploy the app to Vercel or any other Next.js hosting provider.
To deploy to Vercel, follow these steps:

1. Go to Vercel and create a new project.
2. Select "Next.js" as the framework.
3. Connect your GitHub account and select the practice_thread repository or whatever name you will call your repo.
4. Click "Deploy".
5. Vercel will automatically build and deploy the app. Once the deployment is complete, you will be able to access the app at the URL provided by Vercel.


### Summary of app features:
- Performing Next.js 13.4 operations with Server Side Rendering
- Handling MongoDB complex schemas, multiple data population
- Creating beautiful layouts with TailwindCSS
- Using Clerk for authentication
- Handling file uploads with UploadThing
- Exploring Shadcn components
- Listening to real-time events with webhooks
- Understanding middleware, API actions, and authorization
- Exploring & integrating new Next.js layout route groups
- Validating data with Zod
- Managing forms with react hook form
- Creating reusable components

