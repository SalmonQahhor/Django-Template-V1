# Django Project Setup

A clean and minimal starter template for Django development.

## 🚀 Quick Start

To set up the project and run the server, execute these commands in order:

```bash
# 1. Setup Environment
python3 -m venv venv && source venv/bin/activate

# 2. Install & Update
pip install --upgrade pip && pip install django environs

# 3. Database & Admin
python manage.py makemigrations && python manage.py migrate
python manage.py createsuperuser

# 4. Run Server
python manage.py runserver
