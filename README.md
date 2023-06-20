# Airbnb Clone

This project is a full-stack clone of Airbnb, developed exclusively for educational purposes. It replicates the core features of the Airbnb platform, providing users with an immersive experience of searching and booking accommodations. By utilizing Next.js, a popular React framework, this project offers a seamless and responsive user interface. The frontend incorporates modern design principles and user-friendly components, while the backend implements essential functionalities such as user authentication, property listing, search filters, and booking management. This project serves as an excellent learning resource for developers interested in building real-world web applications, as it showcases the implementation of complex features commonly found in popular online marketplaces like Airbnb.

## Demo
```
https://aircloneb.vercel.app/
```

## Technologies Used


**Typescript:** The project is developed using TypeScript, a statically typed superset of JavaScript that enhances tooling and provides type safety.

**NextAuth:** NextAuth is utilized for authentication, making it easy to implement secure user authentication flows in the project.

**Node.js:** Node.js is used as the backend runtime environment, allowing server-side JavaScript execution and providing a scalable and efficient server foundation.

**Next.js:** Next.js, a framework built on top of React, is used for server-side rendering (SSR) and creating optimized web applications.

**React.js:** The UI components are built using React.js, a popular JavaScript library for building user interfaces.

**Axios:** Axios is used as an HTTP client for making API requests to external services and fetching data.

**Cloudinary:** Cloudinary is employed for managing and optimizing images in the project, providing seamless image upload, storage, and transformation capabilities.

**MongoDB:** MongoDB is a powerful NoSQL database with a flexible schema, JSON-like data format, and high scalability, making it suitable for modern web applications.

**Prisma:** Prisma is utilized as an ORM (Object-Relational Mapping) tool, providing a type-safe and database-agnostic query interface for seamless integration with databases.

## Prerequisites

```
- Node.js (version 14.x)
```

Make sure you have Node.js installed by running the following command in the terminal:
```
node --version
```

## Cloning the repository

```
git@github.com:talescarneiro/airbnb-clone-app.git
```

## Install packages

```
npm install
```

## Setup .env file

```
DATABASE_URL=
NEXTAUTH_SECRET="NEXTAUTH_SECRET"

GITHUB_ID=
GITHUB_SECRET=

GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=

NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=
```

## Setup Prisma

```
npx prisma db push
```

## Run the application

```
npm run dev
```
