# Privacy Policy for Colorado Avalanche Alerts

**Last Updated:** [DATE]

## Introduction

Colorado Avalanche Alerts ("we", "our", or "the app") is committed to protecting your privacy. This Privacy Policy explains how our mobile application collects, uses, and safeguards your information.

## Information We Collect

### Location Data
- **Saved Locations**: You can save multiple geographic coordinates with optional custom names. These locations are stored locally on your device only and are never transmitted to our servers.
- **Point-in-Polygon Calculations**: The app performs calculations on your device to determine which Colorado Avalanche Information Center (CAIC) forecast zone contains your saved locations.

### Data from Third-Party Services
The app retrieves publicly available data from:
- **Colorado Avalanche Information Center (CAIC) API**: Avalanche forecasts and regional discussions
- **National Weather Service (NWS) API**: Weather forecasts
- **CAIC GeoJSON API**: Geographic boundary data for forecast zones

These requests are made directly from your device to the respective APIs and are not routed through our servers.

## How We Use Your Information

- **Forecast Display**: To show you relevant avalanche forecasts for your saved locations
- **Background Notifications**: To alert you when new forecasts are published (if you enable notifications)
- **Offline Functionality**: Cached forecast data is stored locally for up to 36 hours to allow offline access

## Data Storage

All data is stored locally on your device:
- **Saved locations** (coordinates and custom names)
- **App preferences** (debug mode, notification settings, etc.)
- **Cached forecast and weather data** (automatically expires after 36 hours)
- **Application logs** (for debugging, if debug mode is enabled)

**We do not operate any servers that collect, store, or process your personal information.**

## Third-Party Services

The app connects to the following external services:

### Colorado Avalanche Information Center (CAIC)
- **Purpose**: Retrieve avalanche forecasts and regional discussions
- **Data Shared**: None. Requests are standard HTTP GET requests.
- **Privacy Policy**: https://avalanche.state.co.us/privacy-policy

### National Weather Service (NWS)
- **Purpose**: Retrieve weather forecasts
- **Data Shared**: Geographic coordinates (to retrieve location-specific forecasts)
- **Privacy Policy**: https://www.weather.gov/privacy

These services may log standard web request information (IP address, request time) as part of their normal operations. We do not control or have access to this information.

## Permissions

The app requests the following Android permissions:

- **INTERNET**: Required to fetch avalanche forecasts and weather data
- **ACCESS_NETWORK_STATE**: To check if internet connection is available
- **POST_NOTIFICATIONS**: To send local notifications about new forecasts (Android 13+)
- **VIBRATE**: To vibrate when notifications are received
- **RECEIVE_BOOT_COMPLETED**: To reschedule notification checks after device restart
- **WAKE_LOCK**: To ensure background tasks complete when checking for new forecasts

## Children's Privacy

This app does not knowingly collect personal information from children under 13. The app is intended for outdoor enthusiasts who engage in backcountry winter recreation and should be used by individuals capable of understanding avalanche safety information.

## Changes to This Privacy Policy

We may update this Privacy Policy from time to time. Changes will be reflected in the "Last Updated" date at the top of this policy. Continued use of the app after changes constitutes acceptance of the updated policy.

## Data Security

- All data is stored locally on your device using Android's secure Preferences API
- No user accounts or authentication are required
- No data is transmitted to our servers (we don't operate any servers for this app)
- Communication with third-party APIs uses HTTPS encryption

## Your Rights

You have full control over your data:
- **Delete Locations**: Remove saved locations at any time through the app's Location Management page
- **Clear Cache**: Force clear cached data via the app's Debug Settings
- **Uninstall**: Completely removes all app data from your device

## Contact Information

If you have questions about this Privacy Policy or the app's data practices, please contact:

**Email:** [YOUR EMAIL]
**GitHub Issues:** https://github.com/[YOUR-USERNAME]/AvalancheAlert/issues

## Disclaimer

This app provides avalanche forecast information for informational purposes only. Always verify forecasts through multiple sources and obtain proper avalanche safety training before entering avalanche terrain. The app is not a substitute for professional avalanche education and should not be your sole source of information.

---

**Note to Developer**: Before publishing:
1. Fill in [DATE] with the current date
2. Replace [YOUR EMAIL] with your support email address
3. Update the GitHub Issues link with your actual GitHub username
4. Consider hosting this on a public URL (GitHub Pages, personal website, etc.)
5. Link to this privacy policy from the Play Store listing and in the About page of the app
