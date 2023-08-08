---
sidebar_position: 2
---

## Configure development environment

You will need multiple environment variables in order to work with the root system.So first create a <code>.env</code>file in your root directory of the project.

**Here is a example <code>.env</code>file;**

```yaml
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/dashboard
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/dashboard

OPENAI_API_KEY=
REPLICATE_API_TOKEN=

PINECONE_API_KEY=
PINECONE_ENVIRONMENT=
PINECONE_INDEX=

UPSTASH_REDIS_REST_URL=
UPSTASH_REDIS_REST_TOKEN=

NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=

DATABASE_URL=

STRIPE_API_KEY=
STRIPE_WEBHOOK_SECRET=

NEXT_PUBLIC_APP_URL="http://localhost:3000"

```
and place your variables inside their. 

:::danger Don't expose to public

Remember to add this file to the <code>.gitignore</code> to not dispose it to github or any vcs provider of yours!

:::

**After configuring, You are ready to go with the project and modify it!**