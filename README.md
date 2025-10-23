# 💻 4to Tecnología 2025  
## **Trabajo Práctico 1 – Tecnologías de la Información – 🏪 Store Manager 3000**

Una nueva cadena de tiendas nos contrató para desarrollar un sistema de **gestión de productos y ventas**.  
El sistema permitirá administrar el inventario, controlar precios y realizar operaciones de venta de forma eficiente.  

El objetivo será crear un programa modular, con menú interactivo, uso correcto de **listas, diccionarios, funciones, bucles y condicionales**, asegurando que todas las entradas sean validadas.

---

### 🧩 1. Cargar productos  

- El usuario podrá agregar un nuevo producto al inventario.  
- Por cada producto, se solicitará:
  - Nombre del producto.  
  - Precio unitario (número positivo).  
  - Cantidad en stock (entero mayor o igual a 0).  
- Todos los productos deben almacenarse en un **diccionario**, donde:  
  - **Clave:** nombre del producto.  
  - **Valor:** otro diccionario con el precio y la cantidad (`{"precio": 500, "stock": 20}`).  
- No se deben permitir nombres vacíos, precios negativos ni duplicados.  
- Si un producto ya existe, el sistema debe ofrecer la opción de **actualizar su precio o stock**.  

---

### 📋 2. Mostrar inventario  

- El sistema mostrará todos los productos registrados en formato tabla:  
  `Producto | Precio | Stock`  
- Indicar la **cantidad total de productos** y el **valor total del inventario** (precio × cantidad).  
- Si no hay productos registrados, debe indicarse con un mensaje claro.  

---

### 💸 3. Registrar venta  

- El usuario podrá realizar una venta ingresando:
  - Nombre del producto.  
  - Cantidad a vender.  
- El sistema deberá:
  - Verificar que el producto exista.  
  - Comprobar que haya suficiente stock.  
  - Descontar la cantidad vendida.  
  - Calcular el total de la venta.  
- Si el stock llega a 0, mostrar una alerta de **“Producto agotado”**.  

---

### 🗑️ 4. Eliminar producto  

- Permitir eliminar un producto del inventario.  
- Validar que el producto exista antes de borrarlo.  
- Confirmar la eliminación antes de ejecutar la acción.  

---

### 📊 5. Estadísticas  

- Mostrar:
  - El producto más caro.  
  - El producto más económico.  
  - El producto con mayor stock.  
- Si el inventario está vacío, se debe informar.  

---

### 🔚 6. Salir del sistema  

Antes de cerrar, el sistema debe imprimir un resumen con:  
- Cantidad total de productos.  
- Valor total del inventario.  
- Ventas realizadas en la sesión.  

---

### ⚙️ Requerimientos  

- Menú interactivo con al menos 6 opciones.  
- Uso obligatorio de **diccionarios anidados**.  
- Validación de todas las entradas (precios, nombres y cantidades).  
- Implementar funciones para cada acción (`agregar_producto()`, `mostrar_inventario()`, etc.).  
- Código limpio, organizado y con mensajes claros.  

---

### ⭐ Desafíos extra  

- Aplicar descuentos a ciertos productos seleccionados.  
- Mostrar los tres productos con mayor valor de stock.  
- Calcular el promedio general de precios del inventario.  

---

### ✅ Condiciones de aprobación  

| Criterio | Puntaje |
|----------|----------|
| Cumplimiento de todas las funcionalidades básicas | 6 pts |
| Uso correcto de funciones y validaciones | 8 pts |
| Implementación de desafíos extra | 10 pts |

---

---

# 🧾 4to Tecnología 2025  
## **Trabajo Práctico 2 – Tecnologías de la Información – 🚖 RideNow! – Sistema de viajes compartidos**

Una startup argentina de movilidad quiere crear un prototipo de su sistema de gestión de viajes.  
Tu tarea será desarrollar una versión inicial del programa que administre choferes, pasajeros y viajes.  

---

### 🚗 1. Registrar choferes  

- Solicitar al usuario el nombre del chofer y su patente.  
- Guardar los datos en una **lista de diccionarios**, donde cada chofer tenga esta estructura:  
  `{"nombre": "Carlos", "patente": "ABC123", "viajes": 0}`  
- No se permiten patentes repetidas ni campos vacíos.  

---

### 👥 2. Registrar pasajeros  

- El sistema permitirá ingresar los nombres de los pasajeros frecuentes.  
- Los pasajeros se guardarán en una **lista simple** sin duplicados.  
- Si el usuario intenta ingresar un nombre vacío o repetido, se mostrará un error.  

---

### 🧾 3. Asignar viaje  

- El usuario podrá seleccionar un chofer y un pasajero para crear un viaje.  
- Por cada viaje se registrará:  
  - Chofer asignado.  
  - Pasajero transportado.  
  - Precio del viaje (validar número positivo).  
