# Sistema de Gestión de Créditos 



## Tecnologías Utilizadas
* **Backend:** Python / Django REST Framework
* **Frontend:** React (Vite)
* **Base de Datos:** MySQL
* **Control de Versiones:** Git & GitHub

---

## Estructura del Proyecto

sistema-gestion-creditos/
├── backend/                  # Proyecto Django
│   ├── apps/
│   │   ├── clientes_solicitudes/
│   │   ├── evaluacion/
│   │   ├── creditos/
│   │   ├── pagos_morosidad/
│   │   ├── seguridad_reportes/
│   │   └── integraciones/
│   ├── core/
│   └── manage.py
├── frontend/                 # Proyecto React
│   ├── src/
│   └── package.json
├── .gitignore
└── README.md


Guía de Inicio Rápido
Prerrequisitos
Python 3.10+

Node.js 18+

MySQL 8.4.0+

1. Configuración del Backend (Django)
cd backend
python -m venv venv
# En Windows: venv\Scripts\activate 
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
2. Configuración del Frontend (React)
cd frontend
npm install
npm run dev