**THIS LIBRARY IS IN THE VERY BEGINNING STAGES OF DEVELOPMENT!**

**DO NOT USE UNLESS YOU ARE LOOKING TO DO SOME HEAVY WORK ON IT FIRST!**


# Charco
D3-based chart components for Angular 6

As you can see, I haven't done much more than set up a skeleton for my library here for now.

Here's what I'd like to do with it:

### Line Chart
Initially, I'd like to focus on the venerable old line chart

- Series lines (duh)
- Event lines (vertical lines at specific x-values)
- Cursor lines (horizontal lines at specific y-values)
- Grid lines, etc.
- Statistical capabilities (selectable regions of data that display averages, medians, etc along with deeper statistical data)
- Zoomable and pannable data area
- Legend with the ability to enable/disable series
- Ability to accept data in a TS-sensible format
- Unit tests with 100% code coverage
- Every portion of the charts built with reusability in mind (axes, etc)

For now, the animations will take a back seat to basic functionality.

### Data Handling
Once I have a solid Line Chart component built, I want to focus on handling data.  Namely, I would like to be able to:

- Decimate data on-the-fly according to customizable criteria
- Convert data from nearly every possible data source format into the format required by the Line Chart
- Perform other transformations on data, from simple tasks, like normalization and offsets, to more complex tasks, like FFTs and Classification

Eventually, I see this portion becoming a separate library in its own right, but for now, I'm happy with it piggy-backing on Charco.

### More to come
Obviously, some of the above is wish-list thinking, but I do believe that at least 95% of what is up there will be accomplished.  After squaring the Data Handling module away, I'd like to expand into other types of charts and leverage the modular build-out to get into combination charts.  Once all of that is stable, I plan on looking at the animation side of things, only adding animations when it will remain performant and unobtrusive.
