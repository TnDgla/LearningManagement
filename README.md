
---
# **Project Name: Udemy Clone**

**Udemy Clone** is a Fullstack Learning Management System (LMS) application designed to allow users to browse, purchase, and take online courses while providing admin functionalities for managing courses, users, and payments.

---

### **Mission and Objectives**

---

### **Mission:**
To build an interactive and responsive LMS platform that enables users to explore, purchase, and learn from a variety of online courses while providing admins with tools to manage content effectively.

---

### **Objectives:**
1. **User Authentication:**
   - Secure login and signup functionality using Redux and JWT.

2. **Admin Features:**
   - Tools to add, edit, and manage courses, including lectures and resources.

3. **Course Management:**
   - Enable users to purchase, access, and track their course progress.

4. **Payment Integration:**
   - Integrate Stripe for secure payment processing.

5. **Responsive Design:**
   - Ensure a seamless experience across devices.

---

### **Technology Stack**

#### **Frontend**
1. **React.js**
   - **Why?**: Simplifies building dynamic and interactive UIs.
   - **Use Case**: Handles the course pages, user dashboards, and admin interfaces.

2. **Shadcn UI**
   - **Why?**: Provides pre-designed, customizable UI components.
   - **Use Case**: Styles forms, buttons, and other elements.

3. **Redux Toolkit (RTK Query)**
   - **Why?**: Efficiently manages application-wide state.
   - **Use Case**: Handles authentication and API data fetching.

---

#### **Backend**
1. **Node.js**
   - **Why?**: Ensures scalable and efficient server-side operations.
   - **Use Case**: Manages APIs, authentication, and payment processing.

2. **Express.js**
   - **Why?**: Simplifies API development.
   - **Use Case**: Handles routes for users, courses, and payments.

3. **Multer & Cloudinary**
   - **Why?**: Facilitates media uploads and storage.
   - **Use Case**: Manages course thumbnails, video lectures, and other assets.

---

#### **Database**
1. **MongoDB**
   - **Why?**: Flexible schema design for managing courses, users, and transactions.
   - **Use Case**: Stores user profiles, course details, and payment records.

---

#### **Deployment**
1. **Frontend Hosting: Vercel or Netlify**
   - **Why?**: Optimized for React-based applications.
   - **Use Case**: Deploys the client-side application.

2. **Backend Hosting: Render or AWS**
   - **Why?**: Reliable platforms for backend services.
   - **Use Case**: Hosts APIs and database connections.

---

## **Workflow Overview**

The application workflow involves users browsing courses, purchasing desired ones via Stripe, and accessing learning materials through a responsive dashboard. Admins can manage courses, lectures, and track user progress.

### **FlowChart**

![image](https://github.com/user-attachments/assets/2f2a08ac-443e-4b2d-9057-45d96a248629)


---

### **Project Structure for Feature Implementation**
This project is structured to ensure a systematic and incremental development process. Each week builds upon the previous deliverables, enabling a smooth transition from basic to advanced functionalities.

**NOTE:** Participants are encouraged to customize the design and functionality to make the application unique.

---

## **Week-by-Week Learning Plan**

---

### **Week 1: Project Setup and UI Design**
- **Goal:** Set up the foundational structure and design the app UI.
- **Tasks:**
  1. Initialize the project with React.js, Vite, and Tailwind CSS.
     - **Reading:** [React.js Documentation](https://react.dev/blog/2023/03/16/introducing-react-dev)
     - **Video:** [React.js Crash Course](https://www.youtube.com/watch?v=w7ejDZ8SWv8)
  2. Configure Shadcn UI for pre-built components.
     - **Reading:** [Shadcn UI Docs](https://ui.shadcn.com/docs)
     - **Video:** [Shadcn Components Tutorial](https://www.youtube.com/watch?v=O4AjymzpIEg)
  3. Build login and signup pages.
     - **Reading:** [React Forms](https://react.dev/reference/react-dom/components/form)
     - **Video:** [Building Forms in React](https://www.youtube.com/watch?v=SdzMBWT2CDQ)

- **Deliverables:**
  - Fully responsive UI with login and signup functionality.

---

### **Week 2: Backend Setup**
- **Goal:** Set up the server and implement basic backend functionalities.
- **Tasks:**
  1. Set up a Node.js and Express.js server.
     - **Reading:** [Express.js Basics](https://expressjs.com/)
     - **Video:** [Express Server Setup](https://www.youtube.com/watch?v=L72fhGm1tfE)
  2. Design user schemas with Mongoose.
     - **Reading:** [MongoDB Schema Design](https://mongoosejs.com/docs/guide.html)
     - **Video:** [MongoDB Models](https://www.youtube.com/watch?v=DZBGEVgL2eE)
  3. Configure JWT-based authentication.
     - **Reading:** [JWT Basics](https://jwt.io/introduction/)
     - **Video:** [JWT Authentication Guide](https://www.youtube.com/watch?v=mbsmsi7l3r4)

- **Deliverables:**
  - Functional backend with user authentication APIs.

---

### **Week 3: Course Management**
- **Goal:** Implement course creation and management functionalities.
- **Tasks:**
  1. Set up Multer and Cloudinary for media uploads.
     - **Reading:** [Cloudinary Documentation](https://cloudinary.com/documentation)
     - **Video:** [Multer & Cloudinary Setup](https://www.youtube.com/watch?v=GML8Mw449O4)
  2. Build APIs for adding, editing, and deleting courses.
     - **Reading:** [RESTful API Design](https://restfulapi.net/)
     - **Video:** [Building REST APIs](https://www.youtube.com/watch?v=pKd0Rpw7O48)
  3. Create React pages for course listing and details.
     - **Reading:** [React State Management](https://react.dev/learn/managing-state)
     - **Video:** [React Components & State](https://www.youtube.com/watch?v=sbUPRl7rR3A)

- **Deliverables:**
  - Admin dashboard for managing courses.

---

### **Week 4: Payment Integration**
- **Goal:** Integrate Stripe for course payments.
- **Tasks:**
  1. Set up Stripe for payment processing.
     - **Reading:** [Stripe API Documentation](https://stripe.com/docs)
     - **Video:** [Stripe Integration Guide](https://www.youtube.com/watch?v=volAze3fpt0)
  2. Create APIs for payment and webhook handling.
     - **Reading:** [Webhook Basics](https://stripe.com/docs/webhooks)
     - **Video:** [Handling Webhooks](https://www.youtube.com/watch?v=VsRwIRKAe3Q)

- **Deliverables:**
  - Functional payment system with secure transactions.

---

### **Week 5: Deployment and Testing**
- **Goal:** Deploy the application and test all functionalities.
- **Tasks:**
  1. Deploy the frontend to Vercel.
     - **Reading:** [Vercel Deployment Guide](https://vercel.com/docs)
     - **Video:** [Deploying React Apps](https://www.youtube.com/watch?v=2LhoCfjm8R4)
  2. Deploy the backend to Render.
     - **Reading:** [Render Documentation](https://render.com/docs)
     - **Video:** [Deploying Node.js Apps](https://www.youtube.com/watch?v=l134cBAJCuc)

- **Deliverables:**
  - Fully deployed and functional Udemy Clone app.

---
### Screenshots
![Screenshot (425)](https://github.com/user-attachments/assets/f0f74a0a-1ef7-4c1c-825c-9be854d623a9)
![Screenshot (426)](https://github.com/user-attachments/assets/51bad050-a956-4faf-b8ca-4144aa3882f0)
![Screenshot (418)](https://github.com/user-attachments/assets/c6d58118-0b73-4454-901a-0ffded956063)
![Screenshot (419)](https://github.com/user-attachments/assets/f14807cb-a509-439e-aed6-dd4c09bc0d95)
![Screenshot (420)](https://github.com/user-attachments/assets/fb043562-c5ec-45e0-92e2-5486f1a44c0e)
![Screenshot (421)](https://github.com/user-attachments/assets/d90d7cad-a31c-4ce0-8f4a-aa78a247de16)
![Screenshot (422)](https://github.com/user-attachments/assets/5b65aa27-6fe5-4fd5-b351-1b01985a2fba)
![Screenshot (423)](https://github.com/user-attachments/assets/15ffd83f-7137-4ca7-b45e-622de61f1569)
![Screenshot (424)](https://github.com/user-attachments/assets/d8eef700-a1a9-41ca-a502-80f3438fa1b4)

---

### **References**
1. [React Documentation](https://reactjs.org/docs/getting-started.html)
2. [MongoDB Documentation](https://www.mongodb.com/docs/manual/)
3. [Cloudinary Documentation](https://cloudinary.com/documentation/)
4. [Stripe API Docs](https://stripe.com/docs/)
5. https://www.youtube.com/watch?v=JMvWrx_rLw4
6. https://github.com/Surendrakumarpatel/lms_patelmernstack

