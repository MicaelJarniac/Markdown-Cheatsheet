# Markdown-Cheatsheet

A few Markdown tricks and other stuff I find useful.

## Keyboard Input

The `<kbd>` tag can be used to represent keyboard keys, and is correctly rendered on GitHub.

Okay, it's technically not Markdown, it's HTML, but it works in Markdown.

Read [this Mozilla Web Docs](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/kbd) page for more info.

<kbd>Ctr</kbd>+<kbd>C</kbd> copies stuff.  
<kbd><kbd>Ctr</kbd>+<kbd>C</kbd></kbd> does the same, but is nested.  
To create a new file, choose the menu option <kbd><kbd><samp>File</samp></kbd>⇒<kbd><samp>New Document</samp></kbd></kbd>

| Key | Action |
|--|--|
| <kbd>Ctr</kbd>+<kbd>V</kbd> | Pastes stuff |
| <kbd>Space</kbd> | Insert a space character |

## Anchors

`[This takes you to the An Example for the Anchors Section section](#An-Example-for-the-Anchors-Section)`

[This takes you to the An Example for the Anchors Section section](#An-Example-for-the-Anchors-Section)

## Details/Dropdown/Spoiler Section

This one is also mostly HTML, but hey, if it works it works.

```markdown
<details>
  <summary>Click me!</summary>
  
  # The hidden section
  
  Oh, you clicked? Wonderful! Now I can show you that, if you add a blank line after the last `summary` tag, you can have Markdown inside here too!
</details>
```

<details>
  <summary>Click me!</summary>
  
  # The hidden section
  
  Oh, you clicked? Wonderful! Now I can show you that, if you add a blank line after the last `summary` tag, you can have Markdown inside here too!
</details>

## An Example for the Anchors Section

## Testing area

Here there be testing stuff, ignore.

<button name="button">Click me</button> - `<button>` doesn't work

[![](https://img.shields.io/badge/label-message-red)][none]

[none]: #
