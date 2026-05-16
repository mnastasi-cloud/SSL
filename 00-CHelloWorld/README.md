# 00-CHelloWorld

## Compilador seleccionado

Se utilizó GCC (GNU Compiler Collection).

## Versión del compilador

Para verificar la versión del compilador se ejecutó:

```bash
/c/msys64/ucrt64/bin/gcc.exe --version
```

Salida obtenida:

```text
gcc.exe (Rev4, Built by MSYS2 project) 16.1.0
```

Por lo tanto, la versión del compilador utilizada es GCC 16.1.0.

## Versión del lenguaje C soportada

El programa fue compilado utilizando:

```bash
/c/msys64/ucrt64/bin/gcc.exe -std=c2x hello.c -o hello
```

La opción `-std=c2x` corresponde al estándar C23.