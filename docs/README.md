# PDF Reader

Estecomponente permite leer archivos pdf.

![image](https://user-images.githubusercontent.com/92064924/204400207-73c99629-9c67-4919-84fc-cd5d73abad95.png)

## Configuration 

### Paso 1 - Clonar

Realizar la [clonación](https://github.com/Daniela1421/itgloberspartnercl-html-pdf.git) de este repositorio.

### Paso 2 - Editar el Manifest.json 

Ingresar al archivo manifest.json y realizar modificaciones en: `vendor`, `name`, `version`, `title` y `description`
como se muestra en el siguiente ejemplo: 
```
{
  "vendor": "itgloberspartnercl",
  "name": "pdf-reader",
  "version": "0.0.1",
  "title": "Lector de PDF",
  "description": "Lector de PDF",
}
```
Además, verifique que el archivo cuente con los siguientes builders: 
```
  "builders": {
    "react": "3.x",
    "messages": "1.x",
    "docs": "0.x",
    "store": "0.x"
  }
```
### Paso 3 - Instalar node-modules

Para realizar esta instalación de node-modules, debe estar ubicado en la carpeta de `react` de la aplicación y ejecutar el comando `yarn`, y tendrá instaladas todas las dependencias necesarias para usar esta plantilla.

### Paso 4 - Ejecutar el preview

Despues de realizar los pasos anteriores puede verificar si su componente está funcionando ejecutando el comando `vtex link` si todo funciona correctamente deberá ver en consola `Sending locale change event`, si por el contrario ocurre un error verifique los pasos anteriores y realice nuevamente este paso. 

### Paso 5 - Implementar el componente

Por último, para utilizar el componente debe agregarlo a las `dependencies` en el `manifest.json` de su tienda de la siguiente manera: vendor.name : version. Por ejemplo: 
```
  "dependencies": {
     "itgloberspartnercl.pdf-reader": "0.x",
  }
```

## Contributors ✨

Daniela Ducuara Cañas
