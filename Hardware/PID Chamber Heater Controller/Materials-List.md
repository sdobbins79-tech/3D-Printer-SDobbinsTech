# PID Chamber Heater Controller Materials List

This list covers the standalone PID controller enclosure project. The PTC heater and fan assembly is still in progress and will be documented later.

## Printed Parts

- [`PID enclosure.stl`](./stl/PID%20enclosure.stl) - main printed controller enclosure
- [`PID door.stl`](./stl/PID%20door.stl) - printed enclosure door / cover
- [`PID knob.stl`](./stl/PID%20knob.stl) - printed knob

## Source Files

- [`PID enclosure.123dx`](./source/PID%20enclosure.123dx)
- [`body.123dx`](./source/body.123dx)
- [`door.123dx`](./source/door.123dx)
- [`knob.123dx`](./source/knob.123dx)
- [`screw.123dx`](./source/screw.123dx)

## Purchased Parts

- [3Dman IEC320 C14 fused rocker switch power inlet module](https://www.amazon.com/3Dman-Rocker-Switch-Socket-C14-2pcs/dp/B07RQV2NPN)
- [DORHEA 120 mm x 25 mm AC-powered cooling fan with speed controller](https://www.amazon.com/dp/B088WB9D5T)
- [CGELE PID temperature controller kit with SSR-40DA solid state relay, K-type thermocouple, and heat sink](https://www.amazon.com/dp/B08ZYHFBYW)
- [Walfront 110V 500W ceramic PTC air heater](https://www.amazon.com/dp/B07P5NCR2F)
- [Thermal interface pad / thermal sheet for SSR and heat sink](https://www.amazon.com/dp/B0BLL88WQW) - verify exact listing before ordering

## Hardware and Consumables

- M3 heat-set inserts
- M3 screws
- M3 washer
- Short PID-to-SSR control wire, approximately 100 mm / 4 in
- Fork/spade terminals or other suitable crimp terminals for the parts used
- Double-sided tape for the fan controller
- Thermal paste or verified thermal interface material for the SSR / heat sink
- Wire rated for the voltage and current used by the heater circuit

## Rating Notes

- The linked PTC heater is listed as `110V 500W`, which is about `4.55A`.
- The included SSR is an `SSR-40DA` style solid state relay, commonly marked as `40A`, but that number should not be treated as the safe limit for this printed enclosure.
- The practical safe limit depends on the fuse, wire gauge, IEC inlet, SSR heat sink, airflow, enclosure temperature, and wiring quality.
- This project should be treated as a `500W heater build` unless the builder is qualified to re-rate the full electrical system.
