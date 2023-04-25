# GRPH: A compile-time graphing library in SPWN.

A compile-time graphing library in SPWN.  
Currently only implements bar charts and line graphs.

## Installation

1. Clone this repository or download the repository zip

```sh
git clone https://github.com/sertdfyguhi/GRPH.git
```

2. Move the `libraries` folder into your SPWN file directory

## Example

```ts
import GRPH

let chart = @bar_chart::new(
  {
    "Stereo Madness": {
      value: 1,
      color: hex("#2451FF")
    },
    "Bloodlust": {
      value: 8,
      color: hex("#F0001F")
    }
  },
  title="The Difficulty of\nDifferent Geometry Dash Levels",
  y_axis_label="Difficulty"
)
chart.add("Back on Track", 2, color=hex("#FF8329"))
chart.show(start_pos=[10, 1])
```

### Resulting Bar Chart:

![The resulting graph in GD](https://raw.githubusercontent.com/sertdfyguhi/GRPH/master/example.png)

## Todo

- [ ] Add documentation
- [x] Add line graph
- [x] Add scatter graph
- [ ] Add pie chart
- [ ] Fix bug where block is out of graph when value is lower than 1
- [ ] Add functionality to have the value shown on graph
