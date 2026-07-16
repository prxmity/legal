# Política de Privacidad de Proximity

Estado: contenido de borrador para integración, staging y revisión del producto.

Este borrador de política de privacidad existe para que las builds del producto puedan mostrar un aviso de privacidad realista, desplazable y versionado antes de la aprobación legal final. Refleja las categorías de datos que se espera que el servicio maneje y las razones operativas por las que dichas categorías pueden utilizarse, pero sigue sujeto a revisión legal y de cumplimiento.

Al usar una build que haga referencia a este repositorio, reconoces que el documento es provisional y puede cambiar antes de un lanzamiento en producción o un despliegue público más amplio.

## 1. Categorías de datos que esperamos procesar

Dependiendo del conjunto de funciones habilitado en una build determinada, el servicio puede procesar identificadores de cuenta, información del proveedor de autenticación, metadatos de perfil, preferencias de idioma, señales de ubicación aproximada o proporcionadas por el dispositivo, eventos de interacción con la app, comunicaciones de soporte y diagnósticos a nivel de dispositivo necesarios para mantener el funcionamiento del producto.

Algunas funciones también pueden depender de estado temporal que indique si has completado el onboarding, aceptado los últimos documentos legales, concedido permisos requeridos o interactuado con otros usuarios a través del producto.

## 2. Por qué esperamos procesar datos

Esperamos procesar datos para autenticar a los usuarios, personalizar flujos de idioma y onboarding, determinar comportamiento del producto relacionado con la proximidad, respaldar comprobaciones de seguridad, investigar abusos, mantener la fiabilidad del servicio y mejorar la calidad del producto durante el desarrollo y la preparación del lanzamiento.

En casos limitados, también pueden conservarse registros operativos o registros relacionados con moderación para comprender incidentes, reproducir errores, responder a reportes y documentar decisiones de aplicación.

## 3. Señales relacionadas con la ubicación

Como Proximity está construido en torno a funciones de descubrimiento cercano, algunas builds pueden utilizar ubicación proporcionada por el dispositivo o señales derivadas relacionadas para determinar si deben mostrarse interacciones relevantes del producto. La precisión exacta, el período de retención y el tratamiento del lado del servidor siguen sujetos a revisión de producto y legal.

Este borrador es intencionadamente prudente: describe categorías y finalidades esperadas sin afirmar una implementación final de producción cuando todavía no existe aprobación.

## 4. Enfoque de retención

Esperamos conservar distintas categorías de datos durante distintos períodos según la necesidad del producto, los requisitos de seguridad, la depuración operativa, las obligaciones legales y el estado del ciclo de vida de la cuenta. Parte de la información puede eliminarse o anonimizarse cuando ya no sea necesaria, mientras que otros registros pueden necesitar conservarse más tiempo para documentar incidentes o eventos de seguridad.

Los calendarios específicos de retención se finalizarán en una versión aprobada posterior.

## 5. Compartición y proveedores de servicios

Podemos depender de proveedores de infraestructura, autenticación, analítica, soporte al cliente, hosting o seguridad para operar el servicio. Cuando se usen proveedores, esperamos que el acceso se limite a lo razonablemente necesario para la función correspondiente y que esté sujeto a controles contractuales y de seguridad adecuados para la implementación final.

No pretendemos que este borrador implique una lista definitiva de proveedores ni un mapa completo de flujos de datos en producción.

## 6. Controles de usuario

Dependiendo de la superficie del producto, los usuarios pueden poder actualizar información del perfil, cambiar el idioma de la interfaz, revisar versiones de documentos legales, revocar determinados permisos o solicitar la eliminación de la cuenta. Los controles exactos disponibles en producción pueden diferir de los disponibles en una build de desarrollo o staging.

## 7. Estado de borrador

Este documento es un borrador de trabajo pensado para respaldar integración y revisión. No es un aviso de privacidad final para producción y no debe tratarse como la declaración aprobada final sobre cómo el servicio en vivo procesa datos personales.
