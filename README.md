# Svelte-Materialdesign-Icons

[![npm version](https://badgen.net/npm/v/svelte-materialdesign-icons)](https://www.npmjs.com/package/svelte-materialdesign-icons)
[![license](https://badgen.net/npm/license/svelte-materialdesign-icons)](https://github.com/shinokada/svelte-materialdesign-icons/blob/main/LICENSE)

Material Design SVG icon components for Svelte. Svelte-Materialdesign-Icons support major CSS frameworks using the `class` props.

## Icon name list

[Icon list](https://github.com/shinokada/svelte-materialdesign-icons/blob/main/icon-list.md)

## Installation

```sh
npm i -D svelte-materialdesign-icons
```

## Usages

In a svelte file:

```html
<script>
    import {
    Adjust,
    ArrowUpBoldOutline,
    Bucket,
    Card,
    ChatPlus,
    DataMatrix
  } from "svelte-awesome-icons";
</script>

<ToiletsPortableSolid />
<StarHalfRegular />
<AppleBrand />
```

## Size

Use the `size` prop to change the size of icons.

```html
<ToiletsPortableSolid size="40" />
<StarHalfRegular size="50" />
<AppleBrand size="60" />
```

## CSS HEX Colors

Use the `color` prop to change colors with HEX color code.

```html
<ToiletsPortableSolid color="#c61515" />
<StarHalfRegular color="#3759e5" />
<AppleBrand color="#3fe537" />
```

## CSS framworks suport

Use the `class` prop to change size, colors and add additional css.

Tailwind CSS example:

```html
<ToiletsPortableSolid class="h-24 w-24 text-blue-700 mr-4" />
<StarHalfRegular class="h-24 w-24 text-red-700" />
<AppleBrand class="h-24 w-24 text-green-500" />
```

Bootstrap examples:

```html
<ToiletsPortableSolid class="position-absolute top-0 px-1" />
```

## Dark mode

If you are using the dark mode on your website with Tailwind CSS, add your dark mode class to the `class` prop.

Let's use `dark` for the dark mode class as an example.

```html
<ToiletsPortableSolid class="text-blue-700 dark:text-red-500" />
<StarHalfRegular class="text-red-700 dark:text-green-500" />
<AppleBrand class="text-green-500 dark:text-blue-500" />
```

## Import all

[REPL](https://svelte.dev/repl/c0045886b264408fba13f1de70c42932?version=3.48.0)

Use `import * as Icon from 'svelte-awesome-icons`.

```html
<script>
	import * as Icon from 'svelte-awesome-icons'
</script>

<Icon.AppStoreBrand />
<Icon.ArrowRightToBracketSolid />

<h1>Size</h1>
<Icon.AppStoreBrand size="30"/>
<Icon.ArrowRightToBracketSolid size="40"/>

<h1>CSS HEX color</h1>
<Icon.ArrowRightToBracketSolid color="#c61515" size="40"/>

<h1>Tailwind CSS</h1>
<Icon.AppStoreBrand class="text-blue-500" />
<Icon.ArrowRightToBracketSolid class="text-pink-700" />
```

## Other icons

- [Svelte-Icon-Sets](https://svelte-svg-icons.vercel.app/)
- [Svelte-Ionicons](https://www.npmjs.com/package/svelte-ionicons)
- [Svelte-Awesome-Icons](https://www.npmjs.com/package/svelte-awesome-icons)
- [Svelte-heros](https://github.com/shinokada/svelte-heros)
- [Svelte-lucide](https://github.com/shinokada/svelte-lucide)
- [Svelte-flags](https://www.npmjs.com/package/svelte-flags)
- [Svlete-simples](https://github.com/shinokada/svelte-simples)
- [Svelte-feathers](https://github.com/shinokada/svelte-feathers)