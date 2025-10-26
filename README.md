# Arkanoid Game

Proyecto sencillo Arkanoid (HTML/CSS/JS).

Cómo subir este proyecto a GitHub

1. Inicializar repo local (si no está):

   ```powershell
   Set-Location -LiteralPath 'd:\Diseño web\100 PROYECOS JS\02-Arkanoid-Game'
   git init
   git add .
   git commit -m "Initial commit"
   ```

2. Crear repositorio en GitHub:
   - Opción A (recomendada si tienes GitHub CLI):

     ```powershell
     gh repo create NOMBRE-DEL-REPO --public --source=. --remote=origin --push
     ```

   - Opción B (manual): crear un nuevo repositorio en https://github.com/new y seguir las indicaciones para enlazar el remoto:

     ```powershell
     git remote add origin https://github.com/TU_USUARIO/NOMBRE-DEL-REPO.git
     git branch -M main
     git push -u origin main
     ```

3. Notas útiles
   - Si git falla al commitear por falta de usuario/ email, configura:

     ```powershell
     git config --global user.name "Tu Nombre"
     git config --global user.email "tu@email"
     ```

   - Puedes cambiar `main` por `master` si tu preferencia o la configuración lo requiere.

¡Listo! Una vez hecho push, revisa el repositorio en GitHub.
