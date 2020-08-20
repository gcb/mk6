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
- [ ] Resulting HTML5 easy to code by hand, or read source and understand
- [ ] Quick to abstract or possible to overdo a fully realistic rendering, but with very few base elements
- [ ] Final text on widgets can always be copied (even checkmark and toggle buttons, on/off, etc)
- [ ] Acceptable on screen readers
- [ ] Easy to theme (darkmod on/off. Or pick OS highlight based on site branding. white backgrouns on print. etc)
- [ ] i18n?
- [ ] Can be used by dynamic javascript apps as an actual UI (but will never require javascript)

## Status

Tasks:

- [X] write README
- [ ] HTML5 output examples
- [ ] Positioning CSS and base theme (Xwindow flat)
- [ ] Markdown syntax ( \`\`\`mk6 or \`\`\`ui? )
- [ ] windows
- - [ ] titles
- - [ ] grid
- - [ ] buttons
- - [ ] border
- [ ] labels
- [ ] buttons
- [ ] checkboxes
- [ ] radio buttons

## Out of scope

Only elements actually present on 90% of UIs will be included.

Not in scope: call out boxes, arrows (use color borders), comment boxes floating on UI (use text around image)

Not in scope: Images. Duh! Light textures that can be done with pure CSS and represent look of a well known UI element are OK.

Not in scope: Animations.

## License

GPLv3
