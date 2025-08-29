# 🔄 Flujo de Trabajo con Git

## Comandos Básicos Diarios

### 1. Antes de empezar a trabajar
```bash
git status                    # Verificar estado
git pull origin main         # Descargar últimos cambios
```

### 2. Después de hacer cambios
```bash
git add .                    # Agregar todos los cambios
git commit -m "Descripción clara del cambio"
git push origin main         # Subir a GitHub
```

### 3. Comandos útiles
```bash
git log --oneline -10        # Ver historial de commits
git diff                     # Ver cambios no guardados
git diff --staged           # Ver cambios en staging
```

## 🏷️ Convenciones para Commits

### Tipos de commit:
- `feat:` Nueva funcionalidad
- `fix:` Corrección de errores
- `style:` Cambios de diseño/CSS
- `refactor:` Refactorización de código
- `docs:` Documentación
- `test:` Pruebas

### Ejemplos:
```bash
git commit -m "feat: Add mobile gyroscope support for 3D effects"
git commit -m "fix: Resolve QR code generation error"
git commit -m "style: Improve card shadow and transitions"
git commit -m "docs: Update README with setup instructions"
```

## 🌐 GitHub Pages

Tu sitio está disponible en:
https://andiquis.github.io/Present/

Para actualizar el sitio, simplemente haz push a la rama main.

## 🔧 Configuración Útil

### Configurar usuario (una sola vez):
```bash
git config --global user.name "Tu Nombre"
git config --global user.email "tu.email@gmail.com"
```

### Ver configuración actual:
```bash
git config --list
```
