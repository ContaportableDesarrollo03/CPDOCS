---
title: Reportes de inventario — ContaPortable
description: Resumen de categorías de reportes de inventario incluídos en ContaPortable. 
---
---
# **Reportes de inventario**

Esta página reúne el detalle de los reportes incluídos en la categoría de inventario en el sistema **ContaPortable**.

<!-- Se agrega el código mermaid para diagramar las subcategorías de inventario -->
!!! tip "Diagrama de las subcategorías contenidas en **Reportes de inventario**"
    ``` mermaid
    graph TD
      A[Reportes de inventario]:::root

      subgraph "Subcategorías"
        B[1. Movimientos]
        C[2. Documentos de inventario]
        D[3. Inventario costeado]
        E[4. Por marca y modelo]
      end

      A --> B
      A --> C
      A --> D
      A --> E

    click B "#1-movimientos" "Ir a movimientos"
    click C "#2-documentos-de-inventario" "Ir a documentos de inventario"
    click D "#3-inventario-costeado" "Ir a inventario costeado"
    click E "#4-por-marca-y-modelo" "Ir a reportes por marca y modelo"
    ```
---

!!! warning "**Recálculo de costos**"
    Es importante tomar en cuenta realizar el recálculo de costos, esto se puede realizar por medio del botón que **se señala en la imagen adjunta**, con esto se habilitará la opción **"Imprimir"**
    ![Botón "Recalcular costos"](../../assets/reportes/inventario/1.1-existences-filter.png){ .align=left }

---
## **1. Movimientos**
---

<!-- Se agrega el código mermaid para diagramar el listado de reportes dentro de la subcategoría de movimientos -->
!!! tip "Diagrama de los reportes contenidos en la subcategoría **Movimientos**"
    ``` mermaid
    graph LR
      A[Movimientos]:::root

      subgraph "Listado de reportes:"

        B[1.1 Existencias]
        C[1.2 Listado para inventario]
        D[1.3 Listado por categorías]
        E[1.4 Salidas por clientes]
        F[1.5 Existencias - Alerta de mínimos]
      end

      A --> B
      A --> C
      A --> D
      A --> E
      A --> F

    click B "#11-existencias" "Ir a reporte de existencias"
    click C "#12-listado-para-inventario" "Ir a reporte de listado para inventario"
    click D "#13-listado-por-categorias" "Ir a inventario costeado"
    click E "#14-salidas-por-clientes" "Ir a reportes por marca y modelo"
    click F "#15-existencias-alerta-de-minimos" "Ir a reportes por marca y modelo"
    ```
---

### 1.1  Existencias

!!! info "Descripción del reporte"
    Este reporte muestra las existencias para los códigos de inventario, Puede ser filtrado por medio de los siguientes parámetros:

    - Fecha
    - Código (Todos o bloques)
    - Bodega 

    Es posible exportarlo a formato Excel, ya sea de forma consolidada o detallada (Plano).

Vista previa del reporte **![Reporte de existencias](../../assets/reportes/inventario/1.1-existences-report.png){ align=left }**

??? abstract "1.1 Existencias - Descargas de ejemplo"
    - **[Descargar versión PDF :fontawesome-regular-file-pdf:](../../assets/reportes/inventario/1.1-EXISTENCES-REPORT.PDF){ .md-button }**
    - **[Descargar versión Excel (Consolidado) :material-microsoft-excel:](../../assets/reportes/inventario/1.1-EXISTENCES-REPORT_CON.xlsx){ .md-button }**
    - **[Descargar versión Excel (Plano) :material-microsoft-excel:](../../assets/reportes/inventario/1.1-EXISTENCES-REPORT_Pln.xlsx){ .md-button }**

