Dashboard de Conciliación Bancaria
Dashboard interactivo en Power BI que automatiza la detección y clasificación de partidas conciliatorias entre el Libro Bancos y el Estado de Cuenta Bancario.
¿Qué problema resuelve?
La conciliación bancaria manual implica cruzar dos fuentes de datos fila por fila. Este dashboard hace el cruce automáticamente, clasifica cada movimiento y muestra exactamente por qué no cuadran los saldos, sin necesidad de leer un solo texto explicativo.
¿Qué muestra?

Saldo según libros vs saldo según banco
Partidas en libros no registradas en banco
Partidas en banco no registradas en libros
Diferencia conciliatoria verificada = S/ 0.00
Clasificación automática por tipo de partida

Metodología
El cruce se realiza mediante un merge externo completo entre ambas fuentes por fecha y monto. Power Query clasifica cada movimiento según su origen y estado. Las métricas DAX calculan los saldos ajustados y verifican el cierre.
Modelo de datos
3 tablas relacionadas con tabla puente para el cruce:

Libro Bancos
Estado de Cuenta Bancario
Tabla de clasificación de partidas

Herramientas
Power BI · DAX · Power Query · Excel
Resultado
Diferencia conciliatoria final: S/ 0.00
