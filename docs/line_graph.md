# **@line_graph**

## Constructors

### new

>**Printed**
>
>```spwn
>(values: @dictionary = {}, title: @string = '', x_axis_label: @string = '', y_axis_label: @string = '', line_color: @chroma = null, axis_color_channel: @color = ?c, text_color_channel: @color = ?c, sorting_array: @array = []) { /* ... */ }
>```
>
>**Type:** `@macro`
>
>**Description:**
>
>_Creates a line graph._
>
>**Example:**
>
>```spwn
>@line_graph::new(
>  {
>    "a": 5,
>    "b": 7,
>    "c": 3,
>  },
>  title="Title",
>  x_axis_label="X axis",
>  y_axis_label="Y axis",
>  line_color=hex("#FF99A5"),
>  sorting_array=["a", "b", "c"]
>)
>```
>
>
>**Arguments:**
>
>| # | name | type | default value | description |
>| - | ---- | ---- | ------------- | ----------- |
>| 1 | `values` | `@dictionary` | `{}` |Values as a dictionary. |
>| 2 | `title` | `@string` | `''` |Title of the graph. |
>| 3 | `x_axis_label` | `@string` | `''` |X axis label. |
>| 4 | `y_axis_label` | `@string` | `''` |Y axis label. |
>| 5 | `line_color` | `@chroma` | `null` |Color of lines as a chroma. |
>| 6 | `axis_color_channel` | `@color` | `?c` |Color channel of the axes. |
>| 7 | `text_color_channel` | `@color` | `?c` |Color channel of the text. |
>| 8 | `sorting_array` | `@array` | `[]` |Array of labels to sort the values from. Dictionaries in SPWN are not ordered. |
>

## Macros

### add

>**Printed**
>
>```spwn
>(self, label: @string, value: @number) { /* ... */ }
>```
>
>**Type:** `@macro`
>
>**Arguments:**
>
>| # | name | type | default value | description |
>| - | ---- | ---- | ------------- | ----------- |
>| 1 | `label` | `@string` | |Label of the value. |
>| 2 | `value` | `@number` | |Value. |
>

### add\_dict

>**Printed**
>
>```spwn
>(self, values: @dictionary) { /* ... */ }
>```
>
>**Type:** `@macro`
>
>**Arguments:**
>
>| # | name | type | default value | description |
>| - | ---- | ---- | ------------- | ----------- |
>| 1 | `values` | `@dictionary` | |Values as a dictionary. |
>

### set\_line\_color

>**Printed**
>
>```spwn
>(self, color: @chroma) { /* ... */ }
>```
>
>**Type:** `@macro`
>
>**Arguments:**
>
>| # | name | type | default value | description |
>| - | ---- | ---- | ------------- | ----------- |
>| 1 | `color` | `@chroma` | | |
>

### set\_title

>**Printed**
>
>```spwn
>(self, title: @string) { /* ... */ }
>```
>
>**Type:** `@macro`
>
>**Arguments:**
>
>| # | name | type | default value | description |
>| - | ---- | ---- | ------------- | ----------- |
>| 1 | `title` | `@string` | | |
>

### set\_x\_axis\_label

>**Printed**
>
>```spwn
>(self, x_axis_label: @string) { /* ... */ }
>```
>
>**Type:** `@macro`
>
>**Arguments:**
>
>| # | name | type | default value | description |
>| - | ---- | ---- | ------------- | ----------- |
>| 1 | `x_axis_label` | `@string` | | |
>

### set\_y\_axis\_label

>**Printed**
>
>```spwn
>(self, y_axis_label: @string) { /* ... */ }
>```
>
>**Type:** `@macro`
>
>**Arguments:**
>
>| # | name | type | default value | description |
>| - | ---- | ---- | ------------- | ----------- |
>| 1 | `y_axis_label` | `@string` | | |
>

### show

>**Printed**
>
>```spwn
>(self, start_pos: @array = [0, 0], y_step: @number = 1, between_y_step: @number = 1, groups: @array = []) { /* ... */ }
>```
>
>**Type:** `@macro`
>
>**Arguments:**
>
>| # | name | type | default value | description |
>| - | ---- | ---- | ------------- | ----------- |
>| 1 | `start_pos` | `@array` | `[0, 0]` |Start position of the graph measured from the bottom left corner. |
>| 2 | `y_step` | `@number` | `1` |Amount to step on the Y axis. |
>| 3 | `between_y_step` | `@number` | `1` |Amount of blocks between each step. |
>| 4 | `groups` | `@array` | `[]` | |
>
