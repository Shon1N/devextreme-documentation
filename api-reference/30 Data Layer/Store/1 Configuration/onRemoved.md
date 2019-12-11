---
EventForAction: ..\4 Events\removed.md
type: function(key)
---
---
##### shortDescription
A function that is executed after a data item is removed from the store.

##### param(key): Object|String|Number
The removed data item's key.

---
---
##### jQuery

    <!--JavaScript-->
    var store = new DevExpress.data.{WidgetName}({
        onRemoved: function (key) {
            // Your code goes here
        }
    });

##### Angular

    <!--TypeScript-->
    import {WidgetName} from "devextreme/data/{widget_name}";
    // ...
    export class AppComponent {
        store: {WidgetName};
        constructor() {
            this.store = new {WidgetName}({
                onRemoved: function (key) {
                    // Your code goes here
                }
            })
        }
    }
    
---