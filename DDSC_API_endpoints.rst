This is an inventory of existing DDSC API end points at the start of
the "Fase 2" project.

From dikedata_api, under http://api.ddsc.nl/api/v1/ :

* users/?$ UserList
* users/(?P<pk>[0-9]+)/? UserDetail
* groups/?$ UserGroupList
* groups/(?P<pk>[0-9]+)/?$ UserGroupDetail
* permissionmappers/?$ PermissionMapperList
* permissionmappers/(?P<pk>[0-9]+)/?$ PermissionMapperDetail
* roles/?$ RoleList
* roles/(?P<pk>[0-9]+)/?$ RoleDetail
* datasets/?$ DataSetList
* datasets/(?P<pk>[^/]+)/?$ DataSetDetail
* dataowner/?$ DataOwnerList
* dataowner/(?P<pk>[^/]+)/?$ DataOwnerDetail
* locations/?$ LocationList
* locations/search/?$ LocationSearch
* locations/(?P<uuid>[^/]+)/?$ LocationDetail
* timeseries/?$ TimeseriesList
* timeseries/search/?$ TimeseriesSearch
* timeseries/behind/?$ TimeseriesBehind
* timeseries/(?P<uuid>[^/]+)/?$ TimeseriesDetail
* events/?$ MultiEventList
* events/(?P<uuid>[^/]+)/?$ EventList
* events/(?P<uuid>[^/]+)/(?P<dt>[^/]+)/?$ EventDetail
* logicalgroups/?$ LogicalGroupList
* logicalgroups/(?P<pk>[^/]+)/?$ LogicalGroupDetail
* alarms/?$ AlarmActiveList
* alarms/(?P<pk>[^/]+)/?$ AlarmActiveDetail
* alarmsettings/?$ AlarmSettingList
* alarmsettings/(?P<pk>[^/]+)/?$ AlarmSettingDetail
* alarmitems/(?P<pk>[^/]+)/?$ AlarmItemDetail
* status/(?P<pk>[^/]+)/?$ StatusCacheDetail
* status/?$ StatusCacheList
* sources/?$ SourceList
* sources/(?P<uuid>[^/]+)/?$ SourceDetail
* manufacturer/?$ ManufacturerList
* parameters/?$ Parameter
* compartments/?$ Compartment
* measuringdevices/?$ MeasuringDevice
* measuringmethods/?$ MeasuringMethod
* processingmethods/?$ ProcessingMethod
* referenceframes/?$ ReferenceFrame
* units/?$ Unit
* summary/?$ Summary

From dddsc_site, also under http://api.ddsc.nl/api/v1/ :

* collages/?$ CollageList
* collages/(?P<pk>\d+)/?$ CollageDetail
* collages/create/?$ CollageCreate
* collageitems/?$ CollageItemList
* collageitems/(?P<pk>\d+)/?$ CollageItemDetail
* collageitems/create/?$ CollageItemCreate
* workspaces/?$ WorkspaceList
* workspaces/(?P<pk>\d+)/?$ WorkspaceDetail
* workspaceitems/?$ WorkspaceItemList
* workspaceitems/(?P<pk>\d+)/?$ WorkspaceItemDetail
* layers/?$ LayerList
* layers/(?P<pk>\d+)/?$ LayerDetail
* account/?$ CurrentAccount
* account/login-url/?$ LoginApiView
* account/logout-url/?$ LogoutApiView
* proxy/$ ProxyView
* proxy/(?P<urlbase>.+) ProxyView
* annotations/search/$ AnnotationsSearchView
* annotations/detail/(?P<pk>\d+)/?$ AnnotationsDetailView
* annotations/count/$ AnnotationsCountView
* annotations/create/$ AnnotationsCreateView
* annotations/files/$ AnnotationsFileView
* annotations/files/(?P<pk>\d+)/(?P<filename>.*)$ AnnotationsFileView
* version/$ VersionView

As well as login/logout functionality defined in lizard_auth_client,
under /api/ .
