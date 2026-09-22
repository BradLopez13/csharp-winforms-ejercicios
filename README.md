# csharp-winforms-ejercicios

Ejercicios de clase del ciclo de DAM (2023) sobre diseño de interfaces de escritorio con C# y Windows Forms (.NET Framework).

## Qué hay

| Proyecto | Qué es |
| --- | --- |
| `tierra Media` | «Banco de la Tierra Media»: formulario de solicitud de préstamo con validación de campos mediante `ErrorProvider`; el botón solo se activa cuando los datos son válidos. |
| `CentroMedico` | Aplicación multiformulario (registros, datos propios y fechas de revisión) con menú lateral. |

`CentroMedico` parte de la plantilla de dominio público [Modern GUI Multi Form](https://rjcodeadvance.com/) de RJ Code Advance; su licencia original se conserva en la carpeta del proyecto. Los formularios de contenido son el trabajo del ejercicio.

Las capturas de las dos aplicaciones están en `Capturas Interfaces Brad Lopez.pdf`.

## Cómo ejecutarlo

Abrir el `.sln` de cada proyecto en Visual Studio en Windows y ejecutar. `tierra Media` usa .NET Framework 4.7.2 y `CentroMedico` usa 4.5.2.

## Limitaciones conocidas

- Solo interfaz: los datos no se guardan en ningún sitio.
- Windows Forms sobre .NET Framework no es multiplataforma.
