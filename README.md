# Packet Tracer: Configuración de un Enrutador Inalámbrico y Clientes

## Resumen del Proyecto
Este proyecto de simulación en Cisco Packet Tracer consiste en conectar y configurar la red doméstica cableada e inalámbrica para un hogar, garantizando conectividad segura a Internet para múltiples dispositivos.

## Objetivos
1. **Conexión Física de Dispositivos:**
   - Conectar la acometida de cable coaxial desde el *Cable Splitter* hacia el *Cable Modem* y la televisión.
   - Enlazar el *Cable Modem* al puerto Internet del *Home Wireless Router* mediante cable directo Ethernet.
   - Conectar las PCs de escritorio (*PC de Oficina* y *PC de Dormitorio*) a los puertos LAN GigabitEthernet del router.

2. **Configuración del Enrutador Inalámbrico:**
   - Configuración del servidor DHCP local y restricción del número máximo de usuarios a 10.
   - Actualización de las credenciales de administración del router (cambio de contraseña por defecto a `MyPassword1!`).
   - Habilitación de la red Wi-Fi de 2.4 GHz con SSID `MyHome`.
   - Implementación de seguridad inalámbrica **WPA2 Personal** con la frase de contraseña `MyPassPhrase1!`.

3. **Configuración de Clientes y Verificación de Conectividad:**
   - Obtención de direcciones IP dinámicas vía DHCP en las PCs cableadas.
   - Conexión de la computadora portátil (*Laptop*) a la red Wi-Fi `MyHome` mediante la clave precompartida.
   - Pruebas de conectividad Web navegando exitosamente al servidor externo `skillsforall.srv` desde todos los clientes.

## Requisitos
- **Cisco Packet Tracer** (v8.0 o superior).
