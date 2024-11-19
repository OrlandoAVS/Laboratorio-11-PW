# Laboratorio-11-Plantilla

¿Cuál es la finalidad del archivo vercel.json?
El archivo vercel.json sirve para configurar las propiedades y el comportamiento de un proyecto desplegado en Vercel. Permite definir rutas, reescrituras, redirecciones, configuraciones específicas para los entornos de desarrollo y producción, así como definir qué funciones se consideran serverless.

¿Qué ventajas tiene desplegar en Vercel frente a un servidor tradicional?
- Despliegue rápido y sencillo: Sin necesidad de administrar un servidor manualmente.
- Escalabilidad automática: Las aplicaciones escalan según la demanda sin configuración adicional.
- CDN integrada: Archivos estáticos y funciones serverless se distribuyen globalmente para mejorar el rendimiento.
- Integraciones directas: Con sistemas de control de versiones como GitHub, facilitando despliegues automáticos con cada commit.

¿Qué propiedades del archivo vercel.json son necesarias para que una aplicación Express funcione correctamente en Vercel?
Para que una aplicación Express funcione correctamente, es necesario especificar al menos las siguientes propiedades:
- "rewrites": Para redirigir todas las solicitudes a la función que maneja el servidor Express.
- "functions": Definir qué rutas están asociadas a funciones específicas.
- "outputDirectory" (si aplica): Indica la carpeta donde se encuentran los archivos estáticos del proyecto.
