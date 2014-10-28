This is an inventory of existing NXT API end points at the start of
the "Fase 2" project.

From lizard-nxt, under https://nxt.lizard.net/api/v1/ :

* ^layers/$ LayerViewSet
* ^layers/{pk}/$ LayerViewSet
* ^locations/$ LocationViewSet
* ^locations/{pk}/$ LocationViewSet
* ^objects/$ ObjectsView
* ^timeseries/$ TimeseriesViewSet
* ^timeseries/{pk}/$ TimeseriesViewSet
* ^events/$ EventViewSet
* ^events/{pk}/$ EventViewSet
* ^eventseries/$ EventSeriesViewSet
* ^eventseries/{pk}/$ EventSeriesViewSet
* ^search/$ SearchView
* ^geocode/$ GeocoderView
* ^reversegeocode/$ ReverseGeocoderView
* ^objects/(?P<z>[^/]+)/(?P<x>[^/]+)/(?P<y>[^/]+)/\.(?P<format>[a-z]+)$ ObjectsView
* ^rasters/$ RasterView
* ^tiles/(?P<slug>[^/]+)/(?P<z>[^/]+)/(?P<x>[^/]+)/(?P<y>[^/]+)/?\.(?P<format>[a-z]+)$ TilesView

As well as Django Admin, data import, and login/logout functionality defined
in lizard_auth_client, under / .
