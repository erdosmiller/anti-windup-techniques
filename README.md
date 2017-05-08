PID Integrator Anti-Windup Implementation Examples
==================================================

This repo contains a VI (anti-windup-techniques.vi) that allows the user to configure a PID and simulated system and view the behavior of anti-windup implementations.

The integral gain (Ki) is applied per-cycle, every 10ms.

Dependencies
------------

This project depends on [LV-PID](https://github.com/erdosmiller/lv-pid) and OpenG Toolkit, which can be download via VI Package manager.

Requires LabVIEW 2015 or later