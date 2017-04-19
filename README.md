# Microtip.css

A modern, ultra lightweight css tooptip library

## Installation

- **via npm**
	Install the package using npm:-
```
npm install microtip
```

- **via yarn**
	Install the package via yarn:-
```
yarn add microtip
```

- **via CDN**
	Directly include the link to the css into your project:-
```
https://unpkg.com/microtip/microtip.css
```

- **direct download**
	Download the file directly from github

## Usage

Using the tooltip is incredibly simple. Simply add a custom `data-microtip` attribute to the element on which you want the tooltip to appear. The tooltip message is the attribute value. Example:-
```html
<button data-microtip="Hey tooltip!" >
```

#### Position Modifiers

You can change the direction of the tooltip by adding a `data-microtip-position` attribute. The accepted values of this attribute are:- `top`, `top-left`, `top-right`, `bottom`, `bottom-left`, `bottom-right`, `left` and `right`. Example:-
```html
<button data-microtip="Hey tooltip!" data-microtip-position="top-left">
```

### Size Modifiers

By default, the tooltip will takeup only the size it requires to show the text. You can specify sizes by adding a `data-microtip-size` attribute. The accepted values include `small`, `medium`, `large` and `fit`. Example:-
```html
<button data-microtip="This is a decently long text!" data-microtip-position="top-left" data-microtip-size="medium">
```

**Note** - `fit` sets the width of the tooltip to be the same as the width on the element. It only works along with the `top` and `bottom` position modifiers.




&nbsp;


<p align="center">✌️</p>
<p align="center">
<sub><sup>A little project by <a href="https://twitter.com/_ighosh">@i_ghosh</a></sup></sub>
</p>