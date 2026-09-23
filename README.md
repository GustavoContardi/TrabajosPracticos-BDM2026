# Bases de Datos Masivas (11088)

Trabajos prácticos de la cursada del 2do cuatrimestre de 2026, Licenciatura en Sistemas de
Información, Universidad Nacional de Luján.

Alumno: Gustavo An Contardi.
Legajo: 182818

## Contenido

| TP | Tema | Entrega |
| --- | --- | :---: |
| [TP01](TP01/) | Preprocesamiento y transformación de datos | 14/09/2026 |
| [TP02](TP02/) | Procesos ETL con pandas y Apache Hop | 25/09/2026 |

Los demás se van agregando a medida que avanza la cursada.

## Cómo correr los notebooks

Los TP están resueltos con Python y pandas. El TP02 además incluye la misma solución hecha con Apache Hop, en `TP02/hop/`, que se ejecuta con el entorno dockerizado de la materia. Cada TP trae su carpeta `data/` con los datasets que usa, y las rutas dentro de los notebooks son relativas, así que se ejecutan sin configurar nada.

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter lab
