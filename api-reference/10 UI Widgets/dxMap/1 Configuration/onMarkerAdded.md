---
EventForAction: ..\4 Events\markerAdded.md
default: null
type: function(e)
---
---
##### shortDescription
A function that is executed when a marker is created on the map.

##### param(e): Object
Information about the event.

##### field(e.component): {WidgetName}
The widget's instance.

##### field(e.element): dxElement
The widget's container. It is an [HTML Element](https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement) or a [jQuery Element](https://api.jquery.com/Types/#jQuery) when you use jQuery.

##### field(e.model): Object
The model data. Available only if Knockout is used.

##### field(e.options): Object
The added marker's data.

##### field(e.originalMarker): Object
The original marker that the current map provider uses (only for "google" and "bing" providers).

---
#####See Also#####
- [Add and Remove a Marker](/concepts/05%20Widgets/Map/20%20Configure%20Markers/05%20Add%20and%20Remove.md '/Documentation/Guide/Widgets/Map/Configure_Markers/Add_and_Remove/')