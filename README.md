# MySpace Clone

MySpace Clone is a startup project built with Next.js, Prisma, and managed using pnpm. This project aims to explore the capabilities of Next.js for building web applications and Prisma for database operations.

## Getting Started

### Prerequisites

Make sure you have the following tools installed on your machine:

- [Node.js](https://nodejs.org/)
- [pnpm](https://pnpm.io/) (to install it globally, run `npm install -g pnpm`)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/myspace-clone.git


2. Navigate to the project directory:
    
    ```bash
    cd myspace-clone
3. Install dependencies using pnpm:

    ```bash
    pnpm install

### Development
To run the development server:

    pnpm dev

Open http://localhost:3000 in your browser to view the app.


### Database Setup

1. Ensure you have a running database (e.g., PostgreSQL).

2. Configure your database connection in the .env file (rename .env.example file):

    ```
    GITHUB_ID=
    GITHUB_SECRET=
    NEXTAUTH_SECRET=
    DATABASE_URL=
    SHADOW_DATABASE_URL=


3. Run Prisma migrations:
    
    ```bash
    npx prisma init
    pnpm prisma migrate dev
    
### Usage

Explore and modify the Next.js pages in the pages directory.
Utilize Prisma for database operations. Refer to the Prisma documentation for guidance.


### Deployment
Deploy your app to your preferred hosting platform. For example, Vercel, Netlify, or your own server.