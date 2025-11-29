#Project1

Repository ini digunakan untuk latihan GitHub dan CI/CD otomatis.

Isi Repository
- github/workflows/ci.yaml → workflow GitHub Actions
- Dockerfile → build aplikasi dalam Docker 
- deployment.yaml → file untuk deploy ke K3s
- ansible/playbook.yaml → otomatisasi server 

Workflow CI/CD
Workflow otomatis:
1. Pull code ketika ada push
2. Build project
3. Build Docker image
4. Deploy ke server/Kubernetes

Menjalankan Project
Jika project memakai program:
