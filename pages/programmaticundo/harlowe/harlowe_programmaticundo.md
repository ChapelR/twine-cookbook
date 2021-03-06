# "Programmatic Undo": Harlowe (v2.0)

## Summary

While Harlowe supports allowing the user to undo and redo moves, the "undo" operation can also be accessed through the [`(undo:)`](https://twine2.neocities.org/#macro_undo) macro. Through its use, changes from the most current action can be "undone."

## Example

[Download](harlowe_programmaticundo_example.html){: target="_top" download="harlowe_programmaticundo_example.html"}

## Twee Code

```twee
:: StoryTitle
Programmatic Undo in Harlowe

:: Start
[[Enter the darkness]]

:: Enter the darkness
(link: "You are not ready. Go back!")[(undo:)]
```

[Twee Download](harlowe_programmaticundo_twee.txt){ target="_top" download="harlowe_programmaticundo_twee.txt"}
