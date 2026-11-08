# Ejemplos de Forja

Más de 250 ejemplos del lenguaje **Forja** (.fa), organizados por tema y dificultad.

## Organización

Los ejemplos están agrupados por tema:

- `fundamentos/` — primeros pasos y sintaxis básica.
- `poo/` — clases, objetos y métodos.
- `algoritmos/` — recursión, ordenación, búsqueda y estructuras.
- `concurrencia/` — hilos, canales y select.
- `resultados/` — `Resultado`, `Opcion` y propagación.
- `rasgos_genericos/` — rasgos, genéricos e interpolación.
- `avanzado/` — match, ciclos de vida, meta y rendimiento.
- `patrones/` — patrones de diseño.
- `juegos/` — ejemplos interactivos.
- `ownership/` — préstamos y mutabilidad.
- `ffi/` — interoperabilidad.
- `redes/` — sockets, HTTP y servidores.
- `sistema/` — archivos, entorno y utilidades.
- `gui/` — interfaces gráficas.
- `exactitud/` — decimal exacto.
- `contratos/` — `requiere`/`asegura`/`siempre`.
- `async_await/` — ejemplos de `async`/`await`.
- `otros/` — casos sueltos.

El índice completo, generado desde el árbol, está en [`INDICE.md`](INDICE.md).

## Ejecutar ejemplos

```bash
# Con ForjaFast VM (por defecto)
forja run ejemplos/fundamentos/01_hola.fa

# Con VM original
forja run ejemplos/fundamentos/01_hola.fa --vm vm

# Con JIT nativo
forja run ejemplos/fundamentos/01_hola.fa --vm jit

# Compilar a nativo y ejecutar
forja run ejemplos/fundamentos/01_hola.fa --asm

# Tests
forja test ejemplos/124_atributo_test.fa
```

## Repositorios relacionados

- [forja-lang/forja](https://github.com/forja-lang/forja) — Núcleo del lenguaje
- [forja-lang/docs](https://github.com/forja-lang/docs) — Documentación
- [forja-lang/vscode](https://github.com/forja-lang/vscode) — Extensión de VS Code
