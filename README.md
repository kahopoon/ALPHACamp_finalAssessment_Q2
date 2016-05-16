# ALPHACamp_finalAssessment_Q2
![Alt text](screenshot.png?raw=true "screenshot")

There are 2 controller in xcode, left is traditional auto-layout, and right is stackview. They are both suitable for different size devices on two orientation.

For traditional auto-layout, I set the left orange block height and the right green block referencing the orange one for height, and also center vertically to orange.
At this stage, we already confirmed the height of two block, also they share the same y-axis, so, just set orange align bottom of space 12, then Y is confirmed for both block views.
And now for X, orange block heading align space of 24 to superviewl, green block heading space 12 and trailing 24.
Completed. :)

For stackview, it is much more effective by dragging to view block and click a single click to embedded with stackview. Set the stackview heading and trailing space of 24 and bottom align space of 12, set th orange block height 80, stack view spacing 12 and fill equally. Completed! wohooo~