- Los viajes se almacenarán en una **lista de diccionarios**, ejemplo:  
  `{"chofer": "Carlos", "pasajero": "Ana", "precio": 2500}`  
- Al asignar un viaje, el contador de viajes del chofer debe incrementarse en 1.  

---

### 📈 4. Consultas y estadísticas  

- Mostrar todos los viajes realizados.  
- Mostrar la **recaudación total** de la empresa.  
- Mostrar el chofer con **mayor cantidad de viajes**.  
- Calcular el **promedio de precio por viaje**.  

---

### 🗑️ 5. Eliminar chofer o pasajero  

- Permitir eliminar choferes o pasajeros registrados.  
- Si tienen viajes asociados, se debe advertir al usuario antes de eliminarlos.  

---

### 🔚 6. Cerrar sistema  

Antes de finalizar, mostrar un resumen general con:  
- Choferes registrados y sus viajes.  
- Pasajeros frecuentes.  
- Total de viajes y recaudación.  

---

### ⚙️ Requerimientos  

- Uso de **listas, diccionarios y bucles**.  
- Validación de datos obligatoria.  
- Código modular, con funciones separadas por tarea.  
- Menú principal con opciones claras y numeradas.  
- Presentación legible y uso de mensajes descriptivos.  

---

### ⭐ Desafíos extra  

- Mostrar el chofer con **mayores ganancias acumuladas**.  
- Agregar una opción para buscar todos los viajes realizados por un pasajero.  
- Calcular el total de kilómetros recorridos si cada viaje tiene una distancia asociada.  

---

### ✅ Condiciones de aprobación  

| Criterio | Puntaje |
|----------|----------|
| Funcionalidades básicas completas | 6 pts |
| Código estructurado y sin errores | 8 pts |
| Al menos un desafío extra | 10 pts |

---

---

# 🏦 4to Tecnología 2025  
## **Trabajo Práctico 3 – Tecnologías de la Información – 💰 SafeBank – Sistema bancario digital**

Una fintech necesita un sistema básico para administrar las cuentas de sus clientes.  
El programa debe permitir abrir cuentas, registrar movimientos, realizar transferencias y generar reportes.  

---

### 🏦 1. Crear cuentas  

- El usuario podrá crear nuevas cuentas ingresando:  
  - Nombre del titular.  
  - Número de cuenta (único).  
  - Saldo inicial (validar número positivo).  
- Las cuentas se guardarán en un **diccionario**, donde:  
  - **Clave:** número de cuenta.  
  - **Valor:** otro diccionario con los datos (`{"titular": "Juan", "saldo": 10000}`).  
- No se deben permitir números de cuenta duplicados.  

---

### 💰 2. Depositar dinero  

- Permitir ingresar un monto para sumar al saldo de una cuenta.  
- Validar que el monto sea positivo.  
- Si la cuenta no existe, mostrar un mensaje de error.  

---

### 💸 3. Extraer dinero  

- Solicitar el número de cuenta y el monto a extraer.  
- Validar que el monto sea positivo y que haya saldo suficiente.  
- Actualizar el saldo luego de la operación.  

---

### 🔄 4. Transferencias entre cuentas  

- El usuario podrá transferir dinero entre dos cuentas existentes.  
- Validar que ambas cuentas existan y que el saldo sea suficiente.  
- Registrar la operación en un **historial de movimientos** (lista de diccionarios).  
  Ejemplo: `{"origen": 1001, "destino": 1002, "monto": 5000}`  

---

### 📊 5. Consultar información  

- Mostrar todas las cuentas con su titular y saldo actual.  
- Permitir consultar los movimientos realizados por una cuenta específica.  
- Mostrar la cuenta con **mayor saldo** y la de **menor saldo**.  

---

### 🔚 6. Cerrar sesión  

Antes de finalizar, mostrar un resumen general con:  
- Total de cuentas creadas.  
- Suma total de dinero en el sistema.  
- Cantidad de transferencias realizadas.  

---

### ⚙️ Requerimientos  

- Uso obligatorio de **diccionarios anidados y listas**.  
- Múltiples funciones con nombres claros (`crear_cuenta()`, `transferir()`, etc.).  
- Validaciones en todas las operaciones (saldo, existencia de cuentas, datos vacíos).  
- Menú principal con submenús para operaciones bancarias.  
- Código ordenado, con comentarios y mensajes al usuario.  

---

### ⭐ Desafíos extra  

- Calcular el promedio de saldo entre todas las cuentas.  
- Mostrar la evolución del saldo de una cuenta luego de varias operaciones.  
- Implementar un sistema que aplique **interés mensual** al saldo de todas las cuentas.  

---

### ✅ Condiciones de aprobación  

| Criterio | Puntaje |
|----------|----------|
| Cumple con las operaciones bancarias básicas | 6 pts |
| Uso correcto de funciones y estructuras | 8 pts |
| Implementación de desafíos extra | 10 pts |
