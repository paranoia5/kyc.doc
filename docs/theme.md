# Theme (Dark / Light Mode)

You can change the theme prop dynamically and all the components will automatically update to reflect the new theme. If you haven't provided a theme prop, the default theme will be used.

A theme is a JS object containing a list of colors to use. It contains the following properties:

- dark (boolean): Whether this is a dark theme or a light theme
- colors (object): Various colors used by react navigation components:

  - primary (string): The primary color of the app used to tint various elements. Usually you'll want to use your brand color for this.
  - background (string): The color of various backgrounds, such as background color for the screens.
  - card (string): The background color of card-like elements, such as headers, tab bars etc.
  - text (string): The text color of various elements.
  - border (string): The color of borders, e.g. header border, tab bar border etc.
  - onPrimary (string): color on any component with primary color
  - placeholder (string): placeholder color for textinput
  - color (string): The text color of various elements.

- Fonts (object): custom fonts OS specific (android, iOS)

to edit the colors go to `src/theme/colors.ts`:

```
export const dark: Theme = {
...DarkTheme,
colors: {
  ...DarkTheme.colors,
  primary: "#f29e2e",
  onPrimary: "#ffffff",
  surface: "#000000",
  placeholder: "#FFFFFF54",
  color: "#ffffff",
},
fonts: configureFonts(),
};
// light theme props
export const light: Theme = {
...DefaultTheme,
colors: {
  ...DefaultTheme.colors,
  primary: "#f29e2e",
  onPrimary: "#000000",
  background: "#f6f6f6",
  surface: "#ffffff",
  placeholder: "#00000054",
  color: "#000000",
},
fonts: configureFonts(),
};
```
