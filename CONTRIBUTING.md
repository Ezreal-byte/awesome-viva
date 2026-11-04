# Contributing to Awesome Viva

Thanks for helping the Viva ecosystem grow. This list is curated, so not every
submission is merged; the rules below keep it useful.

## What belongs here

- Applications whose own UI is built with Viva and that ship to users.
- Tools, libraries and templates that work with Viva and are usable outside
  their author's machine.
- Guides, talks and articles that teach Viva itself rather than general Go or
  desktop programming.

## What does not

- Wrappers that only use Viva to open a window around a web page.
- Abandoned projects, private repositories, or projects whose README does not
  say how to build or install them.
- The same project under a second name, or a fork with no independent work.
- General-purpose Go GUI libraries that do not use Viva.

## Add an application

1. Edit `README.md` and `README.zh-CN.md` in the same pull request.
2. Add one line under Applications:

   ```markdown
   - [Name](https://github.com/owner/repo) - One sentence about what it does and who it is for. `macOS` `Windows` `Linux` · Licence
   ```

3. Keep entries in the existing order, one per project, and do not add badges
   or screenshots to the list.
4. Check that every link resolves before opening the pull request.

A maintainer may remove an entry that stops building on a released Viva version,
loses its source, or goes unmaintained.

## Licence

By contributing you agree that the list is released under CC0 1.0.
