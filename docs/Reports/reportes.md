# Reportes

Se explica uso y organización de reportes en **contaportable**.

## Archivos

1. **Definereport.prg**: Se creó para poder iniciar el traslado de todos los reportes a código.
2. Contiene dos clases principales: Reportes.

??? note "Clases Statement contenidas en DefineReport.prg"
    1. StatementSTM: Reportes de sistema.
    2. StatementINV: [Reportes de inventario] (categorias/Inventario.md)
    3. StatementCLI: Reportes de cliente.
    4. StatementIVA: Reportes de iva.
    5. StatementReportListener: Actúa como controlador de errores

- REPORTS\Report.sc2 Se usa para invocar las clases Statement y setear la parametrería de los reportes
