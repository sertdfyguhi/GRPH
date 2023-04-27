# GRPH

A SPWN graphing library.

- **Exports**
  - Macros
    - [calc_y_step](GRPH.md#calc_y_step)
- **@line_graph**
  - Constructors
    - [`@line_graph::`new](line_graph.md#new)
  - Macros
    - [`@line_graph::`add](line_graph.md#add)
    - [`@line_graph::`add_dict](line_graph.md#add_dict)
    - [`@line_graph::`set_line_color](line_graph.md#set_line_color)
    - [`@line_graph::`set_title](line_graph.md#set_title)
    - [`@line_graph::`set_x_axis_label](line_graph.md#set_x_axis_label)
    - [`@line_graph::`set_y_axis_label](line_graph.md#set_y_axis_label)
    - [`@line_graph::`show](line_graph.md#show)
- **@bar_chart**
  - Constructors
    - [`@bar_chart::`new](bar_chart.md#new)
  - Macros
    - [`@bar_chart::`add](bar_chart.md#add)
    - [`@bar_chart::`add_dict](bar_chart.md#add_dict)
    - [`@bar_chart::`set_title](bar_chart.md#set_title)
    - [`@bar_chart::`set_y_axis_label](bar_chart.md#set_y_axis_label)
    - [`@bar_chart::`show](bar_chart.md#show)
- **@scatter_graph**
  - Macros
    - [`@scatter_graph::`add](scatter_graph.md#add)
    - [`@scatter_graph::`add_array](scatter_graph.md#add_array)
    - [`@scatter_graph::`new](scatter_graph.md#new)
    - [`@scatter_graph::`set_title](scatter_graph.md#set_title)
    - [`@scatter_graph::`set_x_axis_label](scatter_graph.md#set_x_axis_label)
    - [`@scatter_graph::`set_y_axis_label](scatter_graph.md#set_y_axis_label)
    - [`@scatter_graph::`show](scatter_graph.md#show)

## Exports

**Printed**

```spwn
{calc_y_step: (values: @dictionary, max_height: @number = 100, between_y_step: @number = 1) { /* ... */ }}
```

**Type:** `@dictionary`

## Macros

### calc_y_step

> **Printed**
>
> ```spwn
> (values: @dictionary, max_height: @number = 100, between_y_step: @number = 1) { /* ... */ }
> ```
>
> **Type:** `@macro`
>
> **Description:**
>
> _Calculates the Y step of a graph based on the max height and the blocks between Y step._
>
> **Arguments:**
>
> | #   | name             | type          | default value | description                             |
> | --- | ---------------- | ------------- | ------------- | --------------------------------------- |
> | 1   | `values`         | `@dictionary` |               | Values of the graph as a dictionary.    |
> | 2   | `max_height`     | `@number`     | `100`         | Max height of the graph in blocks.      |
> | 3   | `between_y_step` | `@number`     | `1`           | The amount of blocks between each step. |
