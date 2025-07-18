Este script busca todos los tickets en estado "Importado" (estado = 8) y los carga en la tabla `sw_colaEnvioMail` para su posterior envío por correo. Si el ticket ya está en esa cola, lo actualiza para que vuelva a intentarse el envío. Maneja errores críticos enviando alertas por mail.

[[cron_tickets_cola_envio.php]]