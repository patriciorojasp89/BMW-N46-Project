# 📝 LOGBOOK DEL PROYECTO

> Este documento almacena los avances importantes del proyecto.
>
> Su objetivo es responder:
>
> * ¿Qué ha ocurrido durante el diagnóstico?
> * ¿Qué resultados se obtuvieron?
> * ¿Cómo afectaron al proyecto?
>
> No se registran conversaciones, ideas o consultas.
>
> Solamente hechos relevantes y verificables.

---

# 📌 Reglas del proyecto

Cada entrada debe representar un avance significativo.

Las entradas nunca se eliminan.

Las entradas históricas no se modifican.

Las conclusiones deben basarse en evidencia obtenida durante el proyecto.

---

# 📅 Entrada 001

## Objetivo

Iniciar un sistema estructurado de documentación técnica del proyecto.

---

## Acción realizada

Se creó el repositorio técnico del proyecto y se definió una metodología de trabajo asistida por IA.

---

## Resultado

Se estableció una estructura documental para registrar el estado del proyecto, las hipótesis, las próximas acciones y los avances relevantes.

---

## Conclusión

El proyecto cuenta con una base organizada para gestionar futuros diagnósticos y decisiones técnicas.

---

## Impacto en el proyecto

🟢 Reduce la incertidumbre organizacional.

🟢 Facilita el seguimiento del diagnóstico.

🟢 Mejora la trazabilidad de futuras decisiones.

---

## Archivos potencialmente relacionados

README.md

STATUS.md

HYPOTHESES.md

NEXT_ACTIONS.md

---

# 📅 Entrada 002

## Objetivo

Evaluar el funcionamiento del sistema Valvetronic mediante Tool32 durante el arranque y posterior al intento de arranque.

---

## Acción realizada

Se ejecutaron pruebas y lecturas relacionadas con el Valvetronic usando Tool32.

Se observaron valores de posición objetivo y posición real del sistema Valvetronic durante el arranque y después del intento de arranque.

También se ejecutó una rutina de aprendizaje/adaptación de topes del sistema Valvetronic.

---

## Mediciones observadas

* Posición objetivo Valvetronic aproximada: 49.6°.
* Posición real Valvetronic aproximada: 50.0°.
* Diferencia aproximada entre objetivo y posición real: 0.39°.
* Tensión observada en el sistema: aproximadamente 12.6 V.
* El motor Valvetronic respondió a comandos directos del DME.
* La rutina de aprendizaje/adaptación finalizó sin errores.
* El sistema mostró conocimiento de topes mínimo y máximo.

---

## Limitación de la prueba

No fue posible observar el comportamiento del Valvetronic en ralentí estable, ya que el motor continúa apagándose después de aproximadamente un segundo.

---

## Resultado

La evidencia obtenida indica que el sistema Valvetronic responde, se posiciona de forma coherente y completa la adaptación sin errores bajo las condiciones de prueba disponibles.

---

## Conclusión

La hipótesis de una falla principal en el motor Valvetronic, sensor excéntrico o aprendizaje de topes queda significativamente debilitada.

El sistema Valvetronic no se considera actualmente la causa principal más probable del síntoma, aunque no queda descartado de forma absoluta debido a la ausencia de una prueba en ralentí estable.

---

## Impacto en el proyecto

🟢 Reduce la probabilidad de falla principal en Valvetronic.

🟢 Permite bajar la prioridad de esta línea de investigación.

🟡 Mantiene pendiente la observación en ralentí estable si el motor logra permanecer funcionando en futuras pruebas.

---

## Archivos potencialmente relacionados

STATUS.md

HYPOTHESES.md

NEXT_ACTIONS.md

---

# 📅 Entrada 003

## Objetivo

Registrar nuevas observaciones del sistema VANOS durante el arranque y documentar el intercambio de solenoides VANOS como prueba de descarte.

---

## Acción realizada

Se observaron valores de posición de árboles de levas y posiciones VANOS antes, durante y después del arranque.

También se intercambiaron los solenoides VANOS de admisión y escape para evaluar si el comportamiento anómalo seguía al componente.

---

## Mediciones observadas

Antes del arranque:

* Camshaft position exhaust: aproximadamente 60.30.
* Camshaft position inlet: aproximadamente 661.10.
* VANOS position inlet: 120.
* VANOS position exhaust: aproximadamente 113.70.
* VANOS inlet setpoint: 120.

Después del arranque:

* Camshaft position exhaust: aproximadamente 61 y variando.
* Camshaft position inlet: aproximadamente 121.80 y variando.
* VANOS position inlet: 120 sin variación.
* VANOS position exhaust: aproximadamente 33.10 y variando.
* VANOS inlet setpoint: 120 antes, durante y después del arranque, sin variación.

---

## Prueba adicional

Se intercambiaron los solenoides VANOS de admisión y escape.

Después del intercambio, el sistema mantuvo el mismo patrón observado:

* VANOS de admisión permaneció en 120.
* Setpoint del VANOS de admisión permaneció en 120.
* VANOS de escape continuó variando.

---

## Resultado

El comportamiento observado no siguió al solenoide intercambiado.

Esto reduce la probabilidad de que la causa principal sea un solenoide VANOS individual defectuoso.

La observación más relevante es que el VANOS de admisión mantiene tanto posición real como setpoint en 120 antes, durante y después del arranque.

---

## Interpretación

La evidencia actual sugiere que el DME no está solicitando movimiento del VANOS de admisión bajo las condiciones actuales de arranque.

Esto diferencia el problema de un escenario donde el DME solicita movimiento pero el mecanismo no responde.

La pregunta principal pasa a ser por qué el DME mantiene el setpoint del VANOS de admisión fijo en 120.

---

## Limitaciones de la prueba

No se ha confirmado si 120 representa una posición normal de arranque, una posición de seguridad, un límite de escala o una condición interna de control.

Tampoco se ha medido presión real de aceite, por lo que el cambio de aceite realizado previamente no confirma presión hidráulica correcta.

---

## Conclusión

La hipótesis de solenoide VANOS de admisión defectuoso queda debilitada.

La línea de investigación debe orientarse a determinar si el control del VANOS de admisión está inhibido por estrategia, condición previa, sincronización, presión hidráulica o porque el motor no alcanza a salir de la fase de arranque.

---

## Impacto en el proyecto

🟢 Reduce la probabilidad de falla individual del solenoide VANOS de admisión.

🟡 Mantiene activa la investigación sobre estrategia VANOS de admisión.

🟡 Refuerza la necesidad de buscar estados de activación, sincronización y condiciones de habilitación del control VANOS.

---

## Archivos potencialmente relacionados

STATUS.md

HYPOTHESES.md

NEXT_ACTIONS.md

---

# 📌 Próxima entrada

Pendiente del siguiente avance técnico significativo del proyecto.
