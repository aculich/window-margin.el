# window-margin.el

## Overview

<table>
<tr><td>Maintainer</td><td><a href="mailto:aculich@gmail.com">Aaron Culich</a></td></tr>
<tr><td>Version</td><td>0.1</td></tr>
<tr><td>Keywords</td><td>margins, text, visual-line, word wrap</td></tr>
<tr><td>URL</td><td>http://github.com/aculich/window-margin.el</td></tr>
<tr><td>Description</td><td>Automatic margins for visual-line-mode wrapping</td></tr>
</table>

## Commentary

This minor mode will automatically resize windows to the width of the fill-column, or optionally to some fixed size set with the window-margin-width variable.

To enable it with text-mode use:

```
(add-hook 'text-mode 'turn-on-window-margin-mode)
```

This minor mode was inspired by reading [an entry on StackOverflow](http://stackoverflow.com/q/14009223/462302). I discovered that (the quirky, but useful) longlines-mode was being discontinued. I can't claim that this mode will be any less quirky (probably moreso at this early 0.1 release), but it makes use of margins and visual-line mode which is better way to accomplish the effect than implemented by longlines-mode

## License

Copyright 2012, Aaron Culich

```
This file is part of GNU Emacs.

GNU Emacs is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

GNU Emacs is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with GNU Emacs.  If not, see <http://www.gnu.org/licenses/>.
```
