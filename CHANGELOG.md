# Hostinger Public API
### Tue Mar 18 2025
- `GET` `/api/vps/v1/virtual-machines/{virtualMachineId}/metrics`:
  - `200` response: changed `uptime`.`usage`.`type` to `array`
  - `200` response: added `uptime`.`usage`.`items`
  - `200` response: changed `incoming_traffic`.`usage`.`type` to `array`
  - `200` response: added `incoming_traffic`.`usage`.`items`
  - `200` response: changed `outgoing_traffic`.`usage`.`type` to `array`
  - `200` response: added `outgoing_traffic`.`usage`.`items`
  - `200` response: changed `disk_space`.`usage`.`type` to `array`
  - `200` response: added `disk_space`.`usage`.`items`
  - `200` response: changed `ram_usage`.`usage`.`type` to `array`
  - `200` response: added `ram_usage`.`usage`.`items`
  - `200` response: changed `cpu_usage`.`usage`.`type` to `array`
  - `200` response: added `cpu_usage`.`usage`.`items`
