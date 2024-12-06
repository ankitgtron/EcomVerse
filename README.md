# React Ecommerce App

Build a FULLSTACK React Ecommerce App that is fully Responsive with Stripe Payment

Video: https://www.youtube.com/watch?v=EBCdyQ_HFMo

For all related questions and discussions about this project, check out the discord: https://discord.gg/2FfPeEk2mX

Certainly! Here's the updated **week-by-week plan** with **tasks** and the relevant **reading** and **video resources** included directly beneath each task to make it easy for students to follow along.

---

---


### **Week 1: Project Setup and Basic UI**
**Goal**: Set up the environment and create the basic structure of the app.


**Week-1 Task:**
1. **Install Node.js, npm, and VSCode**:
   - Install the latest version of **Node.js** and **npm**.
   - Install **VSCode** as your development environment.
   
   **Reading Material**:  
   - [Node.js Installation](https://nodejs.org/en/download/)
   - [VSCode Installation Guide](https://code.visualstudio.com/docs/setup/setup-overview)
   
   **Video Tutorial**:  
   - [How to Install Node.js and VSCode](https://www.youtube.com/watch?v=HfM1SJJszU4)

2. **Create a New React Project**:
   - Use the `npx create-react-app` command to initialize a new React project.
   - Set up the basic folder structure for your project (components, pages, redux, etc.).

   **Reading Material**:  
   - [React Quick Start Guide](https://react.dev/learn)  
   
   **Video Tutorial**:  
   - [React Setup and Structure](https://www.youtube.com/watch?v=RGKi6LSPDLU)  

3. **Set Up Strapi Backend**:
   - Create the Strapi backend using `npx create-strapi-app@latest server`.
   - Set up your Strapi collections for **products** and **orders**.

   **Reading Material**:  
   - [Strapi Quickstart Guide](https://docs.strapi.io/developer-docs/latest/getting-started/quick-start.html)  
   
   **Video Tutorial**:  
   - [Getting Started with Strapi](https://www.youtube.com/watch?v=6FnwAbd2SDY)  

4. **Install Dependencies for Frontend**:
   - Install Material UI, React Router, and Redux Toolkit.

   **Reading Material**:  
   - [Material UI Installation](https://mui.com/material-ui/getting-started/installation/)  
   - [React Router Documentation](https://reactrouter.com/web/guides/quick-start)  
   - [Redux Toolkit Documentation](https://redux-toolkit.js.org/introduction/getting-started)

   **Video Tutorial**:  
   - [Material UI Basics](https://www.youtube.com/watch?v=Xoz31I1FuiY)  
   - [React Router Setup](https://www.youtube.com/watch?v=Law7wfdg_ls)  
   - [Redux Toolkit Setup](https://www.youtube.com/watch?v=93p3LxR9xfM)
   
**Week 1 Deliverables**:
   - A basic React app setup with Strapi backend.
   - Installed dependencies (Material UI, Redux, React Router).
   - Basic folder structure (components, pages, redux, etc.).

---

### **Week 2: Product Management and Display**
**Goal**: Fetch and display products on the frontend.

**Week-2 Task:**

1. **Populate Strapi with Product Data**:
   - Define product fields like `name`, `price`, `category`, and `description`.
   - Populate sample product data using Strapi's admin panel.

   **Reading Material**:  
   - [Strapi Content Types](https://docs.strapi.io/user-docs/content-type-builder)

   **Video Tutorial**:  
   - [Strapi Content Types](https://www.youtube.com/watch?v=aqJI-lY6bbk)

2. **Fetch Product Data Using Axios**:
   - Use Axios to fetch product data from Strapi and display it in the React app.

   **Reading Material**:  
   - [Axios Documentation](https://axios-http.com/docs/intro)

   **Video Tutorial**:  
   - [React Axios Tutorial](https://www.youtube.com/watch?v=Gl-vOU7ZU9A)

3. **Create Product Listing and Details Pages**:
   - Build the **Product Listing Page** for displaying products fetched from Strapi.
   - Create a **Product Details Page** to show individual product information.

   **Reading Material**:  
   - [React Components](https://react.dev/learn/your-first-component)  
   - [Material UI Cards](https://mui.com/material-ui/react-card/)

   **Video Tutorial**:  
   - [Material UI Cards](https://www.youtube.com/watch?v=Xoz31I1FuiY&t=16s)

**Week 2 Deliverables**:
   - A functional product listing page with data from Strapi.
   - Product details page with individual product information.

---

### **Week 3: Cart and State Management with Redux**
**Goal**: Add cart functionality using Redux Toolkit.

**Week 3 Task**

1. **Setup Redux**:
   - Install **Redux Toolkit** and **React-Redux**.
   - Create a **Redux slice** for cart state management.

   **Reading Material**:  
   - [Redux Toolkit Documentation](https://redux-toolkit.js.org/introduction/getting-started)

   **Video Tutorial**:  
   - [Redux Toolkit Crash Course](https://www.youtube.com/watch?v=93p3LxR9xfM)

2. **Build the Cart Sidebar**:
   - Design the cart sidebar using **Material UI Drawer**.

   **Reading Material**:  
   - [Material UI Drawer Component](https://mui.com/material-ui/react-drawer/)

   **Video Tutorial**:  
   - [Material UI Drawer Tutorial](https://www.youtube.com/watch?v=Ix1LZGBSp-E)

3. **Connect Redux State with the UI**:
   - Use Redux state to manage cart data and display it dynamically.

   **Reading Material**:  
   - [Redux Tutorial for Beginners](https://react-redux.js.org/introduction/getting-started)

   **Video Tutorial**:  
   - [Connecting Redux to React](https://www.youtube.com/watch?v=93p3LxR9xfM)

**Week 3 Deliverables**:
   - A cart system with add/remove features.
   - Cart sidebar using Material UI Drawer.

---

### **Week 4: Checkout and Stripe Payment Integration**
**Goal**: Implement checkout functionality and integrate Stripe payments.

**Week 4 Task**
1. **Build the Checkout Form**:
   - Use **Formik** for form handling and **Yup** for validation.
   - Collect user details like name, address, and payment information.

   **Reading Material**:  
   - [Formik Documentation](https://formik.org/docs/overview)  
   - [Yup Validation Guide](https://github.com/jquense/yup)

   **Video Tutorial**:  
   - [Formik and Yup Tutorial](https://www.youtube.com/watch?v=7Ophfq0lEAY)

2. **Setup Stripe Payment**:
   - Integrate **Stripe API** in the backend for payment processing.

   **Reading Material**:  
   - [Stripe Payment API Docs](https://stripe.com/docs/payments/integration-builder)

   **Video Tutorial**:  
   - [Stripe Integration with React](https://www.youtube.com/watch?v=3OOHC_UzrKA)

3. **Connect Frontend and Backend for Payment**:
   - Connect the frontend **checkout form** with the backend **Stripe API** to process payments.

   **Reading Material**:  
   - [Stripe Checkout API Guide](https://stripe.com/docs/payments/checkout)

   **Video Tutorial**:  
   - [Stripe API and Checkout](https://www.youtube.com/watch?v=volAze3fpt0)

**Week 4 Deliverables**:
   - Functional checkout page with Stripe integration.
   - Payment processing handled by Stripe.

---

### **Week 5: User Authentication and Admin Panel**
**Goal**: Implement user authentication and build an admin dashboard.

**Week 5 Task**
1. **Setup User Authentication**:
   - Use **Strapi Authentication** for user login and registration.
   - Protect routes using **React Router**.

   **Reading Material**:  
   - [Strapi Authentication Documentation](https://docs.strapi.io/developer-docs/latest/guides/auth-request.html)  
   - [React Router Protected Routes](https://reactrouter.com/en/main/start/tutorial)

   **Video Tutorial**:  
   - [Strapi Authentication](https://www.youtube.com/watch?v=lbEFSP1WAv0)  
   - [React Protected Routes](https://www.youtube.com/watch?v=iM9G0lgXsc4)

2. **Create Admin Dashboard**:
   - Build an **Admin Panel** using Material UI Table to manage products, orders, and view user activity.

   **Reading Material**:  
   - [Material UI Table Docs](https://mui.com/material-ui/react-table/)

   **Video Tutorial**:  
   - [Admin Dashboard with Material UI](https://www.youtube.com/watch?v=wYpCWwD1oz0)

**Week 5 Deliverables**:
   - A secure login/signup system.
   - Admin panel to manage products, orders, and users.

---

### **Week 6: Final Testing and Deployment**
**Goal**: Test the app thoroughly and deploy it.

**Week 6: Task**

1. **Testing the App**:
   - Use **Postman** to test backend APIs and simulate payment requests.
   - Test the frontend using **React Testing Library** or **Jest**.

   **Reading Material**:  
   - [Postman API Testing](https://learning.postman.com/docs/getting-started/introduction/)  
   - [Jest Testing Guide](https://jestjs.io/docs/getting)

**Video Tutorial:**
- [React Testing](https://www.youtube.com/watch?v=8Xwq35cPwYg)
- [React Deploy](https://www.youtube.com/watch?v=dg2Gw1HSlpQ)

**The End**
