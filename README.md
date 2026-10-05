# Urban Air Station Threshold Alerts

Build a environment prototype that uses CO2 sensor, turbidity sensor, solar panel to notify users when measurements exceed limits. Include setup instructions, a circuit diagram, tested firmware, and sample output.

## Project details

| Field | Value |
| --- | --- |
| Roadmap ID | 202 |
| Category | Environment |
| Platform | Arduino MKR WAN 1310 |
| Difficulty | Intermediate |
| Estimated build time | 24 hours |
| Connectivity | LTE-M |
| Core components | CO2 sensor, turbidity sensor, solar panel |
| Control mode | threshold alert |

## Repository layout

- `firmware/urban-air-station-threshold-alerts/urban-air-station-threshold-alerts.ino`: runnable firmware or application
- `docs/wiring.md`: suggested low-voltage wiring plan
- `docs/architecture.md`: system data flow
- `docs/test-plan.md`: repeatable verification steps
- `sample-data/example.json`: example telemetry record
- `tools/validate.py`: dependency-free repository validation

## Quick start

1. Open `firmware/urban-air-station-threshold-alerts/urban-air-station-threshold-alerts.ino` in Arduino IDE or Arduino CLI.
2. Select the board matching **Arduino MKR WAN 1310**.
3. Compile and upload, then open the serial monitor at 115200 baud.

## Expected behavior

Threshold Alerts demonstration with repeatable test steps. The default implementation supports simulated or generic analog inputs so the control path can be exercised before hardware-specific drivers are added.

## Hardware adaptation

The included code is a safe reference implementation. Update pin assignments and sensor conversions from the exact component datasheets, then repeat the test plan before connecting actuators.

## License

MIT
