# Qudox Visual Assets

Repositorio público, **solo de imágenes** — logo y assets visuales de presentaciones de Qudox. No contiene texto de marca, estrategia, tono de voz ni ningún contenido sensible: por eso es público, a diferencia del repositorio principal (`Qudox-Oficial/Qudox-Design-System`, privado).

**Para qué existe:** estos archivos son texturas fotográficas y assets compuestos que no se pueden convertir a texto sin perder calidad. El sistema de marca (`QUDOX-DESIGN-SYSTEM.md`, en el repo privado) los descarga automáticamente desde acá cuando genera una presentación, en vez de necesitar que alguien los adjunte a mano.

**Fuente de verdad de las reglas de uso:** este repo es solo el almacenamiento de los archivos. Qué asset usar, cuándo, y con qué medidas, está documentado en el repositorio privado — sección 6.12 (Texto siempre editable) y 6.12.2 (URLs) del sistema de marca. Si algo de acá no coincide con lo que dice esa sección, confiar en la sección del sistema de marca, no en lo que parezca lógico mirando la carpeta.

## `surfaces-assets/presentaciones/` — estado de cada archivo

**Confirmados, en uso activo** (con URL oficial en el sistema de marca):
- `fondo-portada.jpg` — portada y cierre
- `footer-listo-para-logo.png` — footer con logo editable
- `banda-footer-fondo-claro.png` — footer todo-en-uno
- `patron-lineas-decorativas-oscura.png` — footer de `section-divider`
- `banda-lateral-patron-verde-1.png` / `-2.png` — layout alternativo (banda lateral)

**Piezas fuente, no usar directo** (ingredientes para reconstruir `footer-listo-para-logo.png` si cambia):
- `banda-footer-claro-nueva.png`
- `parche-textura-logo.png`

**Exploratorios, sin confirmar** (variante oscura, pausada):
- `banda-footer-fondo-oscuro.png`
- `franja-vertical-lineas-oscura.png`

## `logo/`

Los 6 vectores reales del logo. **Ya no hace falta usarlos desde acá** para generar piezas con IA — el vector está embebido directo como código dentro de `QUDOX-DESIGN-SYSTEM.md` (sección 4). Esta carpeta queda para uso humano directo (diseño, imprenta) o como respaldo. Ver `logo/README.md` para el detalle de cada archivo.

## Antes de agregar o sacar algo de acá

Si subís un asset nuevo o sacás uno viejo, actualizá también la sección 6.12.2 del sistema de marca con la URL correspondiente — este repo y ese archivo tienen que quedar sincronizados, uno no sirve de nada sin el otro.
