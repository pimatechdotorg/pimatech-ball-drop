# Pimatech Ball Drop Calculator

A free, open-source Android calculator for countersink inspection using a gage ball. Predict the ball-top measurement, calculate countersink major diameter from a measured height, and choose a ball whose contact lies near the middle of the conical wall. Includes inch/mm units, tolerance evaluation, contact geometry, and a local ball inventory.

## Download

See [Releases](https://github.com/pimatechdotorg/pimatech-ball-drop/releases) for the Android APK and matching source archive. Version 1.0.2 is a **development preview**, not a production-signed or Google Play release. Android 8.0 or later. Runs offline without accounts, advertisements, analytics, subscriptions, or Internet permission.

## Source and building

The complete version 1.0.2 project is preserved in [Pimatech-Ball-Drop-1.0.2-Source.zip](Pimatech-Ball-Drop-1.0.2-Source.zip). Download and extract it, then open its `PimatechBallDrop` directory in Android Studio. The archive includes Kotlin/Compose application source, the pure Kotlin calculation engine, Gradle wrapper, tests, operator instructions, and recorded build/validation evidence. See the enclosed README for JDK 17 and Android SDK 35 build instructions.

The source is currently stored as a versioned archive. Private signing keys are excluded.

## Installation

Download the APK from Releases, open it on Android, and allow the downloading browser or Files app to install unknown apps if prompted. Keep the APK name and development status visible when sharing it. Existing 1.0.1 users can update to 1.0.2 in place. Users of the original 1.0.0 test build must record their saved inputs and uninstall that version first because its signing certificate differs.

## Measurement limits

The calculator assumes an ideal sphere and a straight, coaxial conical countersink. It checks whether contact falls on the conical wall. It is a calculation aid, not a calibrated instrument: verify ball size, hole size, included angle, part condition, and measurement capability for your inspection requirement. Blends, edge breaks, form errors, temperature effects, and measurement uncertainty are not compensated. Clear the previous measurement before inspecting another part.

## License

MIT License; see LICENSE. Third-party components retain their own licenses.

Proudly made and released open source by PimaTech.org.
