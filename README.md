## Creador
* Nombre: Miguel Molina Flores
* Codigo: 56197


# Base de Datos conectado a una aplicación para el guardado de datos de un perrito

El presente proyecto busca crear lograr una conexión entre una aplicación de formulario hecha en REACT y una base de datos dentro de un docker. Lo que ayudará a que se puedan recolectar los datos del formulario dentro de la base de datos logrando así la conexión deseada.

## Contraseña
1234 (para el root)

## Requisitos Técnicos

Requisitos técnicos para ejecutar en Windows 10 o Windows 11:

* Windows 11 de 64 bits: versión Home o Pro 21H2 o superior, o versión Enterprise o Education 21H2 o superior.
* Windows 10 de 64 bits: versión Home o Pro 21H1 (compilación 19043) o superior, o versión Enterprise o Education 20H2 (compilación 19042) o superior.
* Habilitar la función WSL 2 en Windows.

Se requieren los siguientes requisitos de hardware para ejecutar WSL 2 en Windows 10 o Windows 11:
* Procesador de 64 bits con Traducción de Direcciones de Segundo Nivel (SLAT).
* 4 GB de RAM del sistema.
* El soporte de virtualización a nivel de BIOS debe estar habilitado en la configuración del BIOS. Para obtener más información, consulta la sección de Virtualización.

## Ejecución local

1. Clonar el repositorio que contiene el docker con el siguiente comando:

  `git clone https://github.com/Mickysaurio-rex/BD_Primer_Parcial.git`

2. Ubicalo en una carpeta, mejor si es una recien creada, e ingresa en esta misma:
  `cd [nombre del directorio]`
  
3. Levanta los servicios con los siguientes comandos:
   `docker-compose up`
   `docker-compose -f [nombre del archivo que tiene la configuracion del docker] up`

4. Para detener los servicios:
   `docker-compose down`
   `docker-compose -f [nombre del archivo que tiene la configuracion del docker] down`
