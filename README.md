# Práctica 3 — Protección Jurídica del Software y Propiedad Intelectual (Ley 65-00 y Ley 20-00)

**Instituto Tecnológico de las Américas (ITLA) — Departamento de Ciberseguridad**
**Asignatura:** TSI-315 Aspectos Legales de la Ciberseguridad
**Grupo:** 1 (jueves, 6:00 PM – 9:00 PM)
**Profesor:** Prof. Joel Morrobel Ovalle, CISM
**Estudiante:** Gregorys Morel Duluc — Matrícula 2025-0035 (trabajo individual)
**Asignación:** Semana 5 (08/10/2026) · **Entrega y debate:** Semana 7 (22/10/2026)

---

## Entregables

| Archivo | Descripción |
|---|---|
| [`docs/Practica_3_Propiedad_Intelectual_Grupo1.docx`](docs/Practica_3_Propiedad_Intelectual_Grupo1.docx) | Práctica completa en formato Word (editable) |
| [`docs/Practica_3_Propiedad_Intelectual_Grupo1.pdf`](docs/Practica_3_Propiedad_Intelectual_Grupo1.pdf) | Práctica completa en formato PDF |
| [`referencias/Ley_65-00_Derecho_de_Autor.pdf`](referencias/Ley_65-00_Derecho_de_Autor.pdf) | Ley No. 65-00 sobre Derecho de Autor |
| [`referencias/Ley_20-00_Propiedad_Industrial.pdf`](referencias/Ley_20-00_Propiedad_Industrial.pdf) | Ley No. 20-00 sobre Propiedad Industrial |

## Propósito de la práctica

Identificar, clasificar y defender jurídicamente los activos de software, algoritmos y desarrollos tecnológicos de una empresa en la República Dominicana, a partir del caso de la Fintech ficticia **FinanzaTech Dominicana, S.A.** Se aplican la Ley No. 65-00 sobre Derecho de Autor (el software como obra literaria, código fuente y objeto, obras laborales y por encargo) y la Ley No. 20-00 sobre Propiedad Industrial (patentes, signos distintivos, secreto empresarial y registro ante la ONAPI), junto con la Ley No. 53-07 sobre Crímenes y Delitos de Alta Tecnología.

## Estructura del repositorio

​```
TSI315-Practica3-PropiedadIntelectual-2025-0035/
├── README.md
├── docs/
│   ├── Practica_3_Propiedad_Intelectual_Grupo1.docx
│   └── Practica_3_Propiedad_Intelectual_Grupo1.pdf
└── referencias/
    ├── Ley_65-00_Derecho_de_Autor.pdf
    └── Ley_20-00_Propiedad_Industrial.pdf
​```

## Resumen de la resolución

### Parte I — Escenario A: parche malicioso no intencionado (3.0 puntos)

- **Titularidad y responsabilidad:** los programadores son los autores del parche (Art. 5, Ley 65-00), pero la empresa desarrolladora es el *productor* del programa, es decir, quien "toma la iniciativa y la responsabilidad de la realización de la obra" (Art. 73). Por eso es la empresa la que responde frente a sus clientes.
- **Responsabilidad penal:** la Ley 53-07 exige intención (Arts. 4 y 10). Sin dolo no hay delito de la empresa ni de los programadores. Si un programador insertó el código a sabiendas, o los órganos de la empresa lo permitieron, aplican los Arts. 8, 10, 11 y 60. Los terceros que exfiltraron los datos responden por los Arts. 6, 14 y 17.
- **Responsabilidad civil:** es contractual frente a FinanzaTech (Arts. 1134, 1135 y 1147 del Código Civil) y extracontractual frente a los usuarios (Arts. 1382 a 1384). La Ley 53-07 la refuerza por "falta de vigilancia o de control" (Art. 60, Párrafo) y permite condenar a indemnizar a la víctima (Art. 62).
- **EULA:** es una licencia de uso (Art. 75, Ley 65-00). Puede limitar la cuantía de la responsabilidad entre profesionales (Arts. 1134 y 1150 del Código Civil). No cubre el dolo ni la falta grave, no excluye la responsabilidad penal ni las leyes de orden público (Art. 6), no se le puede oponer a los usuarios (Art. 1165) y, frente a consumidores, sus cláusulas de exoneración son nulas (Art. 83, Ley 358-05).

