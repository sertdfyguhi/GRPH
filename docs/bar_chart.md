# **@bar_chart**

## Constructors

### new

> **Printed**
>
> ```spwn
> (values: @dictionary = {}, title: @string = '', y_axis_label: @string = '', axis_color_channel: @color = ?c, text_color_channel: @color = ?c, sorting_array: @array = []) { /* ... */ }
> ```
>
> **Type:** `@macro`
>
> **Description:**
>
> _Creates a bar chart._
>
> **Example:**
>
> ```spwn
> @bar_chart::new(
>  {
>    "a": 5,
>    "b": 7,
>    "c": 3,
>  },
>  title="Title",
>  y_axis_label="Y axis",
>  sorting_array=["a", "b", "c"]
> )
> ```
>
> **Arguments:**
>
> | #   | name                 | type          | default value | description                                                                    |
> | --- | -------------------- | ------------- | ------------- | ------------------------------------------------------------------------------ |
> | 1   | `values`             | `@dictionary` | `{}`          | Values as a dictionary.                                                        |
> | 2   | `title`              | `@string`     | `''`          | Title of the graph.                                                            |
> | 3   | `y_axis_label`       | `@string`     | `''`          | Y axis label.                                                                  |
> | 4   | `axis_color_channel` | `@color`      | `?c`          | Color channel of the axes.                                                     |
> | 5   | `text_color_channel` | `@color`      | `?c`          | Color channel of the text.                                                     |
> | 6   | `sorting_array`      | `@array`      | `[]`          | Array of labels to sort the values from. Dictionaries in SPWN are not ordered. |

## Macros

### add

> **Printed**
>
> ```spwn
> (self, label: @string, value: @number, color: @chroma = null) { /* ... */ }
> ```
>
> **Type:** `@macro`
>
> **Arguments:**
>
> | #   | name    | type      | default value | description                      |
> | --- | ------- | --------- | ------------- | -------------------------------- |
> | 1   | `label` | `@string` |               | Label of the value.              |
> | 2   | `value` | `@number` |               | Value.                           |
> | 3   | `color` | `@chroma` | `null`        | Color of the bar for this value. |

### add_dict

> **Printed**
>
> ```spwn
> (self, values: @dictionary) { /* ... */ }
> ```
>
> **Type:** `@macro`
>
> **Arguments:**
>
> | #   | name     | type          | default value | description             |
> | --- | -------- | ------------- | ------------- | ----------------------- |
> | 1   | `values` | `@dictionary` |               | Values as a dictionary. |

### set_title

> **Printed**
>
> ```spwn
> (self, label: @string) { /* ... */ }
> ```
>
> **Type:** `@macro`
>
> **Arguments:**
>
> | #   | name    | type      | default value | description |
> | --- | ------- | --------- | ------------- | ----------- |
> | 1   | `label` | `@string` |               |             |

### set_y_axis_label

> **Printed**
>
> ```spwn
> (self, label: @string) { /* ... */ }
> ```
>
> **Type:** `@macro`
>
> **Arguments:**
>
> | #   | name    | type      | default value | description |
> | --- | ------- | --------- | ------------- | ----------- |
> | 1   | `label` | `@string` |               |             |

### show

> **Printed**
>
> ```spwn
> (self, start_pos: @array = [0, 0], number_text: @bool = false, y_step: @number = 1, between_y_step: @number = 1, groups: @array = []) { /* ... */ }
> ```
>
> **Type:** `@macro`
>
> **Arguments:**
>
> | #   | name             | type      | default value | description                                                       |
> | --- | ---------------- | --------- | ------------- | ----------------------------------------------------------------- |
> | 1   | `start_pos`      | `@array`  | `[0, 0]`      | Start position of the graph measured from the bottom left corner. |
> | 2   | `number_text`    | `@bool`   | `false`       | Adds a text object showing the value of the bar.                  |
> | 3   | `y_step`         | `@number` | `1`           | Amount to step on the Y axis.                                     |
> | 4   | `between_y_step` | `@number` | `1`           | Amount of blocks between each step.                               |
> | 5   | `groups`         | `@array`  | `[]`          |                                                                   |
