# todo

## Set-up
... venv

```bash
pip install --no-index --find-links deps -r requirements.txt
```

## Swagger UI
```bash
https://sharolyn-windtight-dismissively.ngrok-free.dev/docs
```

## Endpoints
```bash
https://sharolyn-windtight-dismissively.ngrok-free.dev/add-device?name=<name>&type=<light or plug>&status=<on or off or offline>&brightness=1&color=%23<hex color>
```
```bash
https://sharolyn-windtight-dismissively.ngrok-free.dev/get-device
```
```bash
https://sharolyn-windtight-dismissively.ngrok-free.dev/toggle?id=<id>
```
```bash
https://sharolyn-windtight-dismissively.ngrok-free.dev/change-color?id=<id>&color=%23<hex color>
```
```bash
https://sharolyn-windtight-dismissively.ngrok-free.dev/change-name?id=<id>&targetname=<new name>
```
```bash
https://sharolyn-windtight-dismissively.ngrok-free.dev/change-brightness?id=<id>&brightnesslevel=<brightness level [1, 70, 150, 254]>
```
```bash
https://sharolyn-windtight-dismissively.ngrok-free.dev/delete-device?id=<id>
```
```bash
https://sharolyn-windtight-dismissively.ngrok-free.dev/change-actionmode?id=<id>&actionmode=<mode only up to 10>
```
## Color Wheel for the Hex code
```bash
https://www.canva.com/colors/color-wheel/
```
