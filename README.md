<div align="center">

# EvidGuard

**Democratizando el análisis forense digital.**

[![Focus](https://img.shields.io/badge/enfoque-forense%20digital-2b2d42)](#)
[![Platform](https://img.shields.io/badge/plataforma-Raspberry%20Pi-c51a4a?logo=raspberrypi&logoColor=white)](#)
[![Status](https://img.shields.io/badge/estado-en%20desarrollo-yellow)](#)

</div>

---

## Quiénes somos

EvidGuard es un proyecto que nace para acercar el análisis forense digital a quien hoy no tiene acceso a él. Las soluciones forenses comerciales suelen ser caras y pensadas para grandes laboratorios, dejando fuera a peritos independientes, pequeñas firmas y profesionales que necesitan trabajar con evidencia digital de forma rigurosa pero sin ese presupuesto.

Nuestra respuesta es una plataforma forense de bajo coste construida sobre una Raspberry Pi, capaz de adquirir, clonar y verificar evidencia digital —incluida la que reside en la nube— con las mismas garantías de integridad y cadena de custodia que exige el trabajo pericial.

---

## Qué problema resolvemos

Cada vez más evidencia digital vive en la nube: correo, almacenamiento, backups, dispositivos gestionados de forma remota. Adquirir esa evidencia de forma forense —íntegra, trazable y verificable— suele requerir herramientas caras o procesos manuales propensos a error. EvidGuard automatiza ese proceso: clona los datos de la nube al entorno local, protege el destino frente a escrituras accidentales, monitoriza cada paso y verifica la integridad del resultado, dejando un rastro auditable de principio a fin.

---

## Cómo trabajamos

- **Bajo coste.** Todo el sistema corre sobre una Raspberry Pi, sin licencias ni hardware especializado.
- **Integridad ante todo.** Cada dispositivo de destino se bloquea en solo lectura y cada transferencia se verifica mediante hashing.
- **Trazabilidad.** Toda acción queda registrada con marca de tiempo y metadatos, pensada para sostener una cadena de custodia.
- **Código abierto.** Las herramientas se publican de forma modular para que la comunidad pericial pueda usarlas, auditarlas y mejorarlas.
- **Alineados con la norma.** El diseño toma como referencia marcos como ISO/IEC 27037, la LECrim, el RGPD, el ENS y el Convenio de Budapest.

---

## Nuestras herramientas

| Herramienta | Qué hace |
|---|---|
| **Rclone Manager** | Gestiona la transferencia de datos entre la nube y el almacenamiento local. |
| **EVG Write-Blocker** | Bloquea en solo lectura los dispositivos de destino para proteger la evidencia. |
| **EvidGuard LogWatch** | Monitoriza las transferencias en curso y notifica errores en tiempo real. |
| **SpyGuard Control Panel** | Centraliza el arranque y control de los servicios del sistema. |
| **GTKHash** | Verifica la integridad de la evidencia mediante hashing criptográfico. |

Los detalles técnicos, instalación y uso de cada herramienta están en sus repositorios correspondientes.

---

## Participantes

Adelin Florian Bordeianu
[GitHub](https://github.com/Borde00) · [LinkedIn](https://www.linkedin.com/in/adelin-florian-bordeianu)

Hugo Cabana de la Cruz
[GitHub](https://github.com/Chugo05) · [LinkedIn](https://www.linkedin.com/in/hugo-cabana-3a1324352)

