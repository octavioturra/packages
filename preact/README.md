# cljsjs/preact

[](dependency)
```clojure
[cljsjs/preact "6.0.0-beta"] ;; latest release
```
[](/dependency)

This jar comes with `deps.cljs` as used by the [Foreign Libs][flibs] feature
of the Clojurescript compiler. After adding the above dependency to your project
you can require the packaged library like so:


```clojure
(ns your-ns
  (:require [cljsjs.preact]))

```


[flibs]: https://github.com/clojure/clojurescript/wiki/Packaging-Foreign-Dependencies
