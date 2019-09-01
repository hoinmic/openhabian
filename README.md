# Lightweight Openhab on a raspberrypi 3b

## Information Flow

```mermaid
graph TD
A[Absence rule]
B[dehumidifier rule]
C[Illumination rule]
D[powerhouse low tariff rule]
E[time segment of the day rule]

W(Mobile phone)
X(Shelly Cloud HT sensor)
Y(Astro binding)
Z(MyStrom switch devices)

W --> A
Y --> E
D --> B
X --> B
E --> C
A --> C
```

## Add-ons

- Network Binding
- HTTP Binding
- MQTT Binding
- Astro Binding
- rrd4j Persistence (-> set as default)
- Embedded MQTT Broker
- JSONPath Transformation

## Installations on RPI

- Raspbian Buster Lite
- openhab
- java

## Additional informations

- In top foleder is a script to automatic copy the openhab files to RPI (file: autocopy)
- Set time on RPI

## ToDo

- Telegram message
- LaMetric
- Add moving average filter for dehumidifier
- Two channel chart?
