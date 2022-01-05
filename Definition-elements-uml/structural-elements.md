# Elementos estructurales

Son las partes estáticas del modelo y representan cosas que son conceptuales o materiales.

**Los elementos estructurales:** son elementos estáticos que no cambian durante el desarrollo de software

## Clase

Es una descripción de un conjunto de objetos que comparten los mismos atributos operaciones relaciones y semántica, una clase implementa una o más interfaces.

- Gráficamente se representa con un rectángulo que incluye su nombre, atributos y sus operaciones

## Interfaces

Una interfaz es una colección de operaciones que especifican un servicio de una determinada clase componente.

- Una interfaz describe el comportamiento visible externamente de ese elemento:
  - Puede mostrar el comportamiento completo o solo una parte de el mismo
  - Una interfaz describe un conjunto de especificaciones de operaciones o sea más o menos su signatura, pero nunca su implementación
  - Se representa con un círculo
  - Rara vez está aislada, sino que está conectada a la clase o componente que realiza

## Colaboración

Define una interacción, es una sociedad de roles y otros elementos que colaboran para proporcionar un comportamiento cooperativo mayor, que la suma de los comportamiento de sus elementos. Las colaboraciones tienen dimensiones tanto estructural como de comportamiento, una misma clase puede participar en diferentes colaboraciones.

- Las colaboraciones representan la implementación de patrones que forman un sistema
  - Se representa con un elipse con bordes discontinuos

## Casos de uso

Un caso de uso es la descripción de un conjunto de acciones que un sistema ejecuta y produce determinado resultado que es de interés para un actor en particular.

- Un caso de uso se utiliza para organizar los aspectos del comportamiento en un modelo el caso de uso es realizado por una colaboración.
- Los casos de uso regularmente expresan una funcionalidad del sistema

## Clases activas

Es una clase cuyos objetos tienen uno o más procesos o hilos de ejecución y por lo tanto pueden dar lugar a actividades de control.

- Una clase activa es igual a una clase excepto que sus objetos representan elementos cuyo comportamiento es concurrente con otros elementos
  - Se representa igual que una clase pero con líneas más gruesas

## Componentes

Es una parte física y reemplazable de un sistema que conforma con un conjunto de interfaces y proporciona la implementación de dicho conjunto, un componente representa típicamente el empacamiento físico de diferentes elementos lógicos:

- Clases
- Interfaces
- Colaboraciones

## Nodos
