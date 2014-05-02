# How to add a person

* Copy paste the below code, as another element of the `features` key, in the `elixir-users.geojson` file

**Limits:** `github` is a REQUIRED. `name`, `twitter` and `email` are optional.

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

  * `coordinates` are of the form `[longitude, latitude]`. You can find lat-long for your city by googling. For London, you can search "london lat long". Make sure that the order of the lat-long array is correct.
  * `properties` key holds other data

* Then send a pull request.
