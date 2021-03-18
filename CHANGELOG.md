# v1.0.3
Some general enhancements that should make this a bit better.
- Some changes to prevent this thing from completely breaking if a plugin / Discord themselves adds a new staus to the menu. It'll still break, but not completely.
- Removed the transition for hovering on the custom status box.
- Removed some unnecessary uses of !important.
- There are two new variables that you can use to set the box-shadow color and for when you hover on the custom status box.
```css
:root {
    --box-shadow-color: rgb(0, 0, 0, 0.5);
    --custom-status-hover: #5C6FB1;
}
```

# v1.0.2
Multiple fixes that this thing really needed.
- If you're using the Game Activity Toggle plugin and have it where it displays on the status list, it should no longer break the entire thing. I couldn't really find out a proper way to fix this- this entire thing is scuffed to begin with so I just put it in the top left part of the menu.
- Fixed the position issue for the placeholder avatar. You can also customize that now if you'd like!

# v1.0.1
Made the custom status placeholder text reappear; kinda looked strange when blank.

# v1.0.0
Initial creation, welcome!