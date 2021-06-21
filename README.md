# iaq-monitor-demo-errata
Errata for the IAQ Monitor Demo project/repository - to be merged in to the original [project](https://www.hackster.io/dxcfl/personal-iaq-monitor-19667c "Personal IAQ Monitor") project / [repository](https://github.com/dxcfl/iaq-monitor-demo "IAQ Monitor Demo")  after June 30, 2021.

## Erratum #1

In the [schematics](https://www.hackster.io/dxcfl/personal-iaq-monitor-19667c#schematics "Personal IAQ Monitor - Schematics"), the connection between the WAKE pin on the CCS811 and GND is missing.  The WAKE pin needs to be pulled to ground in order to communicate with the sensor.

![Schematics](https://github.com/dxcfl/iaq-monitor-demo-errata/raw/main/%5Bproject%5D%20IAQ%20Monitor%20Demo%20-%20Wiring%20(Erratum).png "Schematics")

