# openOS
The iPhone4 is the best phone Apple has built but abandoned by now. This project makes it fit again for everyday use ☺️

# 3rd-party tweaks
In order to get things installed and managed conveniently a few tweaks seem advisable. This list is nowhere complete and some entries might be just temporarily until a better solution is implemented.
- aptitude
- com.slugrail.ipainstaller
- com.conradkramer.open

# Things currently worked on
## Push notifications
While Apple still pushes notifications to this platform, you need an active developer subscription to use them.
This requirement contradicts the open-ness the project aims for, a better solution is needed, especially as a huge number of apps needs new implementations or tweaks and would have no push notifications to begin with.

## Workout export
Multiple accessories which record and transfer workouts to the device. Sadly the capability to export this records is broken as Nike doesn't support them any longer.
While the export of workouts is no longer limited to Nike's infrastructure, a replacement for the infrastructure needs still to be implemented.

## SSL support
The platform needs its root certificates updated. Even after such an unpdate there are several servers the device won't be able to communicate with as it doesn't support the ciphers required for the handshake. The existing calls to NSURL… need to be fixed.

# Things that need fixing or are missing
- AppStore is not accessible
- Common apps
  - banks
  - social media
- Tools to make development easier. The easier the development is going to be, the more likely it will be to get things fixed or added 
  

