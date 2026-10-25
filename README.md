# Order Tracking — OpenWidget App

Order Tracking gives website visitors a quick way to open the store's public order-tracking page from the OpenWidget chat widget.

## How it works

1. The website owner installs the app in OpenWidget.
2. In the app settings, the owner enters their public order-tracking page URL, including `https://`.
3. Visitors click **Track My Order** in the widget.
4. OpenWidget opens the configured tracking URL using the action behavior supported by the platform.

The URL can point to a branded tracking page provided by a courier or ecommerce tracking service, such as Shiprocket or another provider.

## Files

- `app.json` — OpenWidget app configuration.
- `icon.svg` — App icon.

## Notes

- This app redirects visitors to the tracking page configured by the website owner. It does not retrieve order details or track shipments itself.
- No backend, database, or API credentials are included.
- The configured URL must be publicly accessible to the visitor. The website owner should verify that it is the correct tracking page.
- Confirm the intended new-tab behavior in OpenWidget during testing before submitting the app.

## Documentation

[OpenWidget Apps documentation](https://openwidget.com/developers/openwidget-apps)
