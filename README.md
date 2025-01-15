

```
let _, a = Object.values,
    b = "getCurrentUser",
    c = "actionHandler",
    d = "_actionHandlers",
    l = "_dispatcher",
    i = "ExperimentStore";
webpackChunkdiscord_app.push([
    [Date.now()], {},
    e => {
        _ = e
    }
]), m = a((u = a(_.c).find(e => e?.exports?.default?.[b] && e?.exports?.default?.[l]?.[d]).exports.default)[l][d]._dependencyGraph.nodes), u[b]().flags |= 1, m.find(e => "Developer" + i == e.name)[c].CONNECTION_OPEN();
try {
    m.find(e => i == e.name)[c].OVERLAY_INITIALIZE({
        user: {
            flags: 1
        }
    })
} catch {}
m.find(e => i == e.name).storeDidChange()
```
