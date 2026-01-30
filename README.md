# Install tools
  - pip install -r requirements.txt
   - uvicorn main:app --reload

# Car Performance Optimization System 🚗⚙️

Backend system for managing car data and performance specifications, built with **FastAPI** and designed using a scalable, modular architecture.

The project focuses on real-world backend development practices such as authentication, data modeling, clean architecture, and API security.

---

## 🚀 Features

- REST API with **20+ endpoints**
- User authentication and authorization using **JWT**
- Role-based access (user / admin)
- CRUD operations for:
  - Users
  - Cars
  - Performance specifications
- Input validation using **Pydantic**
- Clean, modular backend architecture
- Ready for future extensions (analytics, optimization algorithms, AI models)

---

## 🛠 Tech Stack

- **Python**
- **FastAPI**
- **PostgreSQL**
- **SQLAlchemy (ORM)**
- **Pydantic**
- **JWT Authentication**

---

## 📁 Project Structure

```bash
app/
 ├── routers/        # API routes
 ├── models/         # Database models
 ├── schemas/        # Pydantic schemas
 ├── services/       # Business logic
 ├── core/           # Config, security, JWT utils
 └── database.py     # Database connection
main.py              # Application entry point
requirements.txt

▶️ How to Run the Project
1. Clone the repository
git clone https://github.com/AleZ98/car-performance-optimization-system.git
cd car-performance-optimization-system

2. Create virtual environment & install dependencies
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
pip install -r requirements.txt

3. Run the server
uvicorn main:app --reload

4. Open API documentation

Swagger UI: http://127.0.0.1:8000/docs

ReDoc: http://127.0.0.1:8000/redoc



## Hi, I'm Alex 👋

Junior Python Backend Developer focused on FastAPI and AI systems.

🔹 Python | FastAPI | PostgreSQL  
🔹 REST APIs | JWT Authentication  
🔹 AI & Machine Learning integration  

📫 LinkedIn: https://www.linkedin.com/in/petcu-alexandru-56744b395/

