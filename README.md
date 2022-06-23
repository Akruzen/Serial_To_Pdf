# Serial_To_Pdf
Converts serial communication data received  to pdf. Based on serial communication driver provided by FTDI.

## Details
Set the baud rate, stop bit, and parity from the settings menu. After the desired data is received, click on "Convert to PDF" button to create a PDF in the documents
folder in the internal storage of device.
Project still a work in progress, hence the UI might not be intuative and attractive, but it serves its purpose functionality-wise and the visual overhaul is the only part left.
Note: Due to PendingIntent requirement of Android 12 as seen [here](https://developer.android.com/about/versions/12/behavior-changes-12#pending-intent-mutability), the driver
jar file which uses this Pending Intent hasn't been updated as seen [here](https://www.ftdichip.com/old2020/Android.htm). Due to this limitation, the app will not
work on Android 12 devices and above.
