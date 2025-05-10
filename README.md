# Salud Sexual Inclusiva

Plataforma web para telesalud y educación comunitaria sobre salud sexual y reproductiva con enfoque LGBTIQ+.

## Descripción

Este proyecto es una aplicación web diseñada para proporcionar información y recursos sobre salud sexual y reproductiva, con un enfoque especial en las necesidades de la comunidad LGBTIQ+. La plataforma incluye:

- Información educativa sobre salud sexual y reproductiva
- Sección específica para la comunidad LGBTIQ+
- Servicios de telesalud y consultas virtuales
- Recursos descargables y materiales educativos
- Formulario de contacto

## Estructura del Proyecto

```
SALUD-SEXUAL/
├── src/
│   ├── index.html         # Página principal
│   ├── static/            # Archivos estáticos
│   │   ├── images/        # Imágenes
│   │   └── placeholder/   # Imágenes placeholders
├── main.py                # Aplicación Flask
├── requirements.txt       # Dependencias
└── README.md              # Este archivo
```

## Requisitos

- Python 3.7 o superior
- Flask
- Dependencias listadas en `requirements.txt`

## Instalación

1. Clona este repositorio:
   ```
   git clone https://github.com/tuusuario/salud-sexual.git
   cd salud-sexual
   ```

2. Instala las dependencias:
   ```
   pip install -r requirements.txt
   ```

3. Ejecuta la aplicación:
   ```
   python main.py
   ```

4. Accede a la aplicación en tu navegador:
   ```
   http://localhost:8080
   ```

## Despliegue en Firebase

1. Instala Firebase CLI:
   ```
   npm install -g firebase-tools
   ```

2. Inicia sesión en Firebase:
   ```
   firebase login
   ```

3. Inicializa tu proyecto:
   ```
   firebase init
   ```
   - Selecciona "Hosting" y "Functions"
   - Configura las opciones según tus necesidades

4. Despliega la aplicación:
   ```
   firebase deploy
   ```

## Personalización

- Para añadir imágenes reales, colócalas en el directorio `src/static/images/`
- Puedes modificar el contenido editando el archivo `src/index.html`
- Para añadir nuevas funcionalidades backend, modifica `main.py`

## Notas de Seguridad

- Esta aplicación maneja información sensible sobre salud. Asegúrate de implementar las medidas de seguridad adecuadas en un entorno de producción.
- Para un despliegue real, considera agregar SSL/HTTPS y protección de datos según las regulaciones locales.

## Contribuciones

Las contribuciones son bienvenidas. Por favor, siente libre de mejorar este proyecto y adaptarlo a las necesidades específicas de tu comunidad.

## Licencia

Este proyecto está disponible bajo la licencia MIT.
