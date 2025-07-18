Este script busca operaciones activas que no hayan tenido un cambio de estado significativo en las últimas 72 o 120 horas, dependiendo del producto. Para eso, consulta las operaciones y sus últimas modificaciones, aplicando filtros como estado, vendedor, producto y fechas.

Si encuentra operaciones sin cambios en ese período, revisa el historial completo de modificaciones para esa operación. Si alguna modificación tiene estado 37, cambia el estado de la operación a 1; si no, mantiene el estado 37 y asigna un vendedor específico (89) o el último vendedor registrado en el historial.

Luego actualiza la operación con el nuevo estado, vendedor, fecha y hora actuales, y registra esta actualización como una nueva entrada en la tabla de modificaciones para mantener el historial.

[[Crons]]