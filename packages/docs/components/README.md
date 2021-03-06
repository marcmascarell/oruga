
# Components

Take a look at left sidebar to find out all components !!!

## Config

Oruga allows to customize each components using config constructor or programmatically using `this.$oruga.config`.

```js
{
    globalfield: string|boolean|number|function|....,
    componentname: {
        override: boolean,
        customfieldX: string|boolean|number|function|....
    }
}

```

For example:

```js
{
    button: {
        override: true,
        rootClass: 'btn',
        roundedClass: 'btn-rounded',
        ...
    }
}

```

### Global

| Field                             | Description                                                   | Default                       |
| --------------------------------- | ------------------------------------------------------------- | ----------------------------- |
| statusIcon                        | Show status icon using field and variant prop                 | true                          |
| useHtml5Validation                | Default form components use-html5-validation attribute        | true                          |
| iconPack                          | Icon pack used internally and on the Icon component attribute | 'mdi'                         |

Take a look at each component docs to know all customizable fields/props by config.

## Base Style

| SASS Variable                     | Default                       |
| --------------------------------- | ----------------------------- |
| \$base-border-radius              | 4px                           |
| \$base-font-size                  | 1rem                          |
| \$base-rounded-border-radius      | 9999px                        |
| \$base-line-height                | 1.5                           |
| \$base-disabled-opacity           | 0.5                           |
| \$speed                           | 300ms                         |
| \$speed-slow                      | 150ms                         |
| \$speed-slower                    | 250ms                         |
| \$easing                          | ease-out                      |
| \$control-border-width            | 1px                           |
| \$control-height                  | 2.25em                        |
| \$white                           | #ffffff                       |
| \$black                           | #000000                       |
| \$grey                            | #7a7a7a                       |
| \$grey-light                      | #b5b5b5                       |
| \$grey-lighter                    | #dbdbdb                       |
| \$primary                         | #94C11F                       |
| \$primary-invert                  | $white                        |
| \$danger                          | #ff3860                       |
| \$danger-invert                   | $white                        |
| \$warning                         | #ffdd57                       |
| \$warning-invert                  | $white                        |
| \$success                         | #23d160                       |
| \$success-invert                  | $white                        |
| \$info                            | #info                         |
| \$info-invert                     | $white                        |
| \$whitelist                       | ()                            |
| \$sass-vars:                      | true                          |
| \$css-vars:                       | true                          |
| \$variable-prefix:                | '--oruga-'                    |
| \$sizes:                          | (<br>"small": .75rem,<br>"medium": 1.25rem,<br>"large": 1.5rem<br>) |
| \$colors:                         | (<br>"primary": ($primary, $primary-invert),<br>"danger": ($danger, $danger-invert),<br>"warning": ($warning, $warning-invert),<br>"success": ($success, $success-invert),<br>"info": ($info, $info-invert)<br>) |
