<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/9113740/201498864-2a900c64-d88f-4ed4-b5cf-770bcb57e1f5.png">
  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/9113740/201498152-b171abb8-9225-487a-821c-6ff49ee48579.png">
</picture>

<div align="center"><strong>Next.js 14 Admin Dashboard Starter Template With Shadcn-ui</strong></div>
<div align="center">Built with the Next.js App Router</div>
<br />
<div align="center">
<a href="https://next-shadcn-dashboard-starter.vercel.app">View Demo</a>
<span>
</div>

## Overview

This is a starter template using the following stack:

- Framework - [Next.js 14](https://nextjs.org/13)
- Language - [TypeScript](https://www.typescriptlang.org)
- Styling - [Tailwind CSS](https://tailwindcss.com)
- Components - [Shadcn-ui](https://ui.shadcn.com)
- Schema Validations - [Zod](https://zod.dev)
- State Management - [Zustand](https://zustand-demo.pmnd.rs)
- Auth - [Nextauth](https://next-auth.js.org)
- File Uploading - [Uploadthing](https://uploadthing.com)
- Tables - [Tanstack Tables](https://ui.shadcn.com/docs/components/data-table)
- Forms - [React Hook Form](https://ui.shadcn.com/docs/components/form)
- Linting - [ESLint](https://eslint.org)
- Formatting - [Prettier](https://prettier.io)

## Pages

| Pages                                                                             | Specifications                                                                                        |
| :-------------------------------------------------------------------------------- | :---------------------------------------------------------------------------------------------------- |
| [Signup](https://next-shadcn-dashboard-starter.vercel.app/)                       | Authentication with **NextAuth** supports Social logins and email logins(Enter dummy email for demo). |
| [Dashboard](https://next-shadcn-dashboard-starter.vercel.app/dashboard)           | Cards with recharts graphs for analytics.                                                             |
| [Users](https://next-shadcn-dashboard-starter.vercel.app/dashboard/user)          | Tanstack tables with user details client side searching, pagination etc                               |
| [Users/new](https://next-shadcn-dashboard-starter.vercel.app/dashboard/user/new)  | A User Form with Uploadthing to support file uploading with dropzone.                                 |
| [Employee](https://next-shadcn-dashboard-starter.vercel.app/dashboard/employee)   | Tanstack tables with server side searching, pagination etc).                                          |
| [Profile](https://next-shadcn-dashboard-starter.vercel.app/dashboard/profile)     | Mutistep dynamic forms using react-hook-form and zod for form validation.                             |
| [Kanban Board](https://next-shadcn-dashboard-starter.vercel.app/dashboard/kanban) | A Drag n Drop task management board with dnd-kit and zustand to persist state locally.                |
| [Not Found](https://next-shadcn-dashboard-starter.vercel.app/dashboard/notfound)  | Not Found Page Added in the root level                                                                |
| -                                                                                 | -                                                                                                     |

## Getting Started

Clone this repo

```
git clone https://github.com/Kiranism/next-shadcn-dashboard-starter
```

Create `.env` file like as `env.example.txt`

```
UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=
# Next auth 
NEXTAUTH_URL = http://localhost:3000
NEXTAUTH_SECRET= 
# get this from github developer settings 
GITHUB_ID = 
GITHUB_SECRET = 
```

Update your `NEXTAUTH_SECRET` in your `.env` file

Run the following commands to start the development server:

```
npm install
npm run dev
```

You should now be able to access the application at http://localhost:3000.
