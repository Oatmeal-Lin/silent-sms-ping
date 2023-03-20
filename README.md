# Silent SMS ping and detector

This is a fork and new development of [Android Silent SMS Ping](https://github.com/itds-consulting/android-silent-ping-sms). It does not require rooted device.

## What is silent SMS?

A silent SMS (Short Message Service) is a type of text message that is sent to a mobile phone without the knowledge or consent of the phone's user. Unlike regular SMS messages silent SMS messages are invisible and do not trigger any notification or sound on the target phone.

By sending silent SMS on a target phone, a sender can detect whether mobile phone is online or offline. However, silent SMS could also be used to determine the location of the target mobile device. When a silent SMS is sent to the target device, it forces it to update the current (typically the nearest) serving base station onto the cellular network.

Silent SMS messages are often used by law enforcement agencies for surveillance and tracking purposes, because they allow them to locate the position of a mobile phone without alerting the user.

## What is this application doing?

This application, which is a fork of [Android Silent SMS Ping](https://github.com/itds-consulting/android-silent-ping-sms), can send silent SMS messages and determine if a target phone is online or offline. But it can also detect received silent SMS messages and alert user that he has received silent SMS.

The future version will also implement data collection for threat analytics. Stay tuned and check out the issues!

This application is running on new Android devices and does not require rooted device.

### New development and design

The original application has not been maintained for several years. Currently new development of the application is ongoing. In the first stage we have updated SDK (to version 33) and Java (to version 11). In the second stage we will design new outlook of the application. In the third stage some new functionality will be added.

Developers and designers:
- [Jure Poljšak](https://github.com/barracuda-fsh)
- [Matej Kovačič](https://github.com/MatejKovacic)
- Vesna Trenchovska

### License

The project is licensed under the [GNU General Public License version 3 (or newer)](https://github.com/MatejKovacic/silent-sms-ping/blob/master/LICENSE).

### APK download (for testing)

- [debug APK from 20-03-2023](https://github.com/MatejKovacic/silent-sms-ping/blob/master/silent-sms-app-debug_20-03-2023.apk) - click download button to get it on your device and then install it as third party app.
