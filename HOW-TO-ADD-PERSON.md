# To add a person

* Copy paste the below code, as another element of the `features` key, in the `elixir-users.geojson` file

**Limits:** Allowed fields are `name`, `github`, `twitter` and `email`. Github handle is a REQUIRED. Others are optional.

```
{
  "type": "Feature",
  "geometry": {
    "type": "Point",
    "coordinates": [77.5667, 12.9667]
  },
  "properties": {
    "name": "Akash Manohar",
    "github": "HashNuke",
    "twitter": "HashNuke",
    "email": "akash@akash.im",
    "marker-color": "#6692D4",
  }
}
```

* Edit details

  * `coordinates` are of the form `[longitude, latitude]`
  * `properties` key holds other data

* Then send a pull request.
