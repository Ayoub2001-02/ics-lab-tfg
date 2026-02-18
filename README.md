# Laboratorio ICS-IoT para TFG

Este repositorio contiene documentación y recursos asociados al laboratorio de Ciberseguridad en IoT desarrollado para un Trabajo de Fin de Grado. El entorno simula una red ICS (Industrial Control System) con dispositivos Modbus y ataques desde una máquina Kali.

## Componentes del laboratorio

- **SCADA** (Ubuntu Server + Scada-LTS en contenedores)
- **PLC1 y PLC2** (Ubuntu Server + ModbusPal)
- **Attacker** (Kali Linux + SMOD)

## Máquinas virtuales

Las 4 imágenes OVA exportadas están disponibles en el siguiente directorio:

🔗 (https://drive.google.com/drive/folders/1wvd4xKzsR0Kd6sji58K4bfQM720C5fKv?usp=drive_link)

Esto se debe a que no se permiten ficheros con un tamaño superior a 25M.

## Casos de uso incluidos

- Lectura/escritura Modbus desde SCADA
- Simulación de sensores
- Ataque: WriteSingleRegister con SMOD
