# **@scatter_graph**

## Macros

### add

>**Printed**
>
>```spwn
>(self, pos: @array, color: @chroma = null) { /* ... */ }
>```
>
>**Type:** `@macro`
>
>**Arguments:**
>
>| # | name | type | default value | description |
>| - | ---- | ---- | ------------- | ----------- |
>| 1 | `pos` | `@array` | |Position (x, y) of the point. |
>| 2 | `color` | `@chroma` | `null` |Color of the point. |
>

### add\_array

>**Printed**
>
>```spwn
>(self, values: @array) { /* ... */ }
>```
>
>**Type:** `@macro`
>
>**Arguments:**
>
>| # | name | type | default value | description |
>| - | ---- | ---- | ------------- | ----------- |
>| 1 | `values` | `@array` | |Values as a array. |
>

### new

>**Printed**
>
>```spwn
>(values: @array = [], title: @string = '', x_axis_label: @string = '', y_axis_label: @string = '', axis_color_channel: @color = ?c, text_color_channel: @color = ?c) { /* ... */ }
>```
>
>**Type:** `@macro`
>
>**Arguments:**
>
>| # | name | type | default value | description |
>| - | ---- | ---- | ------------- | ----------- |
>| 1 | `values` | `@array` | `[]` |Values as a array. |
>| 2 | `title` | `@string` | `''` |Title of the graph. |
>| 3 | `x_axis_label` | `@string` | `''` |X axis label. |
>| 4 | `y_axis_label` | `@string` | `''` |Y axis label. |
>| 5 | `axis_color_channel` | `@color` | `?c` |Color channel of the axes. |
>| 6 | `text_color_channel` | `@color` | `?c` |Color channel of the text. |
>

### set\_title

>**Printed**
>
>```spwn
>(self, label: @string) { /* ... */ }
>```
>
>**Type:** `@macro`
>
>**Arguments:**
>
>| # | name | type | default value | description |
>| - | ---- | ---- | ------------- | ----------- |
>| 1 | `label` | `@string` | | |
>

### set\_x\_axis\_label

>**Printed**
>
>```spwn
>(self, label: @string) { /* ... */ }
>```
>
>**Type:** `@macro`
>
>**Arguments:**
>
>| # | name | type | default value | description |
>| - | ---- | ---- | ------------- | ----------- |
>| 1 | `label` | `@string` | | |
>

### set\_y\_axis\_label

>**Printed**
>
>```spwn
>(self, label: @string) { /* ... */ }
>```
>
>**Type:** `@macro`
>
>**Arguments:**
>
>| # | name | type | default value | description |
>| - | ---- | ---- | ------------- | ----------- |
>| 1 | `label` | `@string` | | |
>

### show

>**Printed**
>
>```spwn
>(self, start_pos: @array = [0, 0], x_step: @number = 1, y_step: @number = 1, between_x_step: @number = 1, between_y_step: @number = 1, groups: @array = []) { /* ... */ }
>```
>
>**Type:** `@macro`
>
>**Arguments:**
>
>| # | name | type | default value | description |
>| - | ---- | ---- | ------------- | ----------- |
>| 1 | `start_pos` | `@array` | `[0, 0]` |Start position of the graph measured from the bottom left corner. |
>| 2 | `x_step` | `@number` | `1` |Amount to step on the X axis. |
>| 3 | `y_step` | `@number` | `1` |Amount to step on the Y axis. |
>| 4 | `between_x_step` | `@number` | `1` |Amount of blocks between each step on the X axis. |
>| 5 | `between_y_step` | `@number` | `1` |Amount of blocks between each step on the Y axis. |
>| 6 | `groups` | `@array` | `[]` | |
>
