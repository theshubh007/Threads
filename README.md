  <h3 align="center">A full stack Threads Web</h3>
Threads is a cutting-edge community platform designed to enhance user interaction and engagement. It addresses the challenges of creating and managing dynamic online communities by providing a comprehensive set of features, including robust authentication, seamless thread creation, and structured commenting. With Threads, users can effortlessly explore and discover other users and communities through efficient search and pagination. Real-time notifications keep users informed about activity within their threads, while profile and community management tools allow for personalized experiences. The application leverages the latest web technologies to ensure optimal performance, data integrity, and a visually appealing user interface. Threads is the perfect solution for fostering vibrant, engaged online communities.

  ## <a name="tech-stack">⚙️ Tech Stack</a>

- Next.js
- MongoDB
- Shadcn UI
- TailwindCSS
- Clerk
- Webhooks
- Serverless APIs
- React Hook Form
- Zod
- TypeScript

## Features
- Authentication: Clerk offers email, password, and social logins (Google and GitHub) with profile management.
- Engaging UI: Home page showcases the latest threads; create threads and comment with nested replies.
- Search & Pagination: Explore users and communities easily with paginated search.
- Activity & Notifications: Get notifications on activities like comments on your threads.
- Profile & Community Management: Manage profiles, create/invite to communities, and handle member roles.
- Admin Features: Admins can create community-specific threads and manage members.
- Design & Performance: Pixel-perfect Figma design, blazing-fast performance, server-side rendering, and efficient routing.
- Data Handling: MongoDB for complex schemas, real-time updates with webhooks, file uploads, and data validation with Zod.

## Quick Start
### Step 1: 
clone the repo
``` git clone https://github.com/adrianhajdin/threads.git
cd threads
```

### Step 2:
Install the project dependencies using npm:
```
npm install
```

### Step 3:
Set Up Environment Variables
```
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=


NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

MONGODB_URL=""
```

### Step 4:
run the project
```
npm run dev
```
Open http://localhost:3000 in your browser to view the project.


![image](https://github.com/user-attachments/assets/a138ce73-c7c0-4c51-996d-05b70af91601)

![image](https://github.com/user-attachments/assets/78156234-057e-45c9-adff-bf6ed648125d)

