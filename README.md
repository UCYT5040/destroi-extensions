# Destroi Extensions Documentation
## manifest.json
Supply information about your extension.
## destroi.js (alpha)
destroi.js supplies information such as the device gyroscope (position)
### Issues
- Extensive lag when enabling destroi.js
### Functions
#### getDevice
Get the users current device.
returns `device`
### Types
#### device
##### device.getPos
```js
getDevice().getPos() // [x, y, z]
```
returns `array`
