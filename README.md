# Arcade Experiments

Arcade is an expression language that allows you to calculate values, customize popup content, and define conditional behavior in ArcGIS apps. The examples in this repo demonstrate how you can create expressions that execute in custom Arcade profiles. If you are unfamiliar with Arcade and its capabilities, first read: [I’m a developer. Do I really need Arcade?](https://www.esri.com/arcgis-blog/products/js-api-arcgis/developers/im-a-developer-do-i-really-need-arcade/).

[This article](https://www.esri.com/arcgis-blog/products/js-api-arcgis/developers/execute-arcade-expressions-on-your-terms/) describes how the ArcadeExecutor API works for executing Arcade expressions outside their original context.

## Examples

- [Time range](https://ekenes.github.io/arcade-experiments/custom-profiles/time-range.html) - Use `DateDiff` to easily calculate a range between two dates.
- [Summary statistics](https://ekenes.github.io/arcade-experiments/custom-profiles/summary-statistics.html) - Calculate and display summary statistics using Arcade functions that abstract differences in server versions and configurations.
- [Label line segments](https://ekenes.github.io/arcade-experiments/custom-profiles/label-segments.html) - Take advantage of geometry functions not available in the JS API when labeling line segments during editing.

## Resources

### Blogs

- [I’m a developer. Do I really need Arcade?](https://www.esri.com/arcgis-blog/products/js-api-arcgis/developers/im-a-developer-do-i-really-need-arcade/)
- [Execute Arcade expressions on your terms](https://www.esri.com/arcgis-blog/products/js-api-arcgis/developers/execute-arcade-expressions-on-your-terms/)

### API Reference

- [Arcade Executor](https://developers.arcgis.com/javascript/latest/api-reference/esri-arcade.html#createArcadeExecutor)
