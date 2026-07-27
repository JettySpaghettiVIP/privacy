# Pincognito Privacy Policy

**Effective date:** July 27, 2026

Pincognito is a location-scenario simulator for Android. It is published by
**JettySpaghettiVIP** (“we”, “us”). This policy explains what the app handles and when
information leaves the device.

## The short version

Pincognito has no account system, advertising, analytics, telemetry, or crash-reporting service. We
do not sell personal information. Most app data stays on the device. Map, place-search, nearby-place,
and route features contact mapping services over HTTPS, which means those services receive the
requested search text or coordinates and normal network information such as the device IP address.

## Information the app handles

### On the device

Pincognito stores information the user creates or needs to operate the app, including:

- saved places, routes, routines, schedules, scenarios, and app settings;
- the last simulated position and current trip state needed for crash recovery;
- a local, user-visible history of planned and completed activity, with positions reduced to roughly
  neighborhood-level precision;
- cached map tiles and nearby-place results; and
- backup files the user explicitly exports or imports.

The user can clear history and map data in the app. Saved app data can be removed by clearing the
app’s storage or uninstalling it.

### Precise location

If the user grants Android’s location permission, Pincognito can read the device’s current or
last-known precise location so the map can open nearby and a trip can start from the current
position. This permission is optional. A user can choose points on the map instead.

Pincognito also handles coordinates the user selects for simulated places, routes, and scenarios.
Simulated coordinates are not a claim about the user’s physical location.

### Information sent to mapping services

Only when the related feature is used, Pincognito sends:

- place-search text and reverse-geocoding coordinates to OpenStreetMap Nominatim;
- route endpoints and stops to the configured OSRM routing service;
- map viewport coordinates and nearby-place queries to OpenStreetMap Overpass services; and
- map tile coordinates to the configured map-tile service.

These requests use HTTPS. The service operators also receive normal connection information,
including IP address and the Pincognito app identifier. Their handling of that information is
governed by their own terms and privacy notices. Do not enter confidential or personal information
into place search.

The final production providers and links to their privacy notices will be listed here before this
policy is published:

- [MAP TILE PROVIDER AND PRIVACY NOTICE]
- [GEOCODING PROVIDER AND PRIVACY NOTICE]
- [ROUTING PROVIDER AND PRIVACY NOTICE]
- [NEARBY-PLACE PROVIDER AND PRIVACY NOTICE]

## Android backup and user exports

Android may include saved places, routes, routines, schedules, scenarios, and settings in the
user’s encrypted Google account backup or device-to-device transfer, according to the user’s Android
backup settings. Local activity history and crash-recovery state are excluded.

The in-app backup feature writes a file only after the user chooses a destination through Android’s
system file picker. Pincognito does not upload that file to us.

## Sharing

We do not sell personal information or share it for advertising. Information is transmitted to the
mapping providers above only to return maps, search results, nearby places, and routes requested by
the user. We may disclose information if legally required, but Pincognito currently operates no
developer backend that stores app-user data.

## Children

Pincognito is a developer and testing utility and is not directed to children.

## Security and retention

Network requests use HTTPS. On-device data remains until the user clears it, deletes the relevant
item, clears app storage, or uninstalls the app. Cache and history stores are bounded and can be
cleared in the app. External mapping providers control their own server logs and retention.

## Changes

We may update this policy when app features or service providers change. The effective date above
will be updated when that happens.

## Contact

Privacy and support questions: **support@ctrlaltresist.com**

