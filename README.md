# Bases de Datos Masivas (11088)

Trabajos prácticos de la cursada del 2do cuatrimestre de 2026, Licenciatura en Sistemas de
Información, Universidad Nacional de Luján.

Alumno: Gustavo An Contardi.
Legajo: 182818s

## Contenido

| TP | Tema | Entrega |
| --- | --- | :---: |
| [TP01](TP01/) | Preprocesamiento y transformación de datos | 14/09/2026 |

Los demás se van agregando a medida que avanza la cursada.

## Cómo correr los notebooks

Todo está resuelto con Python y pandas. Cada TP trae su carpeta `data/` con los datasets que usa, y las rutas dentro de los notebooks son relativas, así que se ejecutan sin configurar nada.

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter lab
