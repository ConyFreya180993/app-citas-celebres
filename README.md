# Evaluación 2 - Programación Híbrida
Proyecto desarrollado por **Constanza Núñez Sánchez**  
Carrera: Técnico en Informática - IPLACEX  
Asignatura: Programación Híbrida (26-1B-PRH0523-101-05-QM)

Proyecto desarrollado en **Ionic + Angular + Capacitor** para Unidad 2 : Persistencia

## Funcionalidades principales
- Página **Inicio**: muestra una cita aleatoria, con opción de eliminar controlada desde Configuración.
- Página **Gestión**: permite agregar y eliminar citas.
- Página **Configuración**: incluye el toggle *“¿Desea poder borrar citas en el inicio (frase aleatoria)?”*.

## Evidencia
- Probado en emulador **Pixel 4 (Android Studio)**.
- Persistencia confirmada con **SQLite**: las citas se mantienen tras reinicio en frío.
- Se adjuntan pantallazos y grabación como evidencia de funcionamiento.

## Instalación
1. Clonar el repositorio:
   ```bash
   git clone https://github.com/ConyFreya180993/app-citas-celebres.git


2. Instalar dependencias:
   ```bash
   npm install

3. Ejecutar en el navegador: 
    ```bash
   ionic serve

4. Sincronizar con Android:
   ```bash
   ionic capacitor sync
   ionic capacitor open android


// Nota importante: La carpeta node_modules fue eliminada antes de la entrega.
Para regenerar dependencias , basta con ejecutar npm install en la raíz del proyecto.

5. Estructura del Proyecto 

app-citas-celebres/
├── android/                  # Proyecto Android generado por Capacitor
├── node_modules/             # Dependencias de Node (ignorado en Git)
├── src/                      # Código fuente principal de la app
│   ├── app/                  # Configuración global de Angular/Ionic
│   ├── pages/                # Páginas de la aplicación
│   │   ├── inicio/           # Página de Inicio (cita aleatoria)
│   │   ├── gestion/          # Página de Gestión (agregar/eliminar citas)
│   │   └── configuracion/    # Página de Configuración (toggle eliminar en Inicio)
│   ├── services/             # Servicios (ej. citas.service.ts para SQLite)
│   └── assets/               # Recursos estáticos (imágenes, íconos)
├── capacitor.config.ts       # Configuración de Capacitor
├── package.json              # Dependencias y scripts del proyecto
├── README.md                 # Documentación del repositorio
└── .gitignore                # Archivos/carpetas ignorados en Git


## Observaciones

 - Entorno Web vs Nativo: Se observaron limitaciones en la persistencia web (browser) debido a la carga del motor WebAssembly, priorizando por tanto la validación funcional en el emulador nativo de Android.

 - Navegación: Se implementó una gestión de rutas que permite un flujo coherente entre la gestión de datos y la visualización.
La eliminación desde Inicio funciona correctamente gracias al toggle de Configuración.

- En Gestión la opción de eliminar está implementada de forma básica.




# Evidencia de ejecución

Se incluyen videos de prueba en vivo disponible en los siguientes enlaces:

https://drive.google.com/file/d/1tlzHx6Q0RS4NM-b0Ql6KjzT-pp4j48Ek/view?usp=sharing
https://drive.google.com/file/d/1RORnE5rUDS5Um5JaVLv3DL-3fQi2bN2P/view?usp=sharing
https://drive.google.com/file/d/1vgpt5-W5Hfnw_aGJ0CJPNlmTGGZunpIt/view?usp=sharing
https://drive.google.com/file/d/1_SfWFrQvcao9fNqF5MqcUVeIrYRPg_fD/view?usp=sharing
https://drive.google.com/file/d/1tacy9VwcgjzJsd_ipsPnujVIXZ_Ght3l/view?usp=sharing

# Respaldo 
El respaldo de este proyecto se encuentra en el siguiente enlace 

https://drive.google.com/file/d/1RL7qRpNALowhem6Pw4oJtveEWTvl-LJd/view?usp=sharing

Así como el respaldo de capturas de pantalla durante el desarrollo , lo puede en contrar aquí

https://drive.google.com/drive/folders/14CcvlhiGr6yZx3OBJaMLg87NkFIIcMic?usp=sharing
https://drive.google.com/drive/folders/1JaiG0BcQMkD9xNkXndMLqcgn8toPf0Ui?usp=sharing
https://drive.google.com/drive/folders/1yRQG0fLoqPCz2-kJ_JbaIbRB01FBkK88?usp=sharing

---
## Autor
**Constanza Núñez Sánchez**  
Carrera: Técnico en Informática - IPLACEX  
Correo de contacto: conyfreyatecnico@gmail.com  
GitHub: [ConyFreya180993](https://github.com/ConyFreya180993)






















