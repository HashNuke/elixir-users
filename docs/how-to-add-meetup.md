# How to add a meetup

* Copy paste the below code, as another element of the `features` key, in the `elixir-users.geojson` file

**Limits:** `name` is REQUIRED. `url` and `twitter` are optional. Incase your meetup group has a github organisation, then feel free to add that.

```
{
  "type": "Feature",
  "geometry": {
    "type": "Point",
    "coordinates": [77.5667, 12.9667]
  },
  "properties": {
    "name": "Some meetup",
    "url": "some-official-meetup-page.com",
    "twitter": "SomeMeetupOfficialTwitterHandle",
    "marker-color": "#E35D5C",
  }
}
```

* Edit details

  * `coordinates` are of the form `[longitude, latitude]`
  * `properties` key holds other data

* Then send a pull request.
