# Instrucciones para integrar el logo de PROGENER

## 📁 Ubicación del logo
El logo debe colocarse en esta carpeta como:
```
logo-progener.png
```

## 📐 Especificaciones técnicas
- **Nombre de archivo:** `logo-progener.png`
- **Formato:** PNG con fondo transparente (recomendado)
- **Tamaño recomendado:** 
  - Ancho mínimo: 300px
  - Altura: variable (se ajustará automáticamente)
- **Proporción:** Mantén el aspecto original del logo
- **Resolución:** 72-100 DPI para web

## 🎨 Cómo aplicará en el sitio
El logo se mostrará con:
- **Desktop (>768px):** 60px de altura
- **Móvil (<768px):** 45px de altura
- Se ajustará automáticamente proporcionalmente

## 📝 Pasos para actualizar el logo:

1. **Guarda el logo** en esta carpeta con el nombre exacto: `logo-progener.png`

2. **Sincroniza con Git:**
   ```powershell
   cd C:\Users\micha\progener-spa
   git add assets/logo-progener.png
   git commit -m "add: logo oficial PROGENER SpA"
   git push
   ```

3. **Espera ~45 segundos** a que GitHub Pages procese el cambio

4. **Recarga el navegador** con Ctrl+F5 (limpia caché)

¡El logo aparecerá en navbar y footer automáticamente!

---
**Nota:** Si necesitas cambiar el logo después, simplemente reemplaza el archivo `logo-progener.png` en esta carpeta y repite los pasos 2-4.
