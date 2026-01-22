## Sistema de Electronica 
<p align="right"><b><h1>ELECTROMUNDO</h1></b></p>

Se realizara un sitio web donde venderemos los mejores productos de electronica 
![rob](https://github.com/user-attachments/assets/dd167b8b-6073-4ed4-ad25-862d500108f6)
## Descripcion
Mi sitio web está diseñada para resolver las principales problemáticas que enfrentan los clientes al comprar en una tienda de electrónica. Actualmente, los usuarios suelen perder tiempo buscando productos, enfrentan dificultades para acceder a información de contacto inmediata y no siempre encuentran métodos de pago accesibles o promociones claras.


## Requerimientos Funcionales (El “Qué hace”)

RF1: Registrar productos electrónicos (laptops, teléfonos, accesorios).

RF2: Visualizar el inventario actualizado en tiempo real.

RF3: Filtrar productos por categoría, marca y precio.

RF4: Registrar ventas y tener acceso al contacto rapidamente

RF5: Autenticar usuarios (administrador y vendedor).


## Requerimientos NO funcionales 

RF1:  Rendimiento La aplicación debe cargar la página principal en menos de 3 segundos bajo condiciones normales de red

RF2:  Seguridad Se debe implementar autenticación segura con tokens o sesiones.

RF3:  Usabilidad El carrito de compras debe ser accesible desde cualquier sección de la aplicación.

RF4: Disponibilidad el sitio web debe estar disponible al menos el 99.5% del tiempo.

RF5: Portabilidad debe poder ejecutarse en diferentes navegadores modernos (Chrome, Edge, Firefox)


## Tecnologías y Herramientas del Ecosistema

#Manejo de Estado Global
Herramienta: Context API (React Context)
¿Por qué? Se utilizará Context API porque el proyecto necesita compartir información entre varias pantallas sin pasar props manualmente, por ejemplo:
Usuario (admin / vendedor)


#Consumo de Datos
Herramienta: Axios + Fetch API (opcional)
¿De dónde vienen los datos?
Los datos vendrán desde un backend con base de datos, por ejemplo:
API REST (Node.js, MySQL y MongoDB)
¿Por qué Axios? Manejo más fácil de peticiones GET/POST/PUT/DELETE
Permite interceptores para tokens (seguridad)
Mejor control de errores

 
#Estilizado
Herramienta: Tailwind CSS
¿Por qué?
Permite diseño rápido y moderno
Es responsive (se adapta a celular, tablet y PC)
Mantiene un estilo consistente en toda la tienda
Facilita crear botones, cards, banners y menús responsivos como el que ya estás trabajando


#Despliegue
Herramienta: Vercel
¿Por qué?
Se utilizará Vercel porque:
Es ideal para proyectos en React
El despliegue es automático desde GitHub
Muy rápido y estable
Permite tener el sitio disponible con facilidad (cumple el requisito de disponibilidad)

https://mermaid.live/edit#pako:eNptk89S2zAQxl9Fo3MgISRO8KEzIaEQ_pQA7aUOh8XaOBpkKZUlWmB4mD5AT731mhfrSjGm6ZBcbOv37fftrv3McyOQp3yhzPd8Cdaxz5O5ZvQbZV8qD1YahtpZYKBYJZ00t2xn5wM7zG6Q5WAL0GxljfC5MxUTWAlkCthoNr3dlDmM-Dg7l5WDWUNWyCxqgVY-ARmwFWgHSgGpNrpx1E2aEAupQoqVsWTrsDB2_QvaJdgc2iuLOQXbCCdReJQdkZ-odWSYQ3kno9U1Qu5q-CjCH99JR4wHFdKBd6Zc_3SSStAo8L-Ix03EChXmFEQD829TqZ2OI3ySjQqLBTSnYaw0Risb8CSC09f8hTJ3xIw3zFayWjCNgtPsH2RrtDnR37xESycUb_1bNx2cRulZ00Fu9ELaEuiiXNlXg7NInYeNU3aaFO2BdvxAw4gGW_s-j_BFduNMfs-ErEqp_SMGTuoosc2qLiL7KZs2B2_NidhI6THavfeGjKL6sgkvtcxpwxVWdY8BuozQLGR_oLqCVlPjIChZ-yFMShhb47OIXwW8IIxwZ-5Rt7eLXkXqOlBLuJNKOvoKFl6H3WN4e4r1H81QMWtUjDvXvMULKwVPnfXY4iXSlMMtfw4l59wtscQ5T-lSgL2f87l-IQ01_dWY8lVmjS-WPF2AqujOrwR9CRMJhYWyebrZ_dh47Xja3evHIjx95j942u91d_vDXtJPOp3ecDA8aPFHgjqD3W7STZKDg8H-sLPf6b20-FO07ewmg336D5NhkvT2-t3k5S9-OmLd

