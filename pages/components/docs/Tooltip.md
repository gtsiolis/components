# Tooltip

The Tooltip component adds a tooltip to add context to elements on the page. The Toolip has a black background by default.

## Default example

```.jsx
<BorderBox p={3}>
  <Tooltip text="Hello, Tooltip!">Text with a tooltip</Tooltip>
</BorderBox>
```

## System props

Tooltip components get `COMMON` system props. Read our [System Props](/components/docs/system-props) doc page for a full list of available props.

## Component props

| Name | Type | Default | Description |
| :- | :- | :-: | :- |
| align | String | | Can be either `left` or `right`.|
| direction | String | | Can be one of `n`, `ne`, `e`, `se`, `s`, `sw`, `w`, `nw` | Sets where the tooltip renders in relation to the target. |
| noDelay | Boolean | | When set to `true`, tooltip appears without any delay |
| text | String | | Text used in `aria-label` (for accessibility).
| wrap | Boolean | | Use `true` to allow text within tooltip to wrap.


export const meta = {displayName: 'Tooltip'}
