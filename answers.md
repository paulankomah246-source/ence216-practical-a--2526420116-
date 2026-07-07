# ENCE 216 Practical A - Lab Answers

### Checkpoint 1: Hot-Reload Behavior
During a hot-reload, only build() prints again because initState() is only called once when the state object is permanently inserted into the widget tree, whereas a hot-reload explicitly forces a rebuild of the UI to reflect code changes.

### Section 4: Experiment Report
Calling setState() flags the element as "dirty" and schedules a frame rebuild, forcing Flutter to redraw the user interface with whatever current values exist in the state data, regardless of where that data was modified.8
hkksbAdd answers.md
