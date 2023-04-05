

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

