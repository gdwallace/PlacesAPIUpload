# PlacesAPIUpload

Open `polygon-generator.html` in a browser to generate site polygons and upload places to the Trimble Places API.

## Import file

Required headers: `PlaceName`, `Lattitude`/`Latitude`, `Longitude`, `SetId`

Optional address headers (stored for API upload, not shown in the UI list):
`StreetAddress`/`Address`, `City`, `State`, `PostalCode`/`Zip`

The leading street number is split into `address.streetNumber` and the remainder into `address.streetAddress` for the Places API payload.
