# 🧩 HYPOTHESES DEL PROYECTO

> Este documento almacena las principales líneas de investigación del proyecto.
>
> Su objetivo es responder:
>
> * ¿Qué creemos actualmente?
> * ¿Por qué lo creemos?
> * ¿Qué falta demostrar?
>
> Las hipótesis representan posibilidades técnicas y no conclusiones definitivas.
>
> Toda hipótesis debe estar respaldada por evidencia u observaciones objetivas.
>
> Una hipótesis nunca se elimina del proyecto.

---

# 🚦 Estados posibles

🟡 Activa

🟢 Confirmada

🔴 Descartada

⚪ Suspendida

---

# 🎯 Línea de Investigación 1

## Sistema Valvetronic

Estado:

⚪ Suspendida

Prioridad:

Baja

Observaciones relevantes:

* Se ejecutaron pruebas mediante Tool32 durante el arranque y posterior al intento de arranque.
* Los valores de posición objetivo y posición real mostraron una diferencia aproximada de 0.39°.
* El motor Valvetronic respondió a comandos directos del DME.
* La rutina de aprendizaje/adaptación finalizó sin errores.
* El sistema demuestra conocimiento de topes mínimo y máximo.
* No se dispone de observación en ralentí estable debido a que el motor continúa apagándose después de aproximadamente un segundo.

Interpretación actual:

La evidencia disponible debilita significativamente la hipótesis de una falla principal en el motor Valvetronic, sensor excéntrico o proceso de adaptación.

El sistema presenta un comportamiento compatible con funcionamiento normal bajo las condiciones de prueba disponibles.

Qué falta demostrar:

* Comportamiento del sistema durante ralentí estable.
* Verificación adicional únicamente si aparecen nuevos síntomas o evidencia contradictoria.

Conclusión actual:

El sistema Valvetronic no se considera actualmente la causa principal más probable de la falla.

La hipótesis permanece documentada pero suspendida hasta la aparición de nueva evidencia objetiva.

---

# 🎯 Línea de Investigación 2

## Estrategia VANOS

Estado:

🟡 Activa

Prioridad:

Alta

Observaciones relevantes:

* Existen comportamientos observados durante el diagnóstico que justifican mantener esta línea de investigación.
* Aún no existe evidencia suficiente para confirmarla o descartarla.

Qué falta demostrar:

* Obtener mediciones y datos adicionales.

Próximo paso relacionado:

Consultar NEXT_ACTIONS.md.

---

# 🎯 Línea de Investigación 3

## Presión de aceite del motor

Estado:

🟡 Activa

Prioridad:

Alta

Observaciones relevantes:

* Existen indicios compatibles con esta posibilidad.
* Actualmente no se dispone de mediciones suficientes para confirmarla.

Qué falta demostrar:

* Obtener datos objetivos sobre el sistema de lubricación.

Próximo paso relacionado:

Consultar NEXT_ACTIONS.md.

---

# 📌 Reglas del proyecto

Una hipótesis puede cambiar de estado únicamente cuando exista evidencia objetiva que justifique el cambio.

Las hipótesis pueden aumentar o disminuir su prioridad a medida que avance el diagnóstico.

Las hipótesis descartadas permanecen documentadas para mantener el historial técnico del proyecto.

Toda modificación importante debe reflejarse posteriormente en STATUS.md y NEXT_ACTIONS.md mediante una revisión del proyecto.