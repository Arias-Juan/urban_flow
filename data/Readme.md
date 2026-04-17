
### Conclusión

Tras la limpieza y normalización del dataset histórico de multas por exceso
de velocidad de Vaalserberg, se obtuvieron 1713 registros válidos de los
4000 originales.

Del total de infracciones válidas, 453 (26.44%) conservan la fecha por
defecto 1932-01-01 y 339 (19.79%), la hora por defecto 00:00, lo que indica
que una porción significativa de los registros del sistema heredado llegaba
con datos de fecha y hora incompletos o corruptos.

Las infracciones se concentran en tres vías principales: AV LIBERTADOR
con 708 multas, AV SIEMPRE VIVA con 512 y RUTA 9 con 493. Las velocidades
máximas permitidas en estas vías son de 40, 60 y 80 km/h.

Estos resultados evidencian que el sistema anterior no contaba con
validaciones de formato en el ingreso de datos, generando inconsistencias
en fechas, horas, ubicaciones y patentes.
