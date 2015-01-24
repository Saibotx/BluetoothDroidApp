# BluetoothDroidApp

What each file does:

DeviceControlActivity.java - This is where the logic for bluetooth "handshake" happens
DeviceScanActivity.java - Basically upon app startup, this scans for all BLE in the area and allows you to connect to it.
BluetoothLeService.java - (Almost) generic bluetooth le gatt based off sample code.
SampleGattAttributes.java - This includes most of the UUIDs for the HM-10 that we're inteacting with.
