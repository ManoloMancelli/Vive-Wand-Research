# Change Wand into Generic Tracker

Make the following edits (don’t include the - and + at the beginning. that’s just to highlight what you delete and what you add)

Indeed, there are only three lines you have to change. it should be easy to do by hand.

```
-    "device_class": "controller",
+    "device_class": "generic_tracker",
```

```
-    "model_number": "Vive. Controller MV",
+    "model_number": "Vive Tracker PVT",
```

```
     "revision": 1,
+    "tracked_controller_role": "",
     "trackref_from_head": [
         0,
         0.7253744006156921,
```
