# Comment Markers

Use inline `TODO` and `HINT` markers only when the file format safely supports comments and the file is intended for manual editing.

## Primary Languages

- C
  - `// TODO: ...`
  - `/* HINT: ... */`
- C++
  - `// TODO: ...`
  - `/* HINT: ... */`
- Rust
  - `// TODO: ...`
  - `// HINT: ...`
- Python
  - `# TODO: ...`
  - `# HINT: ...`
- JavaScript / TypeScript
  - `// TODO: ...`
  - `// HINT: ...`
- CSS
  - `/* TODO: ... */`
  - `/* HINT: ... */`

## Secondary Languages

- Shell
  - `# TODO: ...`
  - `# HINT: ...`
- CMake
  - `# TODO: ...`
  - `# HINT: ...`
- Fortran
  - `! TODO: ...`
  - `! HINT: ...`

## Marker Rules

- Every `HINT` should contain approach, key concepts, and common pitfalls.
- `HINT` must not contain a full copy-paste implementation.
- Keep markers close to the code region the learner must change.
- Prefer a small number of precise markers over a large number of shallow hints.

## Fallback Rules

- For formats like `JSON`, strict `YAML`, `TOML`, or generated files, do not inject fake comments.
- For vendor, minified, or machine-generated files, place guidance in the response and point to the real source file instead.
- If comment markers would break formatting, parsing, or tests, provide exact file and function anchors in the response rather than forcing inline markers.
