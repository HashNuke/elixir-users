# Elixir users

I noticed that people are trying to organize Elixir meetups. This project should help find meetup groups or provide head count to organize Elixir meetups in newer places.

Maybe you can also meet some Elixir users in person.


## How to add yourself as an individual?

#### If you are an individual

* Copy paste the code block in the next section, as another element of the `features` key, in the `elixir-users.geojson` file

* Edit your details

        * `coordinates` are of the form [longitude, latitude]
        * the `properties` key holds other data

* Then send a pull request.


## DOs & DONTs

* DONT delete or change the marker color.
* DONT add fields not permitted.
* DO file an issue if you have anything to discuss.


#### To add individuals

**Limits:** Allowed fields are `name`, `github`, `twitter` and `email`. Github handle is a REQUIRED. Rest are optional.

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

#### To add meetup groups

**Limits:** Allowed fields are `name`, `url`, `twitter` and `email`. `name` is REQUIRED. Others are optional. Incase your meetup group has a github organisation, then feel free to add that.

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


## Who... why... what?

I, [HashNuke](http://github.com/HashNuke) made this. File an issue to discuss anything.

> Sir, while you are still here, may I interest you in some snake oil serum?
