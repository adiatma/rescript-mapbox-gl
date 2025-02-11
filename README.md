# rescript-mapbox-gl
> 🚧 binding for [mapbox-gl-js](https://github.com/mapbox/mapbox-gl-js)

## Table of Content

<!-- vim-markdown-toc GFM -->

* [Installation](#installation)
* [TODO](#todo)
* [Example](#example)
* [API](#api)
* [Contribution](#contribution)
* [License](#license)

<!-- vim-markdown-toc -->
## Installation
Run the following in your favorit console: 
```console
> yarn add rescript-mapbox-gl
```
## TODO
> 🏗 WIP, 🚧 Isn't implemented
   
- [ ] [**Map**](https://docs.mapbox.com/mapbox-gl-js/api/map/) (🏗)
- [ ] [**Properties and Options**](https://docs.mapbox.com/mapbox-gl-js/api/properties/) (🏗)
- [ ] [**Markers and Control**](https://docs.mapbox.com/mapbox-gl-js/api/markers/) (🚧)
- [ ] [**Geography and Geometry**](https://docs.mapbox.com/mapbox-gl-js/api/geography/) (🚧)
- [ ] [**User interaction handlers**](https://docs.mapbox.com/mapbox-gl-js/api/handlers/) (🚧)
- [ ] [**Sources**](https://docs.mapbox.com/mapbox-gl-js/api/sources/) (🚧)
- [ ] [**Events**](https://docs.mapbox.com/mapbox-gl-js/api/events/) (🚧)

## Example
```rescript
open Mapbox
// create Map
let map = Map.make() // new Map.map()
// create Map with Options
let mapWithOpt = Map.makeOptions(~container=Map.id("app-hash-in-dom"), ())->Map.makeWithOption
```

## API
The API closely match with [mapbox-gl-js](https://github.com/mapbox/mapbox-gl-js). You can refer to the [mapbox-gl-js documentation](https://docs.mapbox.com/mapbox-gl-js)
## Contribution
Feel Free
## License
MIT
