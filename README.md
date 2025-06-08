# Proyecto: Topologías en Mininet

Este repositorio documenta las pruebas realizadas con el simulador de redes Mininet en una máquina virtual con Ubuntu. Se probaron diferentes topologías de red utilizando comandos de consola, y se incluyen capturas de pantalla de cada una de las topologías generadas.

---

## 1. Topología tipo Árbol

**Comando ejecutado:**

sudo mn --topo tree,4,3

**Descripción:**

- Crea una red en forma de árbol con:
  - 4 niveles de profundidad (de raíz a hojas).
  - 3 hijos por nodo.
- Esta topología simula una jerarquía común en redes grandes como las empresariales o de centros de datos.

**Resultado:**

Se generan múltiples switches y hosts organizados jerárquicamente.


---

## 2. Topología tipo Lineal

**Comando ejecutado:**

sudo mn --topo linear,5,4

**Descripción:**

- Crea una red lineal con:
  - 5 switches conectados en serie.
  - 4 hosts por switch.
- Útil para simular redes en cadena, como trenes de producción o dispositivos conectados punto a punto.

**Resultado:**

Una fila de switches, cada uno con sus respectivos hosts.


---

## 3. Topología tipo Toroide (Torus)

**Comando ejecutado:**

sudo mn --topo torus,3,4,5

**Descripción:**

- Genera una red con forma de toroide con:
  - 3 filas.
  - 4 columnas.
  - 5 hosts por nodo de la malla.
- Ideal para simular redes distribuidas o interconexiones de alto rendimiento como las de supercomputadoras.

**Resultado:**

Una malla conectada donde los extremos también se enlazan formando un anillo 2D.



---

## 📁 Archivos en este repositorio

- comandos_mininet.txt: contiene los comandos ejecutados.

---

## 🧪 Objetivo

El objetivo de esta práctica fue aprender a generar y visualizar diferentes tipos de topologías de red usando Mininet, así como documentar y controlar versiones del trabajo usando Git y GitHub.

---

## 🛠️ Requisitos

- Ubuntu (en VM o físico)
- Mininet instalado
- Git instalado
- Cuenta en GitHub

---

## 🔗 Enlaces útiles

- Documentación oficial de Mininet: http://mininet.org
- Comandos comunes de Mininet: http://mininet.org/walkthrough/
- Guía de uso de Git y GitHub: https://docs.github.com/
