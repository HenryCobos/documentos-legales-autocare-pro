# 📄 Documentos Legales - AutoCare Pro

Este repositorio contiene los documentos legales y sitio web informativo de AutoCare Pro, listos para publicarse en GitHub Pages.

## 📋 Contenido

- **Política de Privacidad** (`docs/privacy.html`)
- **Términos de Servicio** (`docs/terms.html`)
- **Página de Soporte** (`docs/support.html`)
- **Página Principal** (`docs/index.html`)

## 🚀 Cómo Publicar en GitHub Pages

### Opción 1: Nuevo Repositorio

1. **Crear repositorio en GitHub:**
   ```bash
   # Desde la carpeta documentos-legales-autocare-pro
   git init
   git add .
   git commit -m "Initial commit: Legal documents and website"
   ```

2. **Subir a GitHub:**
   ```bash
   git remote add origin https://github.com/TU-USUARIO/autocare-pro-legal.git
   git branch -M main
   git push -u origin main
   ```

3. **Activar GitHub Pages:**
   - Ve a tu repositorio en GitHub
   - Haz clic en **Settings**
   - En el menú lateral, selecciona **Pages**
   - En **Source**, selecciona la rama `main`
   - En **Folder**, selecciona `/docs`
   - Haz clic en **Save**

4. **Tu sitio estará disponible en:**
   ```
   https://TU-USUARIO.github.io/autocare-pro-legal/
   ```

### Opción 2: Usar un Repositorio Existente

Si ya tienes un repositorio (como `henrycobos.github.io`):

1. **Copiar archivos:**
   ```bash
   cp -r documentos-legales-autocare-pro/docs/* henrycobos.github.io/autocare-pro/
   ```

2. **Commit y push:**
   ```bash
   cd henrycobos.github.io
   git add autocare-pro/
   git commit -m "Add AutoCare Pro legal documents"
   git push origin main
   ```

3. **Las URLs serán:**
   ```
   https://henrycobos.github.io/autocare-pro/privacy.html
   https://henrycobos.github.io/autocare-pro/terms.html
   https://henrycobos.github.io/autocare-pro/support.html
   https://henrycobos.github.io/autocare-pro/index.html
   ```

## 🔗 URLs para App Store Connect

Una vez publicado, usa estas URLs en tu configuración de App Store Connect:

### Privacy Policy URL:
```
https://TU-USUARIO.github.io/autocare-pro-legal/privacy.html
```

### Terms of Service URL (EULA):
```
https://TU-USUARIO.github.io/autocare-pro-legal/terms.html
```

### Support URL:
```
https://TU-USUARIO.github.io/autocare-pro-legal/support.html
```

### Marketing URL:
```
https://TU-USUARIO.github.io/autocare-pro-legal/
```

## ✅ Verificación de Cumplimiento

Estos documentos cumplen con:

### ✓ Requisitos de Apple App Store
- [x] Política de privacidad clara y accesible
- [x] Términos de servicio completos
- [x] Información de contacto
- [x] Descripción de permisos solicitados
- [x] Información sobre suscripciones y renovación automática
- [x] Política de reembolsos
- [x] Responsabilidades y limitaciones

### ✓ GDPR (Reglamento General de Protección de Datos)
- [x] Explicación clara de qué datos se recopilan
- [x] Base legal para el procesamiento
- [x] Derechos del usuario (acceso, corrección, eliminación)
- [x] Información sobre transferencias internacionales
- [x] Contacto para ejercer derechos

### ✓ CCPA (California Consumer Privacy Act)
- [x] Categorías de información recopilada
- [x] Propósito de recopilación
- [x] Derecho a solicitar eliminación
- [x] No venta de información personal

### ✓ COPPA (Children's Online Privacy Protection Act)
- [x] Declaración sobre usuarios menores de 13 años
- [x] Compromiso de no recopilar datos de niños

## 📝 Notas Importantes

### Para App Store Connect:

1. **Privacy Policy URL:** **OBLIGATORIO** - Apple rechaza apps sin política de privacidad
2. **Support URL:** **OBLIGATORIO** - Debe incluir forma de contacto
3. **Marketing URL:** Opcional pero recomendado
4. **EULA:** Opcional (Apple proporciona uno estándar, pero el nuestro es más específico)

### Actualizaciones Futuras:

Si necesitas actualizar los documentos:
1. Modifica los archivos HTML en `docs/`
2. Actualiza la fecha "Última actualización"
3. Haz commit y push a GitHub
4. Los cambios se reflejarán automáticamente en GitHub Pages

### Traducciones:

Si quieres agregar versiones en inglés:
- Crea archivos como `privacy-en.html`, `terms-en.html`
- Agrega enlaces para cambiar de idioma en cada página

## 🎨 Personalización

### Cambiar colores:
Modifica las variables en las etiquetas `<style>` de cada archivo:
- Color principal: `#1E88E5` (azul)
- Color secundario: `#667eea` (púrpura)

### Cambiar email de contacto:
Busca y reemplaza `support@autocarepro.app` por tu email real en todos los archivos.

### Agregar logo:
Reemplaza el emoji 🚗 con una imagen:
```html
<img src="logo.png" alt="AutoCare Pro" style="width: 100px;">
```

## 📧 Contacto

Para preguntas sobre estos documentos legales:
- Email: support@autocarepro.app
- Repositorio: [GitHub Issues](https://github.com/TU-USUARIO/autocare-pro-legal/issues)

## 📜 Licencia

Estos documentos están diseñados específicamente para AutoCare Pro.

---

**Última actualización:** Octubre 2025
