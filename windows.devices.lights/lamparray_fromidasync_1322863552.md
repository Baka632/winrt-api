---
-api-id: M:Windows.Devices.Lights.LampArray.FromIdAsync(System.String)
-api-type: winrt method
ms.custom: RS5
---

<!-- Method syntax.
public IAsyncOperation<LampArray> LampArray.FromIdAsync(String deviceId)
-->

# Windows.Devices.Lights.LampArray.FromIdAsync

## -description
Retrieves a LampArray object asynchronously for the LampArray device that has the specified plug and play (PnP) device identifier/device instance path.

## -parameters
### -param deviceId
The device identifier/device instance path of the device. To obtain the value, get the [DeviceInformation.Id](../windows.devices.enumeration/deviceinformation_id.md) property value retrieved from [DeviceWatcher](../windows.devices.enumeration/devicewatcher.md)

## -returns
Returns an `IAsyncOperation(LampArray)` object that returns the results of the operation.

Use [DeviceWatcher](../windows.devices.enumeration/devicewatcher.md) to determine the device identifer.

## -remarks

## -see-also

[Dynamic lighting](/windows/uwp/devices-sensors/lighting-dynamic-lamparray)

## -examples

[AutoRGB Sample](https://github.com/microsoft/Dynamic-Lighting-AutoRGB)

Demonstrates how to extract a single, representative color from a desktop screen and use it to illuminate LED lamps on a connected RGB device.
