# Alpine.js IntelliSense

Simple IntelliSense & Snippets for [Alpine.js](https://github.com/alpinejs/alpine) framework (v3.x).

## IntelliSense

IntelliSense for Alpine's directives including all v3 features.

![Screenshot - Directives](img/screenshot-directives.png)

## Snippets

![Screenshot - Snippet](img/screenshot-snippet.png)

### Directives

| Prefix | Body |
| ------ | ---- |
| x\-if | `<template x-if="${1:true}"> $0 </template>` |
| x\-for | `<template x-for="${1:item} in ${2:items}"> $0 </template>` |
| x\-for\-key | `<template x-for="${1:item} in ${2:items}" :key="${3:item}"> $0 </template>` |
| x\-for\-index | `<template x-for="(${1:item}, ${2:index}) in ${3:items}" :key="$2"> $0 </template>` |
| x\-bind:class | `x-bind:class="{ '${1:hidden}': ${2:foo} }"` |
| x\-bind | `x-bind:${1:attribute}="${2:expression}"` |
| x\-show | `x-show="$0"` |
| x\-effect | `x-effect="${1:console.log('Effect running')}"` |
| x\-ignore | `x-ignore` |
| x\-teleport | `<template x-teleport="${1:body}"> $0 </template>` |
| x\-id | `x-id="['${1:field-name}']"` |
| x\-modelable | `x-modelable="${1:propertyName}"` |

### Transitions

| Prefix | Body |
| ------ | ---- |
| x\-transition:enter | `x-transition:enter="$0"` |
| x\-transition:enter-start | `x-transition:enter-start="$0"` |
| x\-transition:enter-end | `x-transition:enter-end="$0"` |
| x\-transition:leave | `x-transition:leave="$0"` |
| x\-transition:leave-start | `x-transition:leave-start="$0"` |
| x\-transition:leave-end | `x-transition:leave-end="$0"` |

### Magic Properties

| Prefix | Body |
| ------ | ---- |
| $el | `$el` |
| $refs | `$refs.${1:name}` |
| $event | `$event` |
| $dispatch | `$dispatch('${1:custom-event}', ${2:{ foo: 'bar' }})` |
| $nextTick | `$nextTick(${1:() => { console.log($event.target.innerText) }});` |
| $watch | `$watch('${1:open}', ${2:value => console.log(value)})` |
| $store | `$store.${1:storeName}` |
| $root | `$root` |
| $data | `$data` |
| $id | `$id('${1:field-name}')` |

### Event Modifiers

| Prefix | Body |
| ------ | ---- |
| \.away | `.away` |
| \.prevent | `.prevent` |
| \.stop | `.stop` |
| \.self | `.self` |
| \.window | `.window` |
| \.document | `.document` |
| \.once | `.once` |
| \.debounce | `.debounce.${1:750}` |
| \.throttle | `.throttle.${1:750}` |
| \.camel | `.camel` |
| \.dot | `.dot` |
| \.passive | `.passive` |
| \.capture | `.capture` |
| \.transition | `.transition` |

### CDN

| Prefix | Body |
| ------ | ---- |
| alpine\-cdn | `<script defer src="https://cdn.jsdelivr.net/npm/alpinejs@3.x.x/dist/cdn.min.js"></script>` |