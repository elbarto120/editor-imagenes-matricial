# Documentación de Ejercicios - Gael Magaña Chan

## Información General
- **Materia:** Fundamentos de Álgebra  
- **Tema:** Determinantes y Propiedades del Determinante  
- **Fecha:** 18/11/2025  
- **Estudiante:** Gael Magaña Chan  
- **Grupo:** 1A

---

## Objetivo de la Documentación
Este documento explica y desarrolla los ejercicios vistos en clase sobre **determinantes**, utilizando métodos como:  
- Determinantes 2×2  
- Regla de Sarrus  
- Cofactores  
- Verificación de propiedades del determinante  
- Aplicaciones geométricas  

Incluye procedimientos claros y resultados finales para cada ejercicio.

---

# Ejercicios Realizados

---

## ### Ejercicio 1: Determinantes 2×2

### **Enunciado**

Calcular los determinantes de las matrices:

$$
A=\begin{pmatrix}
5 & 2 \\
3 & 1
\end{pmatrix},
\quad
B=\begin{pmatrix}
-1 & 4 \\
2 & -8
\end{pmatrix},
\quad
C=\begin{pmatrix}
6 & 9 \\
2 & 3
\end{pmatrix},
\quad
D=\begin{pmatrix}
0 & 5 \\
-5 & 0
\end{pmatrix}
$$

### **Solución**

Usamos la fórmula:

$$
\det\begin{pmatrix}a & b \\ c & d\end{pmatrix}=ad-bc
$$

- **det(A) = 5(1) − 2(3) = -1**  
- **det(B) = (-1)(-8) − 4(2) = 0**  
- **det(C) = 6(3) − 9(2) = 0**  
- **det(D) = 0(0) − 5(-5) = 25**  

### **Resultado Final**
- det(A) = **-1**  
- det(B) = **0**  
- det(C) = **0**  
- det(D) = **25**

---

## ### Ejercicio 2: Regla de Sarrus (Determinante 3×3)

### **Enunciado**

$$
E=\begin{pmatrix}
1 & 2 & 3 \\
0 & 1 & 4 \\
5 & 6 & 0
\end{pmatrix},
\quad
F=\begin{pmatrix}
2 & -1 & 3 \\
1 & 4 & 0 \\
3 & 2 & -2
\end{pmatrix}
$$

### **Proceso**
Aplicar la regla de Sarrus extendiendo las dos primeras columnas.

---

### **Solución E**

Diagonal positiva:  
1·1·0 + 2·4·5 + 3·0·6 = 40  

Diagonal negativa:  
3·1·5 + 2·0·0 + 1·4·6 = 39  

**Det(E) = 40 − 39 = 1**

---

### **Solución F**

Diagonal positiva:  
2·4·(-2) + (-1)·0·3 + 3·1·2 = -10  

Diagonal negativa:  
3·4·3 + 2·0·2 + (-1)·1·(-2) = 38  

**Det(F) = -10 − 38 = -48**

---

## ### Ejercicio 3: Método de Cofactores

### **Enunciado**

$$
G=\begin{pmatrix}
1 & 0 & 2 \\
-1 & 3 & 1 \\
2 & 0 & 1
\end{pmatrix}
$$

### **Proceso**
Expansión por la columna con más ceros (columna 2).

### **Solución**

$$
\det(G)=
3\begin{vmatrix}
1 & 2 \\
2 & 1
\end{vmatrix}
$$

Menor:

1·1 − 2·2 = -3  

Entonces:

**det(G) = 3(-3) = -9**

---

## ### Ejercicio 4: Verificar propiedades del determinante

Matrices:

$$
A=\begin{pmatrix}
2 & 1 \\
1 & 3
\end{pmatrix},
\quad
B=\begin{pmatrix}
1 & 2 \\
3 & 1
\end{pmatrix}
$$

---

### **Propiedad 1: det(AB) = det(A)·det(B)**

- det(A) = 5  
- det(B) = -5  

det(A)·det(B) = **-25**

Multiplicamos:

$$
AB=
\begin{pmatrix}
2(1)+1(3) & 2(2)+1(1) \\
1(1)+3(3) & 1(2)+3(1)
\end{pmatrix}
=
\begin{pmatrix}
5 & 5 \\
10 & 5
\end{pmatrix}
$$

Determinante:

$$
5·5 - 5·10 = -25
$$

✔ **Se verifica la propiedad**

---

### **Propiedad 2: det(Aᵀ) = det(A)**

La transpuesta no cambia el determinante:

**det(Aᵀ) = 5 = det(A)** ✔

---

## ### Ejercicio 5: Aplicación geométrica

Vectores:

$$
\vec{u}=(3,2),\quad \vec{v}=(1,4)
$$

### a) Área del paralelogramo

Se calcula con:

$$
\text{Área}=\left|\det\begin{pmatrix}
3 & 1 \\
2 & 4
\end{pmatrix}\right|
$$

Determinante:

3·4 − 1·2 = **10**

**Área = 10 unidades²**

---

### b) ¿Cambia el área si intercambiamos los vectores?

El determinante cambia de signo, pero el área es valor absoluto.

✔ **El área no cambia.**

---

### c) ¿Qué representa el signo del determinante?

- Signo positivo → orientación antihoraria  
- Signo negativo → orientación horaria  

Representa la **orientación** entre vectores.

---

# ✔ Documento completado correctamente
       
