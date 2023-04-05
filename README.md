

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


