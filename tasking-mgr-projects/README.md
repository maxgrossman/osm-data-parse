### tasking-mgr-projects

Simple node.js script that grabs basic details on all Missing Maps projects from the [HOT tasking manager](tasks.hotosm.org) (filters based on the project name) and saves out a CSV.

Also saves out a GeoJSON of all task features that are marked completed or validated.

Currently setup for our specific use-case. But would be easy to configure.

- download or clone the project
- run `npm install` in the folder
- update the line `var targetCount = 2500;` to a number greater than the most recent project
- run `node parse.js`
