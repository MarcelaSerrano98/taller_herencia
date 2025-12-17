# Taller de Herencia en Java

Este proyecto contiene 10 ejercicios prácticos sobre **herencia en Java**, demostrando conceptos clave como:
- Herencia simple
- Sobrescritura de métodos
- Clases abstractas
- Polimorfismo
- Uso de `super`
- Constructores en herencia

---

## 📋 Ejercicios del Taller

### **Ejercicio 1: Vehicle y Car**
- **Clases**: `Vehicle`, `Car`
- **Concepto**: Herencia básica
- **Descripción**: `Vehicle` tiene el método `move()`. `Car` hereda de `Vehicle` y agrega el método `honk()`

### **Ejercicio 2: Person y Student**
- **Clases**: `Person`, `Student`
- **Concepto**: Herencia con atributos adicionales
- **Descripción**: `Person` tiene `name` y `age`. `Student` hereda y agrega `grade` y el método `study()`

### **Ejercicio 3: Animal, Dog y Cat**
- **Clases**: `Animal`, `Dog`, `Cat`
- **Concepto**: Sobrescritura de métodos (Override)
- **Descripción**: `Animal` tiene `makeSound()`. `Dog` lo sobrescribe para decir "Woof" y `Cat` para decir "Meow"

### **Ejercicio 4: Employee y Manager**
- **Clases**: `Employee`, `Manager`
- **Concepto**: Herencia con atributos privados
- **Descripción**: `Employee` tiene `name` y `salary`. `Manager` hereda y agrega `department`

### **Ejercicio 5: Clase Abstracta Shape**
- **Clases**: `Shape` (abstracta), `Circle`, `Rectangle`
- **Concepto**: Clases abstractas y métodos abstractos
- **Descripción**: `Shape` es abstracta con método `calculateArea()`. `Circle` y `Rectangle` implementan este método

### **Ejercicio 6: Bird y Eagle con super**
- **Clases**: `Bird`, `Eagle`
- **Concepto**: Uso de `super` para llamar método de la clase padre
- **Descripción**: `Eagle` sobrescribe `fly()` pero también llama a `super.fly()` para ejecutar el método original

### **Ejercicio 7: Device y Phone**
- **Clases**: `Device`, `Phone`
- **Concepto**: Constructores en herencia
- **Descripción**: `Device` imprime "Device created" en su constructor. `Phone` hereda y imprime "Phone ready"

### **Ejercicio 8: Account y SavingsAccount**
- **Clases**: `Account`, `SavingsAccount`
- **Concepto**: Herencia con métodos del padre
- **Descripción**: `Account` tiene `deposit()` y `withdraw()`. `SavingsAccount` hereda y agrega `addInterest()`

### **Ejercicio 9: Vehicle, Car, Bike y Truck**
- **Clases**: `Vehicle`, `Car`, `Bike`, `Truck`
- **Concepto**: Polimorfismo con `describe()`
- **Descripción**: Las tres subclases sobrescriben `describe()` para describirse a sí mismas

### **Ejercicio 10: ArrayList con Polimorfismo**
- **Clases**: `Animal`, `Dog`, `Cat`, `Bird`
- **Concepto**: Polimorfismo en colecciones
- **Descripción**: Se crea un `ArrayList<Animal>` que contiene instancias de `Dog`, `Cat` y `Animal`. Se recorre la lista y se llama a `makeSound()` en cada elemento

---

## 🏗️ Estructura del Proyecto

```
src/main/java/com/marce/
├── Animal.java
├── Account.java
├── Bird.java
├── Bike.java
├── Car.java
├── Cat.java
├── Circle.java
├── Device.java
├── Dog.java
├── Eagle.java
├── Employee.java
├── Main.java
├── Manager.java
├── Person.java
├── Phone.java
├── Rectangle.java
├── SavingsAccount.java
├── Shape.java
├── Student.java
├── Truck.java
└── Vehicle.java
```

---

## 🚀 Cómo Ejecutar

### Compilar el proyecto:
```bash
mvn clean compile
```

### Ejecutar el programa principal:
```bash
mvn exec:java -Dexec.mainClass="com.marce.Main"
```

O desde la terminal:
```bash
java -cp target/classes com.marce.Main
```

---

## 📝 Salida Esperada

Al ejecutar `Main.java`, verás la salida de todos los 10 ejercicios demostrando:
- Herencia simple
- Métodos sobrescritos
- Uso de constructores heredados
- Clases abstractas e implementaciones
- Polimorfismo en acción
- ArrayList con instancias polimórficas

---

## 💡 Conceptos Clave Aprendidos

1. **Herencia**: Una clase hija hereda atributos y métodos de una clase padre
2. **Override (@Override)**: Sobrescribir métodos de la clase padre
3. **super**: Acceder a métodos y constructores de la clase padre
4. **Clases Abstractas**: Clases que no pueden instanciarse, solo heredarse
5. **Polimorfismo**: Un objeto puede referenciarse como su clase padre pero ejecutar métodos de su clase real
6. **Constructores en herencia**: Llamar a constructores del padre con `super()`

---

## 📚 Autor

Taller de Herencia en Java - Campus JAVA - Laura Marcela Albarracin Serrano 


