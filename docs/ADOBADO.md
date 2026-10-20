# SoundAdobado - procedencia y cambios

## Origen

- Upstream: https://github.com/storytold/soundcraft
- Commit base: 25d52c646aea780c8076ff966076f994ad256221
- Licencia: MIT OR Apache-2.0
- Copyright original: ArtCraft Team and the SoundCraft contributors.

## Cambios de esta distribucion

- Nombre de producto visible: SoundAdobado (el crate y el ejecutable internos se conservan para no romper el build).
- Enlaces de ayuda, GitHub e issues apuntando a https://github.com/smouj/SoundAdobado y a Adobado Kit.
- README propio, CHANGELOG y guia de contribucion.
- Se retiran los logos y assets de marca de ArtCraft incluidos en docs/brand.
- No se han cambiado el motor, los formatos ni las funciones de edicion.

## Estado de validación — 20/10/2026

- **Build de Windows:** correcto en GitHub Actions ([workflow](https://github.com/smouj/SoundAdobado/actions/workflows/windows-build.yml)).
- **Prueba manual:** app instalada y abierta en Windows.
- **Uso con archivos reales:** abrir, modificar y exportar sigue pendiente.
- **Distribución:** hay una release alpha anterior al icono actual; su ZIP conserva el icono previo y debe actualizarse después de probar el nuevo binario.
- **Origen:** 25d52c646aea780c8076ff966076f994ad256221.
## Marcas

ArtCraft, SoundCraft y sus logos son marcas del ArtCraft Team y no estan cubiertos por la licencia de codigo. Adobe y sus productos son marcas de Adobe Inc. Este proyecto no esta afiliado a Adobe ni a ArtCraft.

## Aviso

Esta es una distribucion modificada. Las modificaciones son de @smouj (2026). El codigo original conserva sus avisos de copyright y licencia.
