# Procesador Monociclo de 16 bits

Este repositorio contiene el diseño y la implementación de un **procesador monociclo de 16 bits**, desarrollado como parte de un proyecto académico en la Universidad Nacional de Misiones (UNaM). El procesador es capaz de ejecutar instrucciones aritmético-lógicas, de carga, almacenamiento y salto condicional en un solo ciclo de reloj.

## Desarrollado por
- **Alumno**: Joaquín Küster
- **Profesor**: Claudio Biale
- **Universidad**: Universidad Nacional de Misiones (UNaM) - Apóstoles, Misiones

## Características principales
- **Arquitectura de 16 bits**: Diseñado para manejar datos y direcciones de 16 bits.
- **Conjunto de instrucciones (ISA)**: Soporta 11 instrucciones, incluyendo operaciones aritméticas, lógicas, carga/almacenamiento y saltos condicionales.
- **Camino de datos**: Implementa un camino de datos completo con etapas de obtención, decodificación y ejecución.
- **Simulación**: Incluye un programa de prueba en lenguaje ensamblador para verificar el correcto funcionamiento del procesador.

## Estructura del proyecto
- **ISA**: Define el conjunto de instrucciones y sus formatos (Tipo R y Tipo I).
- **Camino de datos**: Detalla los componentes hardware necesarios para la ejecución de las instrucciones.
- **Ejecución de instrucciones**: Ejemplo de programa en ensamblador, binario y hexadecimal.
- **Simulación**: Video demostrativo de la ejecución del programa en el procesador.

## Recursos
- **Video de demostración**: [Ver video](https://youtu.be/s9WikaYVWPw)
- **Documentación**: Consulta el informe completo para más detalles sobre el diseño y la implementación.

## Desventajas
- **Ineficiencia**: El tiempo de ciclo está determinado por la instrucción más larga, y las unidades funcionales solo pueden utilizarse una vez por ciclo.

## Bibliografía
El proyecto se basa en recursos académicos y técnicos proporcionados por la universidad y otras fuentes especializadas. Consulta el informe para la lista completa de referencias.

---

**Nota**: Este proyecto fue desarrollado como parte de un trabajo académico y tiene fines educativos.