<div align="center">

  <h2 align="center">Full Stack Event Management App</h2>

   <div align="center">
     <h4>This is a full-stack event management application built using the MERN stack and Next.js framework. The application allows users to create, manage, and view events.
Featuring seamless payment processing through Stripe, you have the capability to purchase tickets for any event or even initiate and manage your own events.</h4>
    </div>
    <br>

<div>
    <img src="https://img.shields.io/badge/-Next_JS_15-black?style=for-the-badge&logoColor=white&logo=nextdotjs&color=000000" alt="Next.js" />
    <img src="https://img.shields.io/badge/-TypeScript-black?style=for-the-badge&logoColor=white&logo=typescript&color=3178C6" alt="TypeScript" />
    <img src="https://img.shields.io/badge/-Stripe-black?style=for-the-badge&logoColor=white&logo=stripe&color=008CDD" alt="stripe" />
    </div>

</div>

<br>

## 📋 <a name="table">Table of Contents</a>

1. ⚙️ [Tech Stack](#tech-stack)
2. 🔋 [Features](#features)
3. 🕸️ [Quick Start](#quick-start)
5. 🔗 [Links](#links)

## <a name="tech-stack">⚙️ Tech Stack</a>


- **Node.js**
- **Next.js**
- **TypeScript**
- **TailwindCSS**
- **Stripe**
- **Zod**
- **React Hook Form**
- **Shadcn**
- **uploadthing**

## <a name="features">🔋 Features</a>

⚡️ **Authentication (CRUD) with Clerk:** User management through Clerk, ensuring secure and efficient authentication.

⚡️ **Events (CRUD):** Comprehensive functionality for creating, reading, updating, and deleting events, giving users full control over event management.
- **Create Events:** Users can effortlessly generate new events, providing essential details such as title, date, location, and any additional information.
- **Read Events:** Seamless access to a detailed view of all events, allowing users to explore event specifics, including descriptions, schedules, and related information.
- **Update Events:** Empowering users to modify event details dynamically, ensuring that event information remains accurate and up-to-date.
- **Delete Events:** A straightforward process for removing events from the system, giving administrators the ability to manage and curate the platform effectively.
        
⚡️ **Related Events:** Smartly connects events that are related and displaying on the event details page, making it more engaging for users
    
⚡️ **Organized Events:** Efficient organization of events, ensuring a structured and user-friendly display for the audience, i.e., showing events created by the user on the user profile
    
⚡️ **Search & Filter:** Empowering users with a robust search and filter system, enabling them to easily find the events that match their preferences.
    
⚡️ **New Category:** Dynamic categorization allows for the seamless addition of new event categories, keeping your platform adaptable.
    
⚡️ **Checkout and Pay with Stripe:** Smooth and secure payment transactions using Stripe, enhancing user experience during the checkout process.
    
⚡️ **Event Orders:** Comprehensive order management system, providing a clear overview of all event-related transactions.
    
⚡️ **Search Orders:** Quick and efficient search functionality for orders, facilitating easy tracking and management.

...and many more, including code architecture and reusability 

<br>

## <a name="quick-start">🕸️ Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)


**Cloning the Repository**

```bash
git clone https://github.com/your-username/your-project.git
cd your-project
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env` in the root of your project and add the following content:

```env
#NEXT
NEXT_PUBLIC_SERVER_URL=

#CLERK
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_CLERK_WEBHOOK_SECRET=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

#MONGODB
MONGODB_URI=

#UPLOADTHING
UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=

#STRIPE
STRIPE_SECRET_KEY=
STRIPE_WEBHOOK_SECRET=
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=
```

Replace the placeholder values with your actual credentials

**Running the Project**

```bash
npm start
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.

<br>

## <a name="links">🔗 Links</a>

- [Clerk Authentication](https://clerk.com/) 

- [Next.js](https://nextjs.org/)

- [Stripe Payments](https://stripe.com/ie)

- [Shadcn](https://ui.shadcn.com/)

- [uploadthing](https://uploadthing.com/)