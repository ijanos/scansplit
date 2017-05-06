# Scan & split

Split scanned photos from a single image.

## Preprocessing

If the photos touch the edge of the scanned picture you can use GraphicsMagick
(or ImageMagick) to add a neutral colored border.

```
gm mogrify -border 10x10 -bordercolor "#ebeae9" test_b.png
```

## License


### Code

    Copyright (C) 2017 János Illés

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.


### Photos

    The pictures are licensed under a
    Creative Commons Attribution 4.0 International License.

    You should have received a copy of the license along with this
    work. If not, see <http://creativecommons.org/licenses/by/4.0/>.
