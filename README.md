# DeviceInfo

Swift does not currently allow getting detailed information about the current device; the most it can show is "iPhone" or "iPad". 

Add this swift file to your project, and implement like so:

```
let deviceInfo = DeviceInfo()
print("\(deviceInfo.getDeviceModel())")      // iPhone 6 (A1549/A1586)
```
