# Permisos de archivos y directorios

| Archivo | Tipo | Permisos | Propietario | Grupo | Otros | Octal |
|---------|------|----------|-------------|-------|-------|-------|
| README  | Archivo | -rw-rw-r-- | rw- (6) | rw- (6) | r-- (4) | 664 |
| docs    | Directorio | drwxrwxr-x | rwx (7) | rwx (7) | r-x (5) | 775 |
| logs    | Directorio | drwxrwxr-x | rwx (7) | rwx (7) | r-x (5) | 775 |
| src     | Directorio | drwxrwxr-x | rwx (7) | rwx (7) | r-x (5) | 775 |

## Notas

- El primer carácter (`-` o `d`) indica el tipo: `-` para archivo regular, `d` para directorio.
- Cada terna de caracteres (`rwx`) representa permisos de lectura (r), escritura (w) y ejecución (x).
- El valor octal se obtiene sumando: r=4, w=2, x=1, para cada uno de los tres grupos (propietario, grupo, otros).
