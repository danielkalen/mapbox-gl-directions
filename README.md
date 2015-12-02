GL directions
---

A full featured directions plugin for [mapbox-gl-js](https://github.com/mapbox/mapbox-gl-js) using the [Mapbox Directions API](https://www.mapbox.com/developers/api/directions/).

## Usage

### Quick start

```html
<link href='https://api.tiles.mapbox.com/mapbox-gl-js/v0.11.2/mapbox-gl.css' rel='stylesheet' />
<link href='dist/mapboxgl.directions.css' rel='stylesheet' />

<script src='https://api.tiles.mapbox.com/mapbox-gl-js/v0.11.2/mapbox-gl.js'></script>
<script src='dist/mapboxgl.directions.js'></script>

<script>
mapboxgl.accessToken = '<YOUR_ACCESS_TOKEN>';

var map = new mapboxgl.Map({
  container: 'map',
  style: 'mapbox://styles/mapbox/streets-v8',
  center: [-79.45, 43.65]
});

var directions = Directions(document.getElementById('directions'));
map.addControl(directions);
</script>
```

## Documentation

- See [API.md](https://github.com/mapbox/gl-directions/blob/master/API.md).

## Contributing

- See [CONTRIBUTING.md](https://github.com/mapbox/gl-directions/blob/master/CONTRIBUTING.md).