Puedes encontrar más información en el sitio oficial de **ContaPortable** **[Enlace en sitio ContaPortable :material-web:](https://www.contaportable.com/indice/vip-modulo-contable-reportes-contables/reporte-inventario-y-facturacion/#existencia){ .md-button align=left }**

---
### 1.2  Listado para inventario

!!! info "Descripción del reporte"
    Este reporte muestra un formato apto para la toma de inventario, Puede ser filtrado por medio de los siguientes parámetros:

    - Fecha
    - Código (Todos o bloques)
    - Bodega 

    Es posible exportarlo a formato Excel, ya sea de forma consolidada o detallada (Plano).

Vista previa del reporte **![Reporte de listado para inventario](../../assets/reportes/inventario/1.2-INVENTORY-LIST-REPORT.png){ align=left }**

??? abstract "1.2 Listado para inventario - Descargas de ejemplo"
    - **[Descargar versión PDF :fontawesome-regular-file-pdf:](../../assets/reportes/inventario/1.2-INVENTORY-LIST-REPORT.PDF){ .md-button }**
    - **[Descargar versión Excel (Consolidado) :material-microsoft-excel:](../../assets/reportes/inventario/1.2-INVENTORY-LIST-REPORT_Con.xlsx){ .md-button }**
    - **[Descargar versión Excel (Plano) :material-microsoft-excel:](../../assets/reportes/inventario/1.2-INVENTORY-LIST-REPORT_Pln.xlsx){ .md-button }**

Puedes encontrar más información en el sitio oficial de **ContaPortable** **[Enlace en sitio ContaPortable :material-web:](https://www.contaportable.com/indice/vip-modulo-contable-reportes-contables/reporte-inventario-y-facturacion/#existencia){ .md-button align=left }**

---
### 1.3  Listado por categorías

**ERROR 404 - NOT FOUND**

      **[Enlace en sitio ContaPortable :material-web:](https://www.contaportable.com/indice/vip-modulo-contable-reportes-contables/reporte-inventario-y-facturacion/#existencia){ .md-button }**

---
### 1.4  Salidas por clientes

!!! info "Descripción del reporte"
    Este reporte muestra las salidas de inventario agrupadas por cliente y únicamente se exporta a formato Excel, ya sea de forma consolidada o detallada (Plano), Puede ser filtrado por medio de los siguientes parámetros:

    - Rango de fechas
    - Código (Todos o bloques)
    - Bodega
    - Departamento

Vista previa del reporte **![Reporte de salidas por clientes](../../assets/reportes/inventario/1.4-SALES-BY-CUSTOMER.png){ align=left }**

??? abstract "1.4 Salidas por clientes - Descargas de ejemplo"
    - **[Descargar versión Excel (Consolidado) :material-microsoft-excel:](../../assets/reportes/inventario/1.4-SALES-BY-CUSTOMER_CON.xlsx){ .md-button }**
    - **[Descargar versión Excel (Plano) :material-microsoft-excel:](../../assets/reportes/inventario/1.4-SALES-BY-CUSTOMER_PLN.xlsx){ .md-button }**

---
### 1.5  Existencias (Alerta de mínimos)

!!! info "Descripción del reporte"
    Este reporte muestra un formato que sirve como alerta de mínimos y máximos de existencias configuradas para los códigos de inventario, Puede ser filtrado por medio de los siguientes parámetros:

    - Fecha
    - Código (Todos o bloques)
    - Bodega 

    Es posible exportarlo a formato Excel, ya sea de forma consolidada o detallada (Plano).

Vista previa del reporte **![Reporte de existencias (Alerta de mínimos)](../../assets/reportes/inventario/1.5-EXISTENCES-MIN-ALERT.png){ align=left }**

??? abstract "1.5 Existencias (Alerta de mínimos) - Descargas de ejemplo"
    - **[Descargar versión PDF :fontawesome-regular-file-pdf:](../../assets/reportes/inventario/1.5_EXISTENCES_MIN_ALERT.PDF){ .md-button }**
    - **[Descargar versión Excel (Consolidado) :material-microsoft-excel:](../../assets/reportes/inventario/1.5_EXISTENCES_MIN_ALERT_CON.xlsx){ .md-button }**
    - **[Descargar versión Excel (Plano) :material-microsoft-excel:](../../assets/reportes/inventario/1.5_EXISTENCES_MIN_ALERT_PLN.xlsx){ .md-button }**


## **2. Documentos de inventario**

### Movimientos de inventario con lote y fecha de vencimiento
- **Video (Loom):** https://www.loom.com/i/857823073cc14e8995566696234b0647

---

## **3. Inventario costeado**

---

## **4. Por marca y modelo**

### 4.1 Reporte de inventario — Marca y modelo

> **Resumen:** Este reporte incluye selectores de **marca** y **modelo** que permiten establecer bloques (comportamiento similar a ...).  
> **Nota:** El documento original continúa con más detalles sobre el comportamiento y filtros del reporte; el texto fuente visible quedó truncado en la copia disponible. Para revisar el contenido completo remítase al archivo original. :contentReference[oaicite:2]{index=2}

---