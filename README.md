[![GitHub issues](https://img.shields.io/github/issues/frameworkperu/openinvoiceperu.svg?style=plastic)](https://github.com/frameworkperu/openinvoiceperu/issues) [![GitHub forks](https://img.shields.io/github/forks/frameworkperu/openinvoiceperu.svg?style=plastic)](https://github.com/frameworkperu/openinvoiceperu/network) [![GitHub stars](https://img.shields.io/github/stars/frameworkperu/openinvoiceperu.svg?style=plastic)](https://github.com/frameworkperu/openinvoiceperu/stargazers) 
[![NuGet](https://img.shields.io/badge/downloads-2.8K-blue.svg?style=plastic)](https://github.com/FrameworkPeru/openinvoiceperu/releases)
[![NuGet](https://img.shields.io/badge/nuget-v1.5.2-green.svg?style=plastic)](https://www.nuget.org/packages/OpenInvoicePeru.DataTransfersObjects/)


![Open Invoice Perú](http://frameworkperu.com/OpenInvoicePeruLogo.png "Open Invoice Perú")
# OpenInvoicePeru v1.5.2 #
OpenInvoicePeru es un proyecto Open Source construido con C#, haciendo sencilla la Facturación Electrónica de SUNAT, este proyecto está orientado al desarrollador.
Permite la generacion de XML, empaquetado, envío y recepción de documentos electrónicos a través de una API REST.

Si encuentra algún bug por favor reportarlo a la zona de [Issues de GitHub](https://github.com/FrameworkPeru/openinvoiceperu/issues).

Puede leer la documentación de SUNAT en el repositorio de [OpenInvoicePeruDocs](https://github.com/FrameworkPeru/openinvoiceperudocs).

Para consultar las novedades y cambios del proyecto revise el [Control de Cambios](CHANGELOG.md)

# Características #
- Generación de XML los siguientes documentos electrónicos:
  - Facturas
  - Boletas 
  - Notas de Crédito
  - Notas de Débito
  - Resumen Diario de Boletas
  - Comunicaciones de Baja
  - Retenciones
  - Percepciones
  - Guías de Remisión
 
- Firmado del XML con un certificado digital elegido por el usuario.
- Envío al servicio Web de SUNAT de los documentos electrónicos generados (Beta y Producción).
- Envío de Resumen Diario y Comunicación de Baja.
- Desempaquetado y Lectura del contenido del CDR de SUNAT.
- Consulta de Tickets de los Resúmenes y Bajas.
- API REST bajo ASP.NET Web API 2.
- Aplicación Windows de prueba de envío a SUNAT.

### Clientes API REST de Ejemplo ###
- Los ejemplos en VB y C# para el consumo de la API REST con PostSharp bajo .NET 4.0 en el siguiente [repositorio](https://goo.gl/adgBmv).

- Ejemplo para conectarte a la API REST desde .NET Framework 2.0 revisa este [repositorio](https://goo.gl/wGkAmu).

- Ejemplo de conexión en Silverlight 5.0 entre a [repositorio](https://github.com/FrameworkPeru/ClienteSLOpenInvoicePeru).

## Donaciones ##

Si cree que el proyecto lo ayuda con su labor, puede donar a través de PayPal [aquí](http://paypal.me/evelascom).

## Consideraciones ##
- El proyecto se ha desarrollado con VS2017, usando como base el .NET Framework 4.6.1.
- Se recomienda usar encarecidamente VS2017 o superior, la edición [Community Edition](https://www.visualstudio.com/downloads/download-visual-studio-vs), es gratis y mucho mejor que sus predecesores.
Puede usar la versión Professional o Enterprise si lo desea.

- Para poder ejecutar correctamente el proyecto **debe iniciar Visual Studio como Administrador** y tener instalado IIS 7.0 o posterior.

- Si quiere colaborar con su granito de arena puede hacer un Fork y enviar un Pull Request.

## Formas de Colaborar ##

1) Hacer un Fork al proyecto en su propio repositorio.
2) Crear un branch con un prefijo que identfique el cambio **(feature/xxx o bugfix/xxx)**.
3) Realizar el Pull Request con los comentarios que expliquen el cambio realizado.

## Enlaces de Interes ##

- [Framework Peru](http://frameworkperu.com)
- [Foro Técnico de OpenInvoicePeru](http://forotecnico.frameworkperu.com)
- [Canal Oficial de OpenInvoicePeru en Telegram](http://t.me/OpenInvoicePeru)
- [Framework Peru en Facebook](http://facebook.com/FrameworkPe)

## Descargo de Responsabilidad ##

Este software se entrega como tal y es libre de modificarlo a su gusto, copiarlo en su totalidad 
o de manera parcial, un agradecimiento público no cuesta nada.

Así mismo no hay garantía expresa de este producto, cualquier inconveniente que se presente con SUNAT 
es enteramente responsabilidad del usuario al usar este Software, a menos que haya recibido soporte por parte de **Framework Peru**. 

Si tiene errores con SUNAT fíjese en el código devuelto:

- Del 0100 al 1999 Excepciones (Usuarios mal escritos, RUCs no validos, etc.).
- Del 2000 al 3999 Errores que generan rechazo (Se envia pero rebota).
- Del 4000 en adelante Observaciones (Correcciones menores).

Si tiene mas dudas con SUNAT comuníquese con ellos al [+51 1 3150730](tel:+5113150730).

## UBL 2.1 ##

Este proyecto fue inicialmente concebido en Abril del 2016 para el formato del UBL 2.0, la actualización al UBL 2.1 por parte de Framework Peru no se realizará de forma [gratuita](http://www.frameworkperu.com/2018/06/15/openinvoiceperu-con-ubl-2-1/), sin embargo cualquier persona es libre de realizar el Pull Request con sus respectivas mejoras al código y hacer que toda la comunidad se beneficie con las actualizaciones, todo cambio es bienvenido. 

## Asesoría y Soporte ##


Si necesita Asesoría, Desarrollo, Implementación o necesita Integrar su Sistema de Ventas o ERP con **OpenInvoicePeru**, puede contactarnos al correo [soporte@frameworkperu.com](mailto:soporte@frameworkperu.com) y se puede concertar una reunión virtual, ya sea Skype, Hangouts, [Telegram](http://t.me/ErickOrlando) o TeamViewer.
Recuerde que si bien el proyecto es de código abierto, el soporte y asesoría técnica son de pago, para más información ingrese [aquí](https://goo.gl/9xkUtB).
