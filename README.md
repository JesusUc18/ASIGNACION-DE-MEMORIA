# Tecnológico de Software
## Materia: Sistemas Operativos
## Alumnos: Jesús Omar Uc Domínguez - Venus Getsemani Semino Alemán - Roberto Balmes Solís - Mario Alberto De la Fuente Ruiz
## Docente: Jorge Javier Pedroza Romero
## Actividad: PUNTOS ADICIONALES: Simulador HTML Interactivo

---

# 🖥️ Simulador de Algoritmos de Asignación de Memoria

Simulador interactivo que compara los algoritmos **Best Fit** y **Worst Fit** para la asignación de memoria en sistemas operativos.

## 📋 Descripción

Este proyecto es una herramienta educativa que permite visualizar y comparar cómo funcionan dos algoritmos clásicos de asignación de memoria. Los usuarios pueden crear bloques de memoria, agregar procesos y observar en tiempo real cómo cada algoritmo gestiona la asignación de recursos.

## ✨ Características

- **Comparación en tiempo real** entre Best Fit y Worst Fit
- **Visualización interactiva** del estado de la memoria
- **Estadísticas de fragmentación** para cada algoritmo
- **Interfaz intuitiva** con diseño moderno y responsivo
- **Métricas de rendimiento** que muestran la eficiencia de cada algoritmo

## 🎯 Algoritmos Implementados

### Best Fit (Mejor Ajuste)
- Busca el bloque de memoria **más pequeño** que pueda contener el proceso
- **Ventaja:** Minimiza el espacio desperdiciado
- **Desventaja:** Puede generar muchos fragmentos pequeños

### Worst Fit (Peor Ajuste)
- Busca el bloque de memoria **más grande** disponible
- **Ventaja:** Deja fragmentos más grandes que pueden ser útiles después
- **Desventaja:** Puede desperdiciar espacio en bloques grandes

## 🚀 Cómo usar

### Paso a paso:

1. **Agregar bloques de memoria:**
   - Ingresa el tamaño del bloque en KB en el campo "Tamaño del bloque"
   - Haz clic en "Agregar Bloque"
   - El simulador inicia con 4 bloques predeterminados: 200 KB, 150 KB, 300 KB y 100 KB

2. **Crear procesos:**
   - Ingresa el tamaño del proceso en KB en el campo "Tamaño del proceso"
   - Haz clic en "Agregar Proceso"
   - El proceso se agregará a la lista de espera

3. **Asignar procesos:**
   - Haz clic en "Asignar Proceso" para que ambos algoritmos asignen el siguiente proceso en espera
   - Observa cómo cada algoritmo selecciona diferentes bloques de memoria

4. **Observar resultados:**
   - **Bloques verdes:** Memoria libre disponible
   - **Bloques morados:** Memoria asignada a un proceso
   - **Lista de procesos:** Muestra qué procesos están asignados (✓) o esperando (⏳)

5. **Analizar estadísticas:**
   - Revisa el porcentaje de fragmentación de cada algoritmo
   - Compara la cantidad de procesos asignados exitosamente
   - Observa las barras de memoria utilizada vs libre

6. **Reiniciar:**
   - **"Liberar Todo":** Desasigna todos los procesos pero mantiene los bloques de memoria
   - **"Reiniciar Memoria":** Elimina todo y vuelve a la configuración inicial

