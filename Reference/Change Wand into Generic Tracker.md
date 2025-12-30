# Change Wand into Generic Tracker

Make the following edits (don’t include the - and + at the beginning. that’s just to highlight what you delete and what you add)

Indeed, there are only three lines you have to change. it should be easy to do by hand.

```
--- LHR-FFA12345orig.json       2019-09-03 20:58:58.389611800 -0700
+++ LHR-FFA12345.json   2019-09-03 21:48:01.618036900 -0700
@@ -9,7 +9,7 @@
         0.9991,
         0.9988
     ],
-    "device_class": "controller",
+    "device_class": "generic_tracker",
     "device_pid": 8210,
     "device_serial_number": "LHR-FFA12345",
     "device_vid": 10462,
@@ -298,9 +298,10 @@
     },
     "manufacturer": "HTC",
     "mb_serial_number": "42T1234567890",
-    "model_number": "Vive. Controller MV",
+    "model_number": "Vive Tracker PVT",
     "render_model": "vr_controller_vive_1_5",
     "revision": 1,
+    "tracked_controller_role": "",
     "trackref_from_head": [
         0,
         0.7253744006156921,
```
$${\color{red}Red}$$