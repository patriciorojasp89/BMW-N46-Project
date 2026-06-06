# 📁 DATA DEL PROYECTO

> Este documento almacena los datos objetivos conocidos del vehículo y del diagnóstico.
>
> Su objetivo es responder:
>
> * ¿Qué hechos verificables conocemos?
> * ¿Qué mediciones existen?
> * ¿Qué códigos de falla se han registrado?
> * ¿Qué componentes han sido reemplazados?
>
> Este archivo no interpreta hipótesis ni define próximos pasos.
>
> Para interpretación consultar:
>
> * 📊 STATUS.md
> * 🧩 HYPOTHESES.md
> * 🎯 NEXT_ACTIONS.md
> * 📝 LOGBOOK.md

---

# 🚗 Datos del vehículo

| Dato                   | Valor            |
| :--------------------- | :--------------- |
| Modelo                 | BMW 320i E90 LCI |
| Fecha de fabricación   | 06/2010          |
| Motor                  | N46              |
| Transmisión            | Automática       |
| Kilometraje aproximado | 195.000 km       |

---

# 🚨 Síntoma principal registrado

El motor enciende y se apaga aproximadamente después de un segundo.

---

# 🧰 Herramientas disponibles

## Hardware

* ICOM
* Osciloscopio
* Multímetro

## Software

* ISTA
* INPA
* Tool32
* NCS Expert
* BMW Standard Tools

---

# 🔩 Componentes reemplazados

| Componente              | Estado                 |
| :---------------------- | :--------------------- |
| Motor de partida        | Reemplazado            |
| Motor Valvetronic       | Reemplazado            |
| Caja de fusibles / JBBF | Reemplazada            |
| Driver LIN del FRM      | Reparado / reemplazado |
| Aceite del motor        | Reemplazado            |
| Módulo confort          | Reemplazado            |
| Llave del auto          | Reemplazado            |

---

# ⚠ Códigos de falla registrados

| Módulo |         Código        | Descripción breve                                          | Estado     |
| :----- | :-------------------: | :--------------------------------------------------------- | :--------- |
| JBBF   |          A6CF         | Falla relacionada con gestión eléctrica de la Junction Box | Registrado |
| EGS    |          578E         | Falla registrada por el módulo de transmisión automática   | Registrado |
| DSC    |          5DE0         | Falla asociada al sistema de estabilidad                   | Registrado |
| FRM    |          A8B6         | Falla relacionada con gestión o comunicación del FRM       | Registrado |
| FRM    |          A8AE         | Falla registrada en funciones controladas por el FRM       | Registrado |
| FRM    |          A8AF         | Falla relacionada con circuitos gestionados por el FRM     | Registrado |
| FRM    |          9CB6         | Falla de gestión eléctrica o comunicación del FRM          | Registrado |
| MOST   | Sin código específico | Módulo CD Changer ubicado en maletero no responde          | Registrado |

---

# 📏 Mediciones registradas

| Sistema     | Medición                   | Resultado                 | Estado     |
| :---------- | :------------------------- | :------------------------ | :--------- |
| Combustible | Presión de combustible     | 5 bar                     | Registrado |
| Arranque    | Duración de funcionamiento | Aproximadamente 1 segundo | Registrado |

---

# 🔌 Módulos / sistemas observados

| Sistema o módulo  | Observación                  | Estado     |
| :---------------- | :--------------------------- | :--------- |
| CD Changer / MOST | No responde                  | Registrado |
| FRM               | Driver LIN intervenido       | Registrado |
| JBBF              | Caja de fusibles reemplazada | Registrado |

---

# 📌 Reglas del archivo

Este archivo debe contener solamente datos objetivos.

No se deben incluir hipótesis, opiniones o recomendaciones.

Si un dato cambia, se debe registrar el nuevo dato manteniendo trazabilidad en LOGBOOK.md.

Si una medición no está confirmada, debe marcarse como pendiente o no verificada.

