# GRPH

A SPWN graphing library.

- **Exports**
  - Macros
    - [calc_y_step](docs/GRPH?id=calc_y_step)
- **@line_graph**
  - Constructors
    - [`@line_graph::`new](docs/line_graph?id=new)
  - Macros
    - [`@line_graph::`add](docs/line_graph?id=add)
    - [`@line_graph::`add_dict](docs/line_graph?id=add_dict)
    - [`@line_graph::`set_line_color](docs/line_graph?id=set_line_color)
    - [`@line_graph::`set_title](docs/line_graph?id=set_title)
    - [`@line_graph::`set_x_axis_label](docs/line_graph?id=set_x_axis_label)
    - [`@line_graph::`set_y_axis_label](docs/line_graph?id=set_y_axis_label)
    - [`@line_graph::`show](docs/line_graph?id=show)
- **@bar_chart**
  - Constructors
    - [`@bar_chart::`new](docs/bar_chart?id=new)
  - Macros
    - [`@bar_chart::`add](docs/bar_chart?id=add)
    - [`@bar_chart::`add_dict](docs/bar_chart?id=add_dict)
    - [`@bar_chart::`set_title](docs/bar_chart?id=set_title)
    - [`@bar_chart::`set_y_axis_label](docs/bar_chart?id=set_y_axis_label)
    - [`@bar_chart::`show](docs/bar_chart?id=show)
- **@scatter_graph**
  - Macros
    - [`@scatter_graph::`add](docs/scatter_graph?id=add)
    - [`@scatter_graph::`add_array](docs/scatter_graph?id=add_array)
    - [`@scatter_graph::`new](docs/scatter_graph?id=new)
    - [`@scatter_graph::`set_title](docs/scatter_graph?id=set_title)
    - [`@scatter_graph::`set_x_axis_label](docs/scatter_graph?id=set_x_axis_label)
    - [`@scatter_graph::`set_y_axis_label](docs/scatter_graph?id=set_y_axis_label)
    - [`@scatter_graph::`show](docs/scatter_graph?id=show)

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
