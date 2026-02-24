# Toughest Technical Challenges

## 1. Dynamic Model Loading in Django
Problem:
Users could select different CNN models. Loading all models at once caused memory overhead.

Solution:
Implemented a dynamic loader function that loads models based on dropdown selection and caches them for reuse.

Why It Was Challenging:
Managing model memory efficiently while keeping response time low.

---

## 2. Integrating ML Predictions with Django Views
Problem:
Synchronizing prediction output with patient database records.

Solution:
Created a ScanResult model and connected it to authenticated users.
