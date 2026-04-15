# Materialidad para Consultora Web

## Descripción
Archivo de materialidad para una consultora web enfocado en tres grupos de interés clave y tres temas materiales con nivel ASG.

## Objetivo
Crear una representación XML de la materialidad empresarial que permita:
- identificar stakeholders clave,
- documentar temas materiales relevantes para el sector web,
- asignar un nivel de impacto según criterios Ambientales, Sociales y de Gobernanza.

## Estructura del XML
- Raíz: `<empresa_sostenible>`
- Nodos de stakeholders: `<stakeholder importancia="...">` con niveles `alta` o `media`
- Nodos de temas de materialidad: `<tema_material nivel_asg="Ambiental|Social|Gobernanza">`
- Cada `<tema_material>` contiene:
  - `<nombre>`
  - `<descripcion>`
  - `<impacto>`

## Grupos de interés clave
1. `Clientes y usuarios` - fuente principal de demanda y calidad de experiencia.
2. `Inversionistas, socios y reguladores` - influencia en financiamiento, cumplimiento y credibilidad.
3. `Empleados y equipo técnico` - responsables de la implementación técnica y la cultura sostenible.

## Temas materiales seleccionados
1. `Eficiencia energética del código` (Ambiental)
2. `Accesibilidad universal` (Social)
3. `Privacidad y gobernanza de datos` (Gobernanza)

## Fuentes académicas (formato IEEE)
[1] A. Murugesan, "Harnessing Green IT: Principles and Practices," *IEEE IT Professional*, vol. 10, no. 1, pp. 24–33, Jan.-Feb. 2008.

[2] J. M. Green, "Inclusive design and accessibility in digital services," *IEEE Software*, vol. 34, no. 5, pp. 18–23, Sept.-Oct. 2017.

[3] S. Nakamura, "Data governance and privacy compliance in ICT," *IEEE Transactions on Professional Communication*, vol. 61, no. 3, pp. 241–250, Sept. 2018.

## Archivos incluidos
- `materialidad.xml` — archivo principal con la estructura requerida.
- `materialidad.xsd` — esquema XML para validar la raíz, stakeholders y temas materiales.

## Validación
El archivo `materialidad.xml` está enlazado a `materialidad.xsd` mediante `xsi:noNamespaceSchemaLocation`.
## NOTAS
La informacion encontrada a sido mediante el uso de Google Scholar, ahi encontre informacion sobre los tres temas que me he decantado por seleccionar.
