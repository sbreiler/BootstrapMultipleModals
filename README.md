# bootstrap-multi-modals
Add the possibility to open more than one modal in bootstrap, fixes all glitchy problems when doing so.

Tested on Bootstrap Version 3.3.2, all recent versions should work.

Features:
 - detect all modals on loading time, or dynamic modals opened by $('#modalid').modal('show')
 - fix z-index, later modals are top most
 - fix margin (flicker) on body, when more than one bootstrap model is opened/closed
 - fix non-scrollable modal after closing another modal

If you have problems or additions let me know :-)

## How to use
Just add 
```javascript
<script src="bootstrap-multi-modals.js"></script>
```
**after** bootstrap.min.js or bootstrap.js
