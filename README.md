# colors-swatches

A component as a module to use @c8r clrs.cc color swatches

## Usage

- import swatches into your component

    ```html
    <link rel="import" href="../colors-swatches.html">
    ```

- the styles are exported as shared styles:

    ```html
    <style is="custom-style" include="colors-swatches">
    ...
    </style>
    ```

- the JavaScript swatches are available on global `window` object:

    ```js
    window.colors
    Object {aqua: "#7fdbff", blue: "#0074d9", lime: "#01ff70", navy: "#001f3f", teal: "#39cccc"…}
    ```

## Author

@peterblazejewicz
