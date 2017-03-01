See http://bl.ocks.org/ganeshv/6a8e9ada3ab7f2d88022 for the template.

My main edits:

- remove `window.addEventListener('message', …)` block since I'm not using postMessage to load data
- change the final `if` block to a simple `d3.json("data.json", …)` call
- create & manually edit a "data.json" file with the appropriate tree data structure

All other changes from the treemap template were minor cosmetic tweaks that could be done without.
