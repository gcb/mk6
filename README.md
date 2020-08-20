# Mardown UI (mk6)

UI description for Markdown.

## Audience

The audience for this project is anyone wanting to add UI drawings, either to communicate new function, or describe real world screens.

The audience of this file is for end-users (the people writting the text documents). See [(Contributing.2.md)] for the actual project code README.

## Goals

- [ ] Be better than using an image
   * Add without leaving text editor
   * No external serving needs
   * No extra image manipulation programs
   * Easy to update when software look and feel changes
   * wastefull to describe rectangles with text
   * Distract with irrelevant information on rest of screen
- [X] Resulting HTML5 easy to code by hand, or read source and understand
- [X] Quick to abstract or possible to overdo a fully realistic rendering, but with very few base elements
- [X] Final text on widgets can always be copied (even checkmark and toggle buttons, on/off, etc)
- [X] Acceptable on screen readers
- [ ] Easy to theme (darkmod on/off. Or pick OS highlight based on site branding. white backgrouns on print. etc)
- [ ] i18n?
- [ ] Can be used by dynamic javascript apps as an actual UI (but will never require javascript)

## Status

Tasks:

- [X] write README
- [X] HTML5 output examples
- [X] Positioning CSS and base theme (Xwindow flat)
- [ ] Markdown syntax ( \`\`\`mk6 or \`\`\`ui? )
- [X] windows
- - [X] titles
- - [X] grid (rudimentary 3 column mode only)
- - [ ] buttons
- - [ ] border
- [ ] labels
- [ ] buttons
- [ ] checkboxes
- [ ] radio buttons
- [ ] menus
- - [ ] context menus

## Out of scope

Only elements actually present on 90% of UIs will be included.

Not in scope: call out boxes, arrows (use color borders), comment boxes floating on UI (use text around image)

Not in scope: Images. Duh! Light textures that can be done with pure CSS and represent look of a well known UI element are OK.

Not in scope: Animations.

## HTML5 syntax

`.mk6` class name bellow can be any other name.

NOTE: this style tag can show up only once or at every code block you need it.

```html
<style>
.mk6 { @import 'mk6.css' }
</style>
```

```html
<window>
	<title>Title of the window</title>
	<list column>
		<label>C:\</label>
		<label>C:\Windows</label>
		<skip></skip>
		<label clickhere>C:\Windows\System32</label>
		<label>D:\</label>
	</list>
	<icons column2x>
		<icon file></icon>
		<icon file></icon>
		<icon image></icon>
		<icon executable></icon>
	</icons>
</window>
```

## Markdown (extension?) syntax

TBD

## License

GPLv3
