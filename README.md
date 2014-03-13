Sandbox
=======

New SLIP's Sandbox service for developers.

If you've stumbled upon this page without first reading out developer documentation please head [over there](https://github.com/Landgate/slip-developer-documentation/wiki) first.

## layers.json
Contains the list of layers in the Sandbox service, along with their layerIds, layerKeys, datasourceIds, URIs for their datasources, and some additional useful metadata.

```javascript
{
  layerId: /* A globally unique ID used to refer to this layer */
  layerKey: /* The layer key - For the GMaps JS Lib. Not unique. */
  name: /* The layer name */
  description: /* The layer description */
  bbox: /* An array of four numbers (west, south, east, north) which define 
    the rectangular bounding box covered by the layer as latitude and longitude in decimal degrees */
  datasourceType: /* The type of layer - one of "table" or "image" */
  datasources: /* The path to the GME API resource of the more specific version of this asset. 
    Used for querying features and only applies to datasourceType "image". */
}
```

For easier viewing of layers.json try the [JSONView](https://chrome.google.com/webstore/detail/jsonview/chklaanhfefbnpoihckbnefhakgolnmc?hl=en) Chrome extension or the free online [JSON Visualisation](http://chris.photobooks.com/json/default.htm) tool.

> **Coming Soon:** Our brand new search and discovery tool! We'll intergrate all of this information and more in a single easy to use web interface.

## Accessing The Sandbox
https://github.com/Landgate/slip-developer-documentation/wiki/Sandbox
