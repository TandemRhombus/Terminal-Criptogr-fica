# Terminal-Criptografica

## ESTRUCTURA DE ENTREGA (DOCUMENTO PDF/WORD)

### **PORTADA (2%)**

**Universidad Autónoma de Aguascalientes** **Materia:** Seguridad en Sistemas

**Profesor:** Arturo Ocampo Silva

**Alumno:** Sergio Emiliano Hernández Villalpando

**ID:** 345849

**Proyecto:** Desarrollo de Sistema de Cifrado César y Atbash

**Fecha de entrega:** 20/02/2026

---

### **ÍNDICE (2%)**

1. Introducción
2. Objetivo
3. Desarrollo (80%)
3.1. Lógica y Código Base ASCII
3.2. Documentación Segura del Código (Método Atbash)
4. Conclusión
5. Bibliografía

---

### **INTRODUCCIÓN (5%)**

Como se analizó en clase, la protección de la información ha sido una prioridad humana desde la creación del lenguaje escrito. Métodos como el **Cifrado César** y el **Atbash** fueron los pilares de la criptografía de sustitución.

Sin embargo, estos sistemas perdieron su eficacia debido a los estudios de **أبو يوسف يعقوب بن إسحاق الكندي** (Al-Kindi). En el siglo IX, Al-Kindi sentó las bases del hackeo de sistemas de encriptación simples mediante la invención del **análisis de frecuencias**. Al-Kindi demostró que cada letra de un idioma aparece con una frecuencia estadística previsible; al mapear estas frecuencias en un texto cifrado, se puede deducir el mensaje original sin conocer la clave. Debido a esto, el uso de César y Atbash ya no es viable hoy en día; la capacidad de procesamiento moderna permite realizar ataques de fuerza bruta y análisis estadísticos en milisegundos, haciendo que estos métodos sean vulnerables ante cualquier auditoría de seguridad computacional.

---

### **OBJETIVO (3%)**

Desarrollar una aplicación web funcional que implemente los algoritmos César y Atbash utilizando una base ASCII personalizable, aplicando una estrategia de documentación técnica segura para proteger la lógica operativa del sistema.

---

### **DESARROLLO (80%)**

#### **3.1. Lógica y Código Base ASCII (65%)**

El programa utiliza una arquitectura web basada en HTML5 y JavaScript. La lógica central se basa en la manipulación de índices sobre un conjunto de caracteres (alfabeto) que el usuario puede alimentar dinámicamente.

Cifrado César: Se aplica un desplazamiento matemático modular sobre la posición del carácter en el alfabeto:$$E(x) = (x + n) \pmod m$$

Cifrado Atbash: Se realiza una inversión simétrica de los índices:$$E(x) = (m - 1) - x$$Donde $x$ es el índice del carácter original, $n$ es el desplazamiento (módulo), y $m$ es la longitud total de tu conjunto de caracteres.

.
* **Interfaz:** Se utiliza la biblioteca **GSAP** para animar el contenedor y los campos de salida, proporcionando un feedback visual profesional.

#### **3.2. Documentación Segura (15%)**

Para cumplir con el requerimiento de documentación segura mediante el uso del ingenio, la descripción técnica de las funciones críticas ha sido cifrada. El siguiente "Diccionario de Referencia" explica el funcionamiento de las etiquetas `[REF-TIPO-X]` insertadas en el código fuente.

> **Nota para el revisor:** Las descripciones técnicas en la siguiente tabla han sido cifradas mediante el algoritmo **Atbash**. Para leer la documentación, copie el texto de la columna "Descripción (Cifrada)" y utilice el módulo Atbash del software entregado.

| Referencia en Código | Descripción Técnica (Cifrada con Atbash) |
| --- | --- |
| **[REF-TIPO-1]** | ,oZoElkE?nWVXommgóbElkE.oVaW:E,oZVUXoEgbZUVWElkdE.02EQEWobgVgPoEkdEcólUdaE,éWoXEoEkbVkXaE(ZoXWk6bV)EZoXoEkTgVoXEgbQkmmgabkWElkEWVXgbiWD |
| **[REF-TIPO-2]** | !UmdkElkE6VkXomgóbE3gbkod:ExkmaXXkEdoEmolkboElkEkbVXoloEmoXámVkXEZaXEmoXámVkXEmabEmacZdkfglolE$0(b)$D |
| **[REF-TIPO-3]** | 2ólUdaElkEtodglomgóbElkE?djonkVa:EtkXgjgmoEWgEkdEmoXámVkXEkRgWVkEkbEkdEmabfUbVaEnoWk;EWgEbaCEoZdgmoEUbEnQZoWWElkEWkiUXglolEZoXoEcobVkbkXEdoEgbVkiXglolElkdEckbWofkD |
| **[REF-TIPO-4]** | 2aVaXElkE.kWZdoPocgkbVaE,gXmUdoX:E6cZdkckbVoEdoEdóigmoE,éWoXEmabEmaXXkmmgóbEZoXoEíblgmkWEbkioVgTaWElUXobVkEkdElkWmgjXolaD |
| **[REF-TIPO-5]** | 2aVaXElkE WZkfaEwgcéVXgma:E fkmUVoEdoEdóigmoE?VnoWhEgbTgXVgkblaEkdEíblgmkEnoWolaEkbEdoEdabigVUlElkdEnUjjkXElkEmoXomVkXkWD |
| **[REF-TIPO-6]** | .gWZoVmhEQE?bgcomgóbE8w?z:E6bQkmVoEkdEXkWUdVolaEkbEkdE.02EQElgWZoXoEdoEobgcomgóbElkEmabjgXcomgóbETgWUodD |

---

### **CONCLUSIÓN (5%)**

El desarrollo de este motor criptográfico demuestra que la seguridad no puede basarse únicamente en algoritmos de sustitución. Al implementar la lógica de Al-Kindi, comprendemos la necesidad de sistemas de encriptación más robustos y la importancia de técnicas como la ofuscación de la documentación para proteger la propiedad intelectual de un desarrollo.

---

### **BIBLIOGRAFÍA (3%)**

* Al-Kindi. (Siglo IX). *Manuscrito sobre el desciframiento de mensajes*.
* Singh, S. (1999). *The Code Book*. Anchor Books.
* GSAP. (2024). *GreenSock Animation Documentation*. Recuperado de greensock.com.
