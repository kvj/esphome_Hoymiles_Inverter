### ESPHome component for Hoymiles Inverters using OpenDTU

* Uses [tbnobody/OpenDTU](https://github.com/tbnobody/OpenDTU) library for communication with Inverter
* Only CMT2300A radio is currently supported
* The components exposes a bare minimum set of sensors: Power, Energy, Current, Voltage of each channel and editable limit entities
* See `project_sample.yaml` for the generic idea on how to use the component
