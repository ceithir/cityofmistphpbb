

## Useful BBCode snippets

[General documentation on how to install BBCode](https://www.phpbb.com/support/docs/en/3.3/kb/article/adding-custom-bbcodes-in-phpbb3/)
[Advanced syntax to help make your own](https://s9etextformatter.readthedocs.io/Plugins/BBCodes/Custom_BBCode_syntax/)

These snippets will require the CSS contained in the theme to look good.

### Yellow note

```
[postit title={TEXT1?} size={CHOICE=normal,large;defaultValue=normal}]{TEXT2}[/postit]
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

### Option

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

