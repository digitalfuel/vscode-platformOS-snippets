# platformOS Snippets for VS Code
This extension for Visual Studio Code adds snippets for Liquid, YAML, grahpQL, marketplace-kit terminal.

Visual Studio Marketplace link: [https://marketplace.visualstudio.com/items?itemName=digitalfuel.vscode-platformOS-snippets](https://marketplace.visualstudio.com/items?itemName=digitalfuel.vscode-platformOS-snippets)

## Preview
![Showcase](./images/showcase.gif)

## Prerequisite
1. Install the latest Visual Studio Code

## Dependencies
1. [Liquid Languages Support](https://marketplace.visualstudio.com/items?itemName=neilding.language-liquid)

## Installation
1. Launch Code
2. From the command palette `Ctrl`-`Shift`-`P` (Windows, Linux) or `Cmd`-`Shift`-`P` (OSX)
3. Type `ext install vscode-platformOS-snippets`
4. Reload Visual Studio Code

## Emmet Enable
Go to user settings and add the following:
```
"emmet.includeLanguages": { "liquid": "html" },
```

## Usage
Type part of a snippet, press `enter`, and the snippet unfolds.

Alternatively, press `Ctrl`+`Space` (Windows, Linux) or `Cmd`+`Space` (OSX) to activate snippets from within the editor.

# Liquid
Whitespace control is add for all snippets. And can be removed when needed by deleting the - inside liquid tags.

### Comment Tag
```javascript
comment- // whitespace stripped
```

### Control Flow Tag
```javascript
if
else
elsif
ifelse
unless
case
when
```

### Iteration Tag
```javascript
cycle
cyclegroup
for
limit       // For loops option
offset      // For loops option
reversed    // For loops option
break
continue
tablerow
```

### Variable Tag
```javascript
assign
increment
decrement
capture
```

### Theme Tag
```javascript
include
includewith    // Theme Tag {% include %} with parameters
section
raw
layout
layoutnone
paginate
```

### Array Filter
```javascript
join
first
last
concat
map
reverse
size
sort
uniq
```

### Math Filter
```javascript
abs
ceil
divided_by
floor
minus
plus
round
times
modulo
```

### Money Filter
```javascript
money
money_with_currency
money_without_trailing_zeros
money_without_currency
```

### String Filter
```javascript
append
camelcase
captialize
downcase
escape
handleize
md5
newline_to_br
pluralize
prepend
remove
remove_first
replace
replace_first
slice
slice_single   // String Filter 'slice' with single parameter
split
strip
lstrip
rstrip
strip_html
strip_newlines
truncate
truncatewords
upcase
url_encode
url_escape
url_param_escape
```

## Release

###0.0.1
- platform-OS snippets 

## License
MIT