### Parte I — Escenario B: disputa de código fuente y obra laboral (3.0 puntos)

- **Precisión normativa:** el Art. 10 de la Ley 65-00 regula la obra anónima y la seudónima. La obra creada bajo relación laboral se rige por el Art. 12 y, en el caso del software, por la norma especial del Art. 73.
- **Titularidad:** los derechos patrimoniales pertenecen a FinanzaTech como productor. Salvo pacto en contrario, se presume que el autor cedió "en forma ilimitada y por toda su duración" el derecho patrimonial exclusivo (Art. 73, Párrafo). La protección dura 70 años (Art. 25, modificado por la Ley 424-06).
- **Derechos morales y patrimoniales:** los morales (paternidad e integridad, Art. 17) son inalienables, pero no permiten explotar la obra. Los patrimoniales (reproducción, modificación y distribución, Art. 19) son de FinanzaTech.
- **Conductas ilícitas:** comercializar el software es el delito del Art. 169 de la Ley 65-00. Cuando se comete por medios informáticos, el Art. 25 de la Ley 53-07 aplica esas mismas penas. Borrar las copias del servidor es daño de datos cometido por un exempleado (Art. 10 y su Párrafo, Ley 53-07). Además, se trata de un secreto empresarial (Arts. 178 a 180, Ley 20-00).
- **Acciones ante la ONDA:** registro de la obra y del contrato (Arts. 149, 150 y 154), impugnación del registro (Art. 155), medidas cautelares, inspección y sanciones administrativas (Arts. 187 y 188). El titular puede optar entre la vía administrativa, la civil y la penal (Art. 168).

### Parte II — Matriz de gestión de riesgos y clasificación de activos (4 puntos)

| Componente / Riesgo | Tipo de protección | Base legal | Organismo |
|---|---|---|---|
| 1. Fuga de código fuente | Derecho de Autor + Secreto Comercial | Ley 65-00: Arts. 2 (num. 11), 12, 19, 20, 73, 169 · Ley 20-00: Arts. 178-180 · Ley 53-07: Arts. 6, 10, 25 | ONDA · Ministerio Público |
| 2. Infracción de copyright (licencias EULA / OSS) | Derecho de Autor | Ley 65-00: Arts. 2 (num. 11), 19, 20, 75, 80, 81, 169 · Ley 53-07: Art. 25 | ONDA |
| 3. Interfaz gráfica (GUI), logotipo y marca | Mixta: Derecho de Autor + Propiedad Industrial | Ley 65-00: Arts. 2 (num. 7 y 11), 7 · Ley 20-00: Arts. 70, 71, 72, 81, 86 | ONDA / ONAPI |
| 4. Firmware / algoritmo industrial biométrico | Propiedad Industrial (patente) + Derecho de Autor sobre el código | Ley 20-00: Arts. 1, 2, 3-6, 8, 27, 29 · Ley 65-00: Art. 2 (num. 11) | ONAPI / ONDA |
| 5. Fórmula de evaluación crediticia no publicada | Secreto Comercial | Ley 20-00: Arts. 176, 178-180, 183, 184 · Ley 65-00: Art. 7 | Sin registro; tribunal competente |

## Marco legal utilizado

- Ley No. 65-00 sobre Derecho de Autor (y sus modificaciones por la Ley No. 424-06)
- Reglamento de Aplicación No. 362-01 de la Ley 65-00 (ONDA, Art. 104)
- Ley No. 20-00 sobre Propiedad Industrial (modificada por las Leyes No. 424-06 y 493-06)
- Ley No. 53-07 sobre Crímenes y Delitos de Alta Tecnología
- Código Civil de la República Dominicana (Arts. 6, 1134, 1135, 1147, 1150, 1165, 1382, 1383 y 1384)
- Ley No. 358-05 General de Protección de los Derechos del Consumidor o Usuario (Art. 83)
- Ley No. 172-13 sobre Protección de Datos Personales

---

*Trabajo académico individual para la asignatura TSI-315 del ITLA. El caso de FinanzaTech Dominicana, S.A. es ficticio.*
