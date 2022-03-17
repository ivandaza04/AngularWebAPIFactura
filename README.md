# AngularWebAPIFactura

CRUD usando ASP.NET Web API, MongoDB y Angular

Prerrequisitos
•	MongoDB
•	Robo 3T
•	Visual Studio o Visual Studio Code con ASP.NET
•	.NET 6.0 SDK
•	Angular CLI: 13.2.4
• Node: 16.14.0

Pasos
1. Cree una base de datos en MongoDB con "DatabaseName": "FacturaStore" y "FacturasCollectionName": "Facturas".
2. Instalar los siguientes complementos en ASP.NET: dotnet add package MongoDB.Driver, dotnet add package NETCore.MailKit --version 2.0.3
3. Ejecute el proyecto "FacturaStoreApi" en un entorno con ASP.NET Core
4. Probar los servicios con POSTMAN
5. Instale Angula y Node
6. Descargar el codigo de frontend en https://github.com/ivandaza04/Factura.git
7. En el proyecto "Factura" y en scr/app/servicios/api/FacturacordService.ts cambie la direccion del puerto que corresponda en readonly APIUrl;
8. Ejecute poyecto en angular "Factura"
