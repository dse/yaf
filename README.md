# Yet Another Framework

yaf is basically selected components of Foundation Sites 6.6.3, split
up, simplified, and not requiring sass.

## Simplifications

-   Vendor prefixes are removed.  You don't need them for most modern browsers, nor even IE11.
-   Built-in CSS transitions are removed.
-   Some unnecessary and/or duplicate CSS rules are removed.
-   You get a plain theme.  Foundation's default styles are split off into sample styles.
-   Your choice of XY Grid and Float Grid are in separate CSS files.
    -   Gutter is always `1rem`.

## Components

-   You need `normalize-8.0.1.css`.
-   You need `yaf-global-styles.css`.
-   You need `yaf-typography.css`.
-   You might want `yaf-forms.css`.
-   You might want `yaf-helpers.css`.
-   More to come.  You probably won't see anything requiring JavaScript.

You probably want a grid system.  Your choices are:

-   `yaf-float-grid.css`.

    These would then be your optional components:
    -   `yaf-float-block-grid.css` (`small-up-<x>`, etc.)

-   `yaf-xy-grid.css`.

    Does not include all of the XY Grid.  Just `grid-padding-x`.

    These would then be your optional components:
    -   `yaf-xy-block-grid.css` (`small-up-<x>`, etc.)
    -   `yaf-xy-grid-margin-x.css`
    -   `yaf-xy-grid-y.css` --- Only includes `grid-padding-y`.
    -   `yaf-xy-grid-margin-y.css`
    -   `yaf-xy-grid-frame.css`
    -   `yaf-xy-grid-frame-y.css`
