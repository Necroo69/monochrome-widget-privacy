# Monochrome Widget — Privacy Policy

**Effective date:** 9 November 2026
**Developer:** Necroo69
**Contact:** open an issue at <https://github.com/Necroo69/monochrome-widget-privacy/issues>

Monochrome Widget ("the app") puts clock, world clock, date, battery, weather,
note and quick-control widgets on your Android home screen. This policy explains what information the app uses, where
it goes, and the choices you have.

Monochrome Widget is an independent app and is not affiliated with Nothing
Technology Limited.

## The short version

- The app has **no accounts, no ads, no analytics and no crash reporting**.
- The developer runs **no servers** and receives **none** of your data.
- Your **approximate location** (or a city you choose) is sent to the weather
  service **Open-Meteo** so the weather widget can show a forecast.
- Everything else (your widget styles, settings, notes and chosen cities) stays
  on your phone.

## Information the app uses

### Approximate location (optional)

If you choose **Use my location**, the app asks for Android's *approximate
location* permission (`ACCESS_COARSE_LOCATION`). It reads your location only
while the app is open, never in the background, and does not ask for precise
location.

- The coordinates are saved on your phone so the weather widget can refresh
  later without asking again.
- The coordinates are sent to **Open-Meteo** to get the forecast (see below).
- To show a place name (for example "Berlin"), the app asks your phone's
  built-in geocoder to turn the coordinates into a place name. On most phones
  this geocoder is provided by Google, which receives the coordinates for that
  lookup under [Google's Privacy Policy](https://policies.google.com/privacy).

You can skip this and search for a city instead. Weather then works without the
location permission.

### City search (optional)

When you search for a city, the text you type is sent to Open-Meteo's
geocoding service to find matching places. The city you pick and its
coordinates are saved on your phone.

### Widget settings

Your widget styles (colors, corners, text), app settings (theme, 12/24-hour
clock, °C/°F, weather refresh rate) and the last forecast are stored only on
your phone.

### Notes

Text you write in the sticky note widget is stored only on your phone and is
never sent anywhere.

### World clock cities

The cities shown by the world clock widget are picked from a list built into
the app. Choosing a city sends nothing over the internet, and your choice is
stored on your phone.

### Flashlight and notifications

The quick-controls widget can turn your phone's flashlight on and off. It
switches only the camera's flash; it does not open the camera, take photos or
record video, and it needs no camera permission.

While the flashlight is on, the app shows a "Flashlight on" notification so the
light can stay on and you can turn it off. On Android 13 and later the app asks
for permission to show notifications (`POST_NOTIFICATIONS`) when you add this
widget. The app uses notifications for nothing else.

### Settings shortcuts

The Wi-Fi, Bluetooth and Do Not Disturb buttons simply open Android's own
settings screens. The app does not read or change those settings itself.

### Battery level

The battery widget reads your phone's battery level and charging state from
Android. This never leaves your phone.

## Third-party service: Open-Meteo

Weather data comes from [Open-Meteo](https://open-meteo.com/). When the app
requests a forecast or searches for a city, Open-Meteo receives the coordinates
or search text, plus the technical details any website request includes (such
as your IP address). The app sends no name, account, device ID or advertising
ID. Open-Meteo's handling of this information is described in its
[terms and privacy policy](https://open-meteo.com/en/terms).

## Backups

If Android backup is turned on for your phone, Android may include the app's
saved settings and location in your device backup (for example, your Google
account backup). This is controlled by your phone's backup settings, not by the
app.

## What the app does not do

- It does not sell or share your information for advertising.
- It does not collect contacts, photos, files, precise location, or any
  identifier for tracking.
- It does not use the camera to take pictures or video.
- It does not send data to the developer.

## Data retention and deletion

All data is stored on your phone. To delete it, clear the app's storage in
Android Settings or uninstall the app. To stop location use at any time, revoke
the location permission in Android Settings, or pick a city instead.
Open-Meteo's retention of request logs is covered by its own policy.

## Children

The app is not directed at children under 13 and does not knowingly collect
personal information from them.

## Changes to this policy

If this policy changes, the new version will be posted at this address with a
new effective date.

## Contact

Questions about this policy: open an issue at <https://github.com/Necroo69/monochrome-widget-privacy/issues>.
Issues are public, so please do not include personal details.
