# Repo listo para subir a Git

Pasos rápidos:
1. Instalar dependencias (opcional, para probar local):
   ```bash
   pnpm install   # o npm install
   pnpm dev       # o npm run dev
   ```
2. Subir a GitHub:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin <URL_DE_TU_REPO>
   git push -u origin main
   ```
3. Deploy recomendado: **Vercel** (conecta el repo y listo).
