# Civic Reporting Portal

A full-stack web application that enables citizens to report local civic issues with images and location details.  
Authorities can view submitted reports, track their progress, and update status fields through a role-based access system.

**Live Demo:** [https://your-live-site-link](https://saurav-citycare.netlify.app/)  
> Since the backend is hosted on Render (free tier), it may take up to a minute to spin up after inactivity.

---

### 🧩 Tech Stack
**Backend:** Spring Boot (Java), MySQL, Supabase  
**Frontend:** React, Tailwind CSS, Leaflet (private repo)  
**Deployment:** Dockerized backend on Render, frontend on Netlify  

---

### 🚀 Features
- Citizens can report civic issues with title, description, images, and location data.  
- Role-based access for authorities to view, filter, and manage issue statuses.  
- Integrated interactive maps using **Leaflet** for visualizing report locations.  
- Image uploads handled via **Supabase storage**.  
- Secure environment-based configuration for credentials.  
- Dockerized and deployed using a CI/CD workflow.  

---

### 🧪 Test Credentials
When a new user signs up, the **Citizen** role is assigned by default.  
To explore other roles, use the credentials below:

| Role | Email | Password |
|------|--------|-----------|
| Authority | *authority@test.com* | *12345678* |
| Super Admin | *admin@test.com* | *12345678* |

> These demo accounts allow testing of different dashboard views and status management features.

---

### 🖼️ Screenshots

> *Note: The UI is intentionally kept simple to focus on backend functionality and deployment.*
<img width="1920" height="914" alt="image" src="https://github.com/user-attachments/assets/fb755078-8ec3-493d-87ab-681fdd4950a4" />
<img width="1916" height="917" alt="image" src="https://github.com/user-attachments/assets/12d0d54d-44ce-415d-81c0-bf3597ffa32a" />
<img width="1920" height="918" alt="image" src="https://github.com/user-attachments/assets/51f8ad81-bcd1-4ea3-8ec2-6b949d074de1" />
<img width="1907" height="908" alt="image" src="https://github.com/user-attachments/assets/588edc08-304c-4871-bbaf-41ca77c06528" />
<img width="1920" height="912" alt="image" src="https://github.com/user-attachments/assets/92810edb-79a5-4297-b1a2-cc1b9c1f2971" />
<img width="1920" height="927" alt="image" src="https://github.com/user-attachments/assets/2bc49fa1-241e-4c84-acfe-7d37aa60dae1" />
<img width="1919" height="915" alt="image" src="https://github.com/user-attachments/assets/fe40927c-d0f3-423d-9794-94209ac0c621" />
<img width="1916" height="917" alt="image" src="https://github.com/user-attachments/assets/eb9b3c64-c84b-4a4c-a4c0-68d6ea16acb9" />
<img width="1918" height="918" alt="image" src="https://github.com/user-attachments/assets/f6c4a49d-7cb5-47ce-990c-3aa286b3d40c" />



---

### 🔮 Future Scope
- Allow authorities to take direct actions or communicate with reporters.  
- Real-time notifications for new reports and updates.  
- City-wide analytics dashboard.  
- Enhanced UI and responsive design.

---
