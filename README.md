# Lightweight Openhab on a raspberrypi 3b

Installations on RPI:
- openhab
- java
- vim

Check the access (mod) of folder:
etc/openhab2/

Required bindings:
- Network Binding
- HTTP Binding
- MQTT Binding

Required misc
- Embedded MQTT Broker

Required transformations:
- JSONPath Transformation

Autocopy to RPI by script:
- autocopy

ToDo:
- Dehumidifier regulation
- Dehumidifier status (Normal operation, Water full, Connection problem)
- Absence algorithm
- Usage of Max-Humidity Setpoint
- Telegram message