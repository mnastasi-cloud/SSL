# 00-CHelloWorld

## Compilador seleccionado

Se utilizó GCC (GNU Compiler Collection).

## Versión del compilador

```bash
gcc --version
```

Salida:

```text
gcc.exe (Rev3, Built by MSYS2 project) 14.2.0
```

## Versión de C soportada

El compilador soporta el estándar C23 utilizando:

```bash
-std=c23
```

También puede utilizarse:

```bash
-std=c2x
```

## Programa fuente

Archivo:

```text
hello.c
```

## Compilación

```bash
gcc -std=c23 hello.c -o hello
```

## Ejecución

```bash
./hello
```

Salida:

```text
Hello, World!
```

## Redirección de salida

```bash
./hello > output.txt
```

Verificación:

```bash
cat output.txt
```

Contenido:

```text
Hello, World!
```

## Compilación con make

```bash
make
```

## Ejecución con make

```bash
make run
```
