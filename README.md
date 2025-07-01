# Registro y Gestión de Personal Administrativo y Gerencial
Aplique los conceptos de Programación Orientada Objetos, Herencia, Polimorfismo y Colecciones en C#.

Este proyecto desarrollado en ASP.NET MVC con C# tiene como objetivo implementar un sistema básico de registro, cálculo de remuneraciones y gestión de empleados. Se estructura en dos módulos principales:

✅ Módulo Administrativo
Permite registrar empleados administrativos con los siguientes datos:

DNI

Nombres y Apellidos

Categoría del puesto (Gerente, Coordinador, Auxiliar, u otros)

Número de hijos

Tipo de contrato (Indefinido o Contratado)

Incluye el cálculo automático de:

💰 Sueldo Básico según categoría

🎓 Bonificación por escolaridad (por número de hijos)

📋 Bonificación por tipo de contrato

🧾 Monto total a pagar

Se utiliza una clase parcial para separar atributos y métodos.

✅ Módulo Gerencial
Permite registrar, editar y listar gerentes utilizando una colección List<Gerente>. Se valida que el DNI no se repita y se visualiza la cantidad total de gerentes registrados.

🛠️ Funcionalidades principales:
Formularios con validación

Envío de datos mediante métodos GET y POST

Separación de lógica en Controlador y Vista (Razor)

Manejo de clases parciales

Uso de listas genéricas (List<T>)

