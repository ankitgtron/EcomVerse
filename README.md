# React Ecommerce App

# EcomVerse: Build Your E-Commerce Website
EcomVerse is a modern, fully functional e-commerce platform designed to provide users with a seamless online shopping experience. Utilizing React for the frontend, Strapi for the backend, Redux Toolkit for state management, and Stripe for secure payments, this project empowers developers to create an efficient, responsive, and user-friendly platform.

From product listing and shopping cart functionality to secure checkout and admin management, EcomVerse guides participants step-by-step to build an e-commerce platform while mastering essential full-stack development skills.

# Mission and Objectives
## Goal:
By the end of the course, participants will have developed a complete e-commerce application with essential features and professional design using modern full-stack technologies.

## Objectives:
- Provide a clear learning path for building e-commerce applications.
- Cover core functionalities such as product management, user authentication, shopping cart, and payment gateway integration.
- Equip participants with knowledge of deploying and maintaining web applications.
- Incorporate scalable technologies and best practices for creating responsive and secure e-commerce platforms.

# Technology Stack

<img width="419" alt="image" src="https://github.com/user-attachments/assets/eac4e4fd-62ae-4cce-aa7d-fe21c216b64a">

# Project Structure for Feature Implementation
This project is structured to ensure a systematic and incremental development process. Each week builds upon the previous deliverables, enabling a smooth transition from basic functionalities to advanced features.

---

**NOTE:**
Participants are encouraged to customize the user interface and incorporate additional features into the application. These modifications allow participants to demonstrate creativity, improve usability, and enhance the functionality of the project. Such enhancements align with the project’s objective of fostering innovative thinking while providing a personalized learning experience.


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

**Week 6 Deliverables**
   - Deploy the complete working ecommerce website.
   - Create a demonstration video of functionality of your ecommerce website

**Screenshots are added for your preference**
![Screenshot (95)](https://github.com/user-attachments/assets/489c54da-6210-426f-a7c9-01b456aa6254)
![Screenshot 2024-12-06 170309](https://github.com/user-attachments/assets/6f8f565b-ec0c-49f7-a081-63e8985e3003)
![Screenshot (88)](https://github.com/user-attachments/assets/eb793b7c-8bba-4c5f-983b-795aa1a20060)
![Screenshot (89)](https://github.com/user-attachments/assets/d480ad7e-2fa4-47b8-9b21-870a23e9a480)
![Screenshot (90)](https://github.com/user-attachments/assets/9aa6342b-3b14-4462-bfc4-21c22ee067de)
![Screenshot (91)](https://github.com/user-attachments/assets/55568305-47fe-42f4-9760-7654c51a79d9)
![Screenshot (92)](https://github.com/user-attachments/assets/2ec25ee4-db6c-41f1-8ee1-fbf39b60078b)
![Screenshot (92)](https://github.com/user-attachments/assets/f21fe405-be0c-4020-a4ef-2eadb351f4b0)
![Screenshot (94)](https://github.com/user-attachments/assets/e4e7f69e-fa4e-4cde-8569-9a0d572bb40a)
![Screenshot (95)](https://github.com/user-attachments/assets/7d4b857c-8a9e-49bf-8876-7a531edbc18b)
![Screenshot (96)](https://github.com/user-attachments/assets/37c108ce-a08d-470c-8cb9-0855b477e521)


**The End**
