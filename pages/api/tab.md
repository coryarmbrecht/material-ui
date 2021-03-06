---
filename: /src/Tabs/Tab.js
---

<!--- This documentation is automatically generated, do not try to edit it. -->

# Tab



## Props

| Name | Type | Default | Description |
|:-----|:-----|:--------|:------------|
| classes | Object |  | Useful to extend the style applied to components. |
| disabled | boolean | false | If `true`, the tab will be disabled. |
| icon | union:&nbsp;string&nbsp;&#124;<br>&nbsp;Element&lt;any><br> |  | The icon element. If a string is provided, it will be used as a font ligature. |
| label | union:&nbsp;string&nbsp;&#124;<br>&nbsp;Element&lt;any><br> |  | The label element. |
| value | any |  | You can provide your own value. Otherwise, we fallback to the child position index. |

Any other properties supplied will be [spread to the root element](/customization/api#spread).

## CSS API

You can override all the class names injected by Material-UI thanks to the `classes` property.
This property accepts the following keys:
- `root`
- `rootLabelIcon`
- `rootAccent`
- `rootAccentSelected`
- `rootAccentDisabled`
- `rootPrimary`
- `rootPrimarySelected`
- `rootPrimaryDisabled`
- `rootInherit`
- `rootInheritSelected`
- `rootInheritDisabled`
- `fullWidth`
- `wrapper`
- `labelContainer`
- `label`
- `labelWrapped`

Have a look at [overriding with classes](/customization/overrides#overriding-with-classes) section
and the [implementation of the component](https://github.com/callemall/material-ui/tree/v1-beta/src/Tabs/Tab.js)
for more detail.

If using the `overrides` key of the theme as documented
[here](/customization/themes#customizing-all-instances-of-a-component-type),
you need to use the following style sheet name: `MuiTab`.

## Inheritance

The properties of the [&lt;ButtonBase /&gt;](/api/button-base) component are also available.

## Demos

- [Tabs](/demos/tabs)

