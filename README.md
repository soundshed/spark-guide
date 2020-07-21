# Spark Amp Guide
A community-maintained guide to getting started with the Positive Grid Spark Amp, including frequently asked questions.

## Orders
Most/many spark amp orders are pre-orders via the Positive Grid website. Depending on your geographic location and when you ordered most customers have experienced long (several month) delays in receiving their amps. Customers ordering today can expect less wait time. The amp is not generally available in stores currently.

## Getting Started

## Apps

Get the Spark Amp App for your device:

Android: https://play.google.com/store/apps/details?id=com.positivegrid.spark&hl=en

iPad/iPhone: https://apps.apple.com/au/app/spark-amp/id1457653921

**There is currently no app for desktop computers (Windows or mac OS).**

Confusingly, Positive Grid also make a music tuition app called Spark Edu which is a subscription service that is no relation to your Spark amp. You do not have to pay to use the spark app with your amp, so if something is asking for money you've gone to the wrong place.

## Using The Amp
- You can use the amp without the app but functionality is limited to the basic controls on the amp itself. The real felxibility of the amp comes from using it with the app.
- A common issue is that either the app backing tracks come through the amp but changing controls doesn't work or vice-versa. The amp uses two types of Bluetooth connections (Bluetooth Audio `Spark 40 Audio` and Bluetooth Low Energy `Spark 40 BLE`). On iOS these both need to be connected before you use the app.
- Your serial number (for registration etc) is visible in the App when the amp is connected and is also on a little sticker near the Aux port.

## Updating Firmware
The *Firmware* is the software the amp uses internally to function (bluetooth connectivty, amp and FX models, controls etc). The firmware version you have installed can be see in the app when the amp is connected (it's a version number such as `1.2.3.37`).

To update your firmware see the PG guide:
https://help.positivegrid.com/hc/en-us/articles/360038685111-How-To-Update-The-Firmware-on-Spark-

- on Windows you may have to install the Spark ASIO driver first (see the above link) and reboot before attempting the update.
- on Mac OS you may have to allow the app to run via the the mac OS Security setting, because the app has been downloaded from the internet.


## Wireless Inputs and Headphones
- You can use any normal wireless transmitter/reciever with the Spark if you want to. This also reduces line hum that would often  be induced by connecting a guitar cable. Amazon/eBay etc have many cheap transmitter/receivers that work reasonably well. Generally avoid Bluetooth transmitters/recievers due to bluetooth audio latency.
- Bluetooth Headphone will not generally work with the Spark. There is no way to tell them to connect to the amp (unlike conencting to a computer, phone etc). In addition Bluetooth audio often has very high latency (the delay between strumming the guitar and hearing the results back grom the amp) which makes it inappropriate for this use.

## Common Amp Issues
- Screeching/siren tone when changin presets: This is known bug, update the amp firmware (see below).

### Hum and Earthing issues
Some users of the first generation Spark Amp have reported hum (buzzing) when using the amp. This has mostly been attributed to lack of electrical grounding on the power supply unit and affects users differently dependin on their house wiring and local electrical interference. Affected users should open a support ticket with PG to discuss. Several users have reported being sent replacement power supplies by PG to help resolve the issue.

Note that in general, hum/buzz is considered a normal characteristic of amplifiers when used on high-gain settings, because low level electrical interference is amplified by the gain stages of the amp (common to all amplifiers). Over the years this has led to the introduction of Noise Gates (which silence noise when the guitar is not playing). The Spark has a noise gate setting which you can adjust in the app.

Ensure the Noise Gate effect is enabled and adjust the Threshold value (when no notes are playing) to the minimum level required to line/pickup noise but to still allow for note sustain.

Noise gate usage: https://www.facebook.com/jonathan.marriott.96/videos/3165897856812563

### Sustain/note cuts out
If playing a note leads to the sound cutting in and out erraticaly, adjust the Noise Gate settings within the app for the preset you are using. Ensure the Noise Gate effect is enabled and adjust the Threshold value (when no notes are playing) to the minimum level required to line/pickup noise but to still allow for note sustain. The required level varies slightly for each guitar/pickup combination.

## Using The App
- Editing presets: swipe the little pedal image up/down to disable/enable the effect, double tap the little pedal image to get the list of effect types to choose from. Swip the FX chain left and right to see the full list of FX in the current chain.

## SmartJam

## Recording
- On Windows, install and use the Spark ASIO driver to reduce audio input/output latency: https://help.positivegrid.com/hc/en-us/articles/360039598451-Spark-Windows-ASIO-Driver-
- In any recording software, make sure the Spark is selected as the track input, and recording is armed.

## Resources
- The `Spark Amp Owners Club` facebook group is probably the most useful and active community for Spark Amp Owners: https://www.facebook.com/groups/202479867664001
- The PG forum: https://forum.positivegrid.com/category/28/spark
