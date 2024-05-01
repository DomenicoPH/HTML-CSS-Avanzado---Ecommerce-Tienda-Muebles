# Proyecto Tienda Muebles (HTML, CSS)

## Enfoque CSS

### - Módulos:  
 Este enfoque organiza el CSS alrededor de módulos o componentes individuales, lo que facilita la reutilización y el mantenimiento del código. Cada módulo tiene su propio archivo CSS, lo que ayuda a mantener la coherencia y aislamiento entre los diferentes componentes de una aplicación o sitio web.
### - BEM:  
BEM (Block Element Modifier) es una metodología de nomenclatura que ayuda a estructurar y organizar el CSS de manera más clara y semántica. Divide los elementos de una interfaz en bloques (componentes), elementos (partes dentro de esos componentes) y modificadores (variantes de un bloque o elemento). Esto facilita la comprensión del código y evita la especificidad excesiva.
### - SMACSS:  
SMACSS (Scalable and Modular Architecture for CSS) es una metodología que se enfoca en la escalabilidad y modularidad del CSS. Proporciona pautas para organizar el CSS en cinco categorías principales: Base, Layout, Module, State y Theme. Esta organización ayuda a mantener un código CSS más limpio, estructurado y fácil de mantener a medida que el proyecto crece en tamaño y complejidad.

## Box Model  

En CSS todo es una caja, pero cómo sea esa caja y que medidas tenga depende de 4 cosas. La primera es el contenido, despues el padding (relleno o margen interno), borde (linea que bordea el contenido. Está después del padding) y finalmente el margen (margen externo).  

## Normalize  
https://necolas.github.io/normalize.css/

## Displays  

En CSS, la propiedad display determina cómo se muestra un elemento en el flujo de un documento HTML. Controla el tipo de caja que un elemento genera y, por lo tanto, su comportamiento y apariencia en la página web. Aquí hay algunos valores comunes para la propiedad display:  

### block:  
Los elementos con esta propiedad ocupan todo el ancho disponible y comienzan en una nueva línea. Ejemplos comunes de elementos de bloque son &lt;div&gt;, &lt;p&gt;, &lt;h1&gt; a &lt;h6&gt;, entre otros.  

### inline:  
Los elementos con esta propiedad no inician una nueva línea y solo ocupan el espacio necesario para su contenido. Ejemplos comunes de elementos en línea son &lt;span&gt;, &lt;a&gt;, &lt;strong&gt;, entre otros.  

### inline-block:  
Combina las características de elementos de bloque e inline. Los elementos ocupan solo el espacio necesario, pero permiten establecer ancho, alto, padding y margen. Esto los hace útiles para crear diseños flexibles que aún respetan las propiedades de bloque y línea.  

### none:  
Hace que el elemento no se muestre en absoluto en la página. Es útil para ocultar elementos de manera condicional con CSS.  

### flex y grid:  
Introducidos en CSS3, estos valores permiten crear diseños más complejos y flexibles. flex establece un contexto de diseño flexible en un contenedor, mientras que grid crea una cuadrícula bidimensional que facilita el posicionamiento de los elementos.