# Inconsistent Blur Filter with 3D Transforms in CSS

This repository demonstrates a bug where the CSS `filter: blur()` property exhibits inconsistent behavior when used in conjunction with 3D transforms (`transform: translate3d()` for example).  The blur effect may not apply correctly, appear partially, or cause unexpected visual glitches across different browsers.

The `bug.css` file contains the problematic CSS code, while `bugSolution.css` provides a potential workaround.

This issue likely stems from how the browser handles hardware acceleration and the compositing of transformed and filtered elements.

## Potential Solutions

The solution might involve adjusting the order of CSS properties or experimenting with alternative techniques to achieve the desired blur effect without relying heavily on 3D transforms.

This is a known quirk with how some browsers handle filter effects in conjunction with transforms.