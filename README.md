# shop-back

Django backend API for Online Store.

## Setup

```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

## Endpoints

| Method | URL | Description |
|--------|-----|-------------|
| GET | /api/products/ | All products |
| GET | /api/products/<id>/ | Product by ID |
| GET | /api/categories/ | All categories |
| GET | /api/categories/<id>/ | Category by ID |
| GET | /api/categories/<id>/products/ | Products by category |
