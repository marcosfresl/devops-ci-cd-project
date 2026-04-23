# DevOps CI/CD Project – Docker + AWS + GitHub Actions

## 📌 Descripción
Este proyecto demuestra la implementación de un pipeline CI/CD completo utilizando GitHub Actions, Docker y despliegue en AWS EC2.

El objetivo es automatizar el ciclo de vida de una aplicación desde el código hasta producción.

---

## 🧱 Stack Tecnológico

- Python (Flask)
- Docker
- GitHub Actions (CI/CD)
- Linux

---

## ⚙️ Arquitectura

1. Developer hace push a GitHub  
2. GitHub Actions ejecuta pipeline:
   - Build de imagen Docker  
   - Deploy automático en EC2 vía SSH  
3. La aplicación queda corriendo en producción  

---

## 🔄 CI/CD Pipeline

El pipeline incluye:

- Build automático de la aplicación  
- Creación de imagen Docker  
- Despliegue automático en servidor EC2  

---

## 🐳 Docker

La aplicación está containerizada para asegurar:

- Portabilidad  
- Consistencia entre entornos  
- Deploy reproducible  

---

## ☁️ Infraestructura
- Security Groups configurados
- Acceso SSH para despliegue automatizado

---

## Cómo ejecutar

```bash
docker build -t devops-app .
docker run -p 5000:5000 devops-app

👨‍💻 Autor

Marcos Fresl
DevOps | Cloud | DevSecOps
