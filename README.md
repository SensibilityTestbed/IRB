# Sensibility Testbed Privacy Policy and IRB

The Sensibility Testbed app accesses sensors on your smartphone or
tablet device. All access happens within the limitations set forth
by Sensibility Testbed's IRB policy #15-10751 from NYU, titled
"Privacy-preserving Experimentation with Sensibility Testbed."

The document is contained in this repository for your review.

The Sensibility Testbed app also accesses certain functions
(detailed below) that require Android's `READ_PHONE_STATE`
permission. Depending on your Android version, you have been
informed about this requirement at install time, or whenever
the app attempts to use these functions. These functions identify
your device's software version, SIM card operator and country,
network operator, etc.

However, despite requiring the same `READ_PHONE_STATE` permission,
the Sensibility Testbed app does *not* access your device's unique
hardware ID, subscriber ID, or SIM card serial number. You can check
this claim by inspecting the app's source code, available online
at https://github.com/SensibilityTestbed/sensibility-testbed .

-------

The Sensibility Testbed app uses the following functions that
require the `READ_PHONE_STATE` permission:
* `getNetworkOperator`
* `getNetworkOperatorName`
* `getAllCellInfo`
* `getSimOperator`
* `getSimCountryIso`
* `getSimOperatorName`
* `getSimState`
* `getCallState`
* `getDataActivity`
* `getDataState`
* `getNetworkType`
* `getPhoneType`
* `getDeviceSoftwareVersion`

