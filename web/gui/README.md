# Netdata Agent Web GUI

## Generating dashboard.js

The monolithic `dashboards.js` file is automatically generated by concatenating the source files located in the `web/gui/src/dashboard.js/` directory by running the build script:

```sh
cd web/gui
make
```

After every change in the `src` directory, the `dashboard.js` file should be regenerated and commited to the repository.

## Custom Dashboards

For information on creating custom dashboards, see **[Custom Dashboards](custom/)** and **[Atlassian Confluence Dashboards](confluence/)**

## Supported chart libraries

- Dygraph
- jQuery Sparkline
- Peity
- Google Charts
- Morris
- EasyPieChart
- Gauge.js
- D3
- C3