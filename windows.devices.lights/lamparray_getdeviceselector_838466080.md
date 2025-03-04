---
-api-id: M:Windows.Devices.Lights.LampArray.GetDeviceSelector
-api-type: winrt method
ms.custom: RS5
---

<!-- Method syntax.
public string LampArray.GetDeviceSelector()
-->

# Windows.Devices.Lights.LampArray.GetDeviceSelector

## -description
Retrieves an Advanced Query Syntax (AQS) string encompassing all LampArray devices on the system. 

## -returns
An AQS string encompassing all LampArray devices on the system.

## -remarks
You can use this string with the [DeviceInformation.FindAllAsync](/uwp/api/windows.devices.enumeration.deviceinformation.findallasync) method or [DeviceWatcher](../windows.devices.enumeration/devicewatcher.md) to get [DeviceInformation](../windows.devices.enumeration/deviceinformation_findallasync_1257462890.md) objects for those LampArrays

## -see-also

[Dynamic lighting](/windows/uwp/devices-sensors/lighting-dynamic-lamparray)

## -examples

[AutoRGB Sample](https://github.com/microsoft/Dynamic-Lighting-AutoRGB)

Demonstrates how to extract a single, representative color from a desktop screen and use it to illuminate LED lamps on a connected RGB device.
