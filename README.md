# Responsive Challenges

> Course: https://courses.kevinpowell.co/view/courses/conquering-responsive-layouts/

## Rules

- 原本的HTML是完全具有响应的，随着CSS的添加，响应性越来越差
- 先设计手机版，保证所有内容都可以正常展示，再设计桌面端
- 尽量不要写死width和height

## em vs rem

- 设置字体大小用`rem`，不要用`em`，因为`em`会叠加父级的字体大小
- `em`可以用于设置`margin`和`padding`，因为此时`em`是当前元素的字体大小，而不是父级的
