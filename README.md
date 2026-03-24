# DUDE FASHION – Django Shop

## 🚀 Quick Start

```bash
cd trendzone
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

Open http://127.0.0.1:8000/

## 🔐 Admin Panel

Go to: http://127.0.0.1:8000/admin/

- **Name:** Enter any name (e.g. Vijay, Raju, anything)
- **Password:** `dude143`  ← fixed, never changes

### What you can do in admin:
- ➕ **Add new products** (shirts, jeans, t-shirts, etc.)
- 📷 Upload product photos from your device
- ✏️ Edit price, MRP, badge (HOT/NEW/SALE)
- 🗑️ Delete or deactivate products
- 🎁 Post new offers/promotions (shown on homepage)
- 📋 Change display order of products

## 📁 Structure

```
trendzone/
  manage.py
  requirements.txt
  trendzone/         ← settings & URLs
  shop/
    models.py        ← Product + Offer models
    admin.py         ← Admin panel config
    views.py         ← Shop + homepage views
    static/shop/img/ ← Your 25 product images
    templates/
      admin/login.html   ← Custom login page
      shop/index.html    ← Homepage
      shop/shop.html     ← Shop with filter + pagination
