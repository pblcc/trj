<p align = "center">
  <a href="docs/README-es.md">Español</a>
</p>

## Tabla de contenido
- [Tabla de contenido](#tabla de contenido)
- [Idea](#idea)
- [Instalación](#instalación)
  - [Requisitos previos](#requisitos previos)
  - [Compilación del cliente](#compilación-del-cliente)
  - [Ejecutando el servidor](#ejecutando-el-servidor)
- [Aviso legal](#aviso-legal)
  - [Licencia](#licencia)
  - [Garantía](#garantía)
  
---

## Idea
Trc es un caballo de Troya creado con la intención de tener ** acceso completo al sistema informático de otra persona **, acceder a su cmd / terminal y poder ejecutar cualquier comando**.

Para lograr esto, se utiliza un servidor programado en Python que se conecta a un socket programado en C desde el lado del cliente.

---

## Instalación

Para usar Trj, tendrá que instalar dos cosas, el cliente y el servidor. El cliente ha sido programado usando C, ya que se puede compilar y el objetivo del ataque no notará que hay software espía ejecutándose como un hilo. El servidor está programado en Python.
### Requisitos previos

| Nombre | Uso | Enlaces |
| ------ | ----- | ------- |
| Git | Clonar del repositorio | [Instalar](https://git-scm.com/downloads) |
| Python (v3.6 +) | Ejecutar el servidor | [Página](https://python.org) |
| Compilador de C (gcc) | Compilar el cliente | [GNU](https://gcc.gnu.org/) |

El primer paso para instalar trj es clonar el repositorio en su máquina local:
```
git clone https://github.com/pblcc/trj
```

### Compilando el cliente
Para compilar el cliente usamos un compilador de C como [gcc](https://gcc.gnu.org) y [CMake](https://cmake.org). Ejecute los siguientes comandos:
```
cd client/
```
```
make
```
Ahora puede iniciar el cliente como:
```
./client
```

### Ejecutando el servidor
Para ejecutar el servidor, debe usar [Python] (https://python.org). Ejecute los siguientes comandos:
```
python server/server.py
```
###### NOTA: Si tienes varias instalaciones de Python, usa Python3

<p align = "centro">
  <img src = "img/banner.png">
</p>

---

## Aviso legal
Trc se puede utilizar con fines maliciosos, por lo que tenemos que especificar un par de cosas.
### Licencia
Este proyecto está bajo la [Licencia] BSL (LICENCIA)
### Garantía
Use tcr ** bajo su propio riesgo **, no soy responsable de ningún uso poco ético que haga con este repositorio. Este repositorio ha sido programado para uso educativo.**