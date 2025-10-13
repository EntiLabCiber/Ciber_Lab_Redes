# 🛰️ Repositorio de Prácticas - Asignatura de Redes

Este repositorio contiene el material, código y documentación correspondiente a las **prácticas de la asignatura de Redes y el material del laboratorio**.  
El objetivo es aplicar los conceptos teóricos vistos en clase mediante la configuración, simulación y análisis de redes.

## 📁 Contenido del Repositorio

- `docs/` – Informes y documentación adicional como guías y manuales de uso.  

## ⚙️ Requisitos

- **Sistema Operativo:** Linux o Windows con WSL  
- **Herramientas recomendadas:**  
  - Cisco Packet Tracer / GNS3   

## 🚀 Uso

**1r PASO:**- Conectar cable ethernet del pc a la entrada MGTM del FortiGate 121G.
**2o PASO:**- Acceder a la interfaz gráfica desde la ip 192.168.1.99 e iniciar sesión con las credenciales admin y la contraseña en blanco.
**2.1:**- Para acceder desde ssh introducir el comando ```sudo ssh 192.168.1.99@admin``` en la terminal, posteriormente introducir la contraseña.
**3r PASO**- Para guardar las configuraciones ir a configuration, backup e introducir un usb en el puerto de la torre con formato fat. 
**3.1:**- Para guardar la configuración desde la terminal se debe acceder a la terminal del FortiGate 121G desde la parte superior derecha e introducir el comando execute backup config usb nombre_del_archivo.txt
**4o PASO**- Cuando se acaben las configuraciones pertimnentes poner execute factoryreset en la terminal del FortiGate121G.


```bash
