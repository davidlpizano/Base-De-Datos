<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:F80000,100:B71C1C&height=220&section=header&text=Database%20Lab&fontSize=55&fontColor=ffffff&animation=twinkling&fontAlignY=38&desc=David%20Lopez%20%7C%20ASIR&descSize=20&descAlign=50&descAlignY=60&descColor=ffcdd2" alt="Bases de Datos Banner" width="100%">

**Modelado Entidad-Relacion, desarrollo en SQL y administracion con Oracle.**

[![Oracle SQL](https://img.shields.io/badge/Oracle_SQL-F80000?style=flat-square&logo=oracle&logoColor=white)](#)
[![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)](#)
[![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white)](#)
[![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)](#)

</div>

<br/>

## 🎯 Sobre este repositorio

Ejercicios, proyectos y apuntes sobre diseño, implementacion y explotacion de **Bases de Datos Relacionales** como parte de mi formacion en **ASIR**.

Desde la conceptualizacion teorica (modelo E/R al logico/relacional) hasta sentencias DCL, DDL y DML con **Oracle SQL Developer**. Varios servicios de mi homelab (Nextcloud, Firefly III, Grafana) utilizan bases de datos MariaDB/SQLite en produccion.

<br/>

## 📂 Contenido

<table>
<tr>
<td width="50%" valign="top">

### 📋 Modelado y Diseño
- Esquemas **Entidad-Relacion (E/R)**
- Normalizacion (1FN, 2FN, 3FN)
- Diseño logico y fisico

### 🏗️ Definicion de Datos (DDL)
- `CREATE`, `ALTER`, `DROP`
- Primary Keys, Foreign Keys, Checks
- Secuencias, indices y vistas

</td>
<td width="50%" valign="top">

### 🔍 Consultas (DML)
- `INSERT`, `UPDATE`, `DELETE`
- **JOINs:** Inner, Left/Right Outer, Full, Cross
- Subconsultas en WHERE, FROM, SELECT
- `GROUP BY`, `HAVING` y funciones de agregacion

### 🔐 Administracion
- Usuarios y perfiles de BD
- Roles y privilegios (`GRANT`, `REVOKE`)

</td>
</tr>
</table>

<br/>

## 🏠 Bases de datos en produccion (Homelab)

<div align="center">

Servicios de mi homelab que utilizan bases de datos reales:

| Servicio | Motor | Uso |
| :--- | :---: | :--- |
| **Nextcloud** | ![MariaDB](https://img.shields.io/badge/-MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white) | Usuarios, archivos, calendario, contactos |
| **Firefly III** | ![MariaDB](https://img.shields.io/badge/-MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white) | Transacciones, categorias, presupuestos |
| **Grafana** | ![SQLite](https://img.shields.io/badge/-SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white) | Dashboards, datasources, alertas |
| **Vaultwarden** | ![SQLite](https://img.shields.io/badge/-SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white) | Contraseñas cifradas y configuracion |
| **Speedtest Tracker** | ![SQLite](https://img.shields.io/badge/-SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white) | Historial de mediciones de velocidad |

</div>

<br/>

## 🚀 Como ejecutar estos scripts

> Los ficheros `.sql` fueron creados para **Oracle**. En otros SGBD (MySQL, PostgreSQL, SQL Server) pueden requerir ajustes en sintaxis o tipos de datos (`VARCHAR2` → `VARCHAR`). Recomiendo Oracle SQL Developer o LiveSQL para pruebas rapidas.

<br/>

<div align="center">

*"Los datos son el petroleo del siglo XXI; la consulta adecuada es la refineria."*

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:F80000,100:B71C1C&height=100&section=footer" width="100%"/>

**[⬅️ Volver a mi perfil principal](https://github.com/davidlpizano/davidlpizano)**

</div>
