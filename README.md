# City of Mist phpBB theme for PBP LARP

## Useful BBCode snippets

[General documentation on how to install BBCode](https://www.phpbb.com/support/docs/en/3.3/kb/article/adding-custom-bbcodes-in-phpbb3/)
[Advanced syntax to help make your own](https://s9etextformatter.readthedocs.io/Plugins/BBCodes/Custom_BBCode_syntax/)

These snippets will require the CSS contained in the theme to look good.

### Yellow note

```
[postit title={TEXT1?} size={CHOICE=small,normal,large;defaultValue=normal}]{TEXT2}[/postit]
```

```
<div class="bbcode-postit bbcode-postit-size-{CHOICE}">
	<div class="bbcode-postit-title">{TEXT1}</div>
	{TEXT2}
</div>
```

### Paper board

```
[board]{TEXT}[/board]
```

```
<div class="bbcode-board">
{TEXT}
</div>
```

### Choice

```
[choice title={TEXT1?}]{TEXT2}[/choice]
```

```
<div class="bbcode-choice">
	<div class="bbcode-choice-title">{TEXT1}</div>
	<div class="bbcode-choice-inner">{TEXT2}</div>
</div>
```

### Choice option

```
[option title={TEXT1}]{TEXT2}[/option]
```

```
<div class="bbcode-option">
	<div class="bbcode-option-title">{TEXT1}</div>
	{TEXT2}
</div>
```

### Block

For when you just need a transparent `<div>` for positioning purpose.

```
[block title={TEXT1?}]{TEXT2}[/block]
```

```
<div class="bbcode-block">
<div class="bbcode-block-title">{TEXT1}</div>
{TEXT2}
</div>
```

### hr

```
[hr][/hr]
```

```
<hr class="bbcode-hr" />
```

### Logos sheet

```
[logos title={TEXT1}]{TEXT2}[/logos]
```

```
<div class="bbcode-logos">
	<div class="bbcode-logos-header" />
	<div class="bbcode-logos-title">{TEXT1}</div>
	<div class="bbcode-logos-inner">{TEXT2}</div>
</div>
```

### Mythos sheet

```
[mythos title={TEXT1}]{TEXT2}[/mythos]
```

```
<div class="bbcode-mythos">
	<div class="bbcode-mythos-header" />
	<div class="bbcode-mythos-title">{TEXT1}</div>
	<div class="bbcode-mythos-inner">{TEXT2}</div>
</div>
```

### Tag

```
[tag]{TEXT}[/tag]
```

```
<span class="bbcode-tag">{TEXT}</span>
```

### Status

```
[status]{TEXT}[/status]
```

```
<span class="bbcode-status">{TEXT}</span>
```

### Roll

```
[roll url={URL;useContent}]{TEXT}[/roll]
```

Icon taken from [Font Awesome](https://fontawesome.com/icons/dice):
```
<a class="bbcode-roll" href={URL}><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 640 512"><!--! Font Awesome Pro 6.4.0 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. --><path d="M274.9 34.3c-28.1-28.1-73.7-28.1-101.8 0L34.3 173.1c-28.1 28.1-28.1 73.7 0 101.8L173.1 413.7c28.1 28.1 73.7 28.1 101.8 0L413.7 274.9c28.1-28.1 28.1-73.7 0-101.8L274.9 34.3zM200 224a24 24 0 1 1 48 0 24 24 0 1 1 -48 0zM96 200a24 24 0 1 1 0 48 24 24 0 1 1 0-48zM224 376a24 24 0 1 1 0-48 24 24 0 1 1 0 48zM352 200a24 24 0 1 1 0 48 24 24 0 1 1 0-48zM224 120a24 24 0 1 1 0-48 24 24 0 1 1 0 48zm96 328c0 35.3 28.7 64 64 64H576c35.3 0 64-28.7 64-64V256c0-35.3-28.7-64-64-64H461.7c11.6 36 3.1 77-25.4 105.5L320 413.8V448zM480 328a24 24 0 1 1 0 48 24 24 0 1 1 0-48z"/></svg></a>
```

