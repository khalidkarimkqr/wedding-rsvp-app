# Full Stack RSVP App

![App Preview](.images/yee987.png)

## Technologies used

- [Next.js](https://nextjs.org/)
- [Supabase](https://supabase.com/)
- [Resend](https://resend.com)
- [Shadcn](https://ui.shadcn.com/)
  
## Getting started

First, add your ENV's to `.env.local` file:

```bash
NEXT_PUBLIC_SUPABASE_URL=your-project-url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your-anon-key/api-key
RESEND_API_KEY=your-resend-api-key
EMAIL_TO=email where you'll receive notifications. It needs to be the email you used to create the API key in Resend.
```
Then, install the dependencies:
  
```bash
npm install
# or
yarn install
# or
pnpm install
# or
bun install
```

Run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

## Supabase

### Add User

- Go to your Supabase account
- `Authentication`
- `Add user` and create your admin user

### Create `rsvps` Table

<img width="672" alt="Screenshot 2024-12-29 at 10 22 54" src="https://github.com/user-attachments/assets/3678b526-1717-42b0-9ce1-71100ad02bfe" />

#### Set Email to be **unique field**

<img width="606" alt="Screenshot 2024-12-29 at 10 23 39" src="https://github.com/user-attachments/assets/c2f647f2-db82-4a0c-a950-08245482b87c" />

### Add Row Level Security Policies

#### Allow anonymous inserts
<img width="548" alt="Screenshot 2024-12-29 at 10 32 46" src="https://github.com/user-attachments/assets/bba99603-73c4-446b-8255-497d38aeae87" />

#### Owner access
<img width="550" alt="Screenshot 2024-12-29 at 10 35 49" src="https://github.com/user-attachments/assets/788ac00a-ea3d-4c11-9be2-e2bf0198f499" />


Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Deploy on Vercel


