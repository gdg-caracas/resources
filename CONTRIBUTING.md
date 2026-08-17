# Cómo contribuir

Gracias por tu interés en compartir recursos con **GDG Caracas**.

## Recursos aceptados

- Presentaciones de charlas, paneles y talleres.
- Codelabs y guías prácticas.
- Demostraciones técnicas y ejemplos utilizados en eventos.
- Materiales complementarios relacionados con actividades de GDG Caracas.

## Antes de comenzar

Verifica que:

- Eres autor del material o tienes autorización explícita para publicarlo.
- El contenido respeta la autoría de terceros y cita sus fuentes.
- No incluye información personal, confidencial o sensible.
- La licencia y las condiciones de reutilización están claramente indicadas.
- El uso de herramientas de IA generativa está declarado cuando corresponda.

## Estructura de cada contribución

Crea una carpeta dentro del tipo de recurso y año correspondiente:

```text
presentations/2026/aaaa-mm-dd-titulo-del-recurso/
├── README.md
├── metadata.yml
└── archivo-del-recurso.pdf
```

Para codelabs o demostraciones utiliza, respectivamente, `codelabs/` o `demos/`.

La carpeta debe contener:

1. **README.md:** resumen, contexto del evento e instrucciones de uso.
2. **metadata.yml:** copia completada de `templates/resource-metadata.yml`.
3. **Recurso:** archivo publicado o enlace oficial cuando el material se aloje externamente.

## Flujo de contribución

1. Haz un fork del repositorio.
2. Crea una rama descriptiva.
3. Añade el recurso en la carpeta correspondiente.
4. Verifica metadatos, enlaces, autoría y permisos.
5. Abre un Pull Request explicando qué agregas y en qué evento fue utilizado.
6. Atiende las observaciones de la revisión.

## Formatos

- Para presentaciones se recomienda PDF como formato de consulta.
- El archivo editable es opcional y solo debe incluirse con autorización del autor.
- Los archivos grandes deben alojarse en una plataforma apropiada y registrarse mediante un enlace estable.
- Los ejemplos de código deben incluir instrucciones suficientes para ejecutarlos de forma segura.

## Revisión

El equipo mantenedor podrá solicitar ajustes de formato, atribución, licencia, accesibilidad, seguridad o documentación antes de aprobar el recurso.

La aceptación de una contribución no transfiere la autoría del material a GDG Caracas.
