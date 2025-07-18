Este cron detecta operaciones que están en estado 40 y cuya última gestión (`fechauc`) ocurrió hace más de un día. Estas operaciones se consideran caducadas por falta de seguimiento. El script actualiza cada una de ellas, restableciendo su estado a 1 y asignando un motivo de baja (código 39). Luego, genera un reporte en HTML con los detalles de las operaciones procesadas y lo envía por correo a `cron@seguroweb.com.ar`.

Es una **tarea de mantenimiento automático** para limpiar o resetear operaciones estancadas en el sistema.

[[Crons]]