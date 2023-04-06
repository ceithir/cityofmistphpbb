

## Useful BBCode snippets

[General documentation on how to install BBCode](https://www.phpbb.com/support/docs/en/3.3/kb/article/adding-custom-bbcodes-in-phpbb3/)
[Advanced syntax to help make your own](https://s9etextformatter.readthedocs.io/Plugins/BBCodes/Custom_BBCode_syntax/)

These snippets will require the CSS contained in the theme to look good.

### Yellow note

```
[postit title={TEXT1?}]{TEXT2}[/postit]
```

```
<div class="bbcode-postit">
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
[choice title={TEXT1?} description={TEXT2?}]{TEXT3}[/choice]
```

```
<div class="bbcode-choice">
<div class="bbcode-choice-title">{TEXT1}</div>
<p class="bbcode-choice-description">{TEXT2}</p>
<div class="bbcode-choice-inner">{TEXT3}</div>
</div>
```

### Logos card

```
[logoscd title={TEXT1?}]{TEXT2}[/logoscd]
```

```
<div class="bbcode-logoscd">
<div class="bbcode-logoscd-title">{TEXT1}</div>
{TEXT2}
</div>
```

### Mythos card

```
[mythoscd title={TEXT1?}]{TEXT2}[/mythoscd]
```

```
<div class="bbcode-mythoscd">
<div class="bbcode-mythoscd-title">{TEXT1}</div>
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
[logos title={TEXT1} identity={TEXT2}]{TEXT3}[/logos]
```

```
<div class="bbcode-logos">
	<div class="bbcode-logos-header" />
	<div class="bbcode-logos-title">{TEXT1}</div>
	<div class="bbcode-logos-identity">
		Identity: <span class="bbcode-logos-identity-content">{TEXT2}</span>
	</div>
	<div class="bbcode-logos-inner">{TEXT3}</div>
</div>
```

### Mythos sheet

```
[mythos title={TEXT1} mystery={TEXT2}]{TEXT3}[/mythos]
```

```
<div class="bbcode-mythos">
	<div class="bbcode-mythos-header" />
	<div class="bbcode-mythos-title">{TEXT1}</div>
	<div class="bbcode-mythos-mystery">
		Mystery: <span class="bbcode-mythos-mystery-content">{TEXT2}</span>
	</div>
	<div class="bbcode-mythos-inner">{TEXT3}</div>
</div>
```

