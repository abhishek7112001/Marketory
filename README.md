# <img src="./src/app/favicon.ico" width="30"> Marketory</img>

Welcome to **Marketory**, an e-commerce website with an admin panel designed to facilitate online purchases of Products. This project utilizes modern technologies such as **Next.js**, **Javascript**, **Prisma**, **MongoDB**, **Iron-Session**, **shadcn** and **Stripe** for seamless integration and robust functionality.

<!-- ![Thumbnail](/marketory.png) -->

## Features

- **User-friendly Interface**: Marketory provides an intuitive interface for users to browse and purchase products conveniently.
- **Admin Panel**: A powerful admin panel is included for managing products, orders, and user data efficiently.
- **Secure Payment Processing**: Integration with Stripe ensures secure and seamless payment processing for a smooth checkout experience.
- **Dynamic Content Rendering**: Next.js is employed for server-side rendering, enabling dynamic content generation and improved performance.
- **Scalable Backend**: MongoDB is used as the database backend, offering scalability and flexibility for managing data.

## <a name="tech-stack">Tech Stack</a>

- Next.js
- MongoDB
- Javascript
- iron-session
- Primsa
- Stripe
- Shadcn
- Tailwind CSS

## <a name="quick-start">Integration and Installation Process</a>

Follow these steps to set up the project locally on your device.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/)
- [Git](https://git-scm.com/)

To get started with **Marketory**, follow these steps:

1. **Clone the Repository**:
    ```shell
    git clone https://github.com/prashant-sagar-shakya/marketory.git
    ```
2. **Install Dependencies**:
    ```shell
    cd marketory
    npm install
    ```
3. **Start the Development Server**:
    ```shell
    npm run dev
    ```
4. **Access the Website**: Open your browser and navigate to `http://localhost:3000` to access the website.

5. **Set Up Environment Variables**: Create a new file named `.env` in the root of your project and add the following content:

    ```env
    NEXT_PUBLIC_SECRET_KEY=sdfdsfsdbvsdjvhbsjfdsbfjsd54354353453dsfsfs
    NODE_ENV="development"
    DATABASE_URL=""

    UPLOADTHING_SECRET=
    UPLOADTHING_APP_ID=

    NEXT_PUBLIC_CHARACTERS="dfbhsdufsbvdefhfbdjhb"


    SMTP_EMAIL=
    SMTP_PASS=

    STRIPE_SECRET_KEY=""
    NEXT_PUBLIC_FRONTEND_URL=http://localhost:3000
    ```
## <a name="contribution">Contribution</a>
Contributions are welcome, Happy Coding !!!