			      KindleClip
			      ==========

In late 2010, I bought an Amazon Kindle device. It has wildly changed
the way I interact with written material. Not only it allows me to
read whatever interests me, whenever I want to, but it brought me a
sacred pleasure I had denied to myself for too long: Taking notes as I
read.

Yes, I consider books to be sacred, and don't like marking them. I had
often taken together a book and a notepad, and some of my books have
one (or more) sheets of paper with them, noting the most
interesting/remarkable places. But now, given the perennial and
pristine nature of electronic files, I am extensively taking notes,
highlighting, and bookmarking the places I want to return to!

Now, the Kindle stores all said annotations in a very easy to parse
"My Clippings.txt" file — They are always shown when reading the book,
but are a bit hard to use otherwise. I often read more than one book
at a time. When I highlight a passage, I will often want to quote it
in other texts I am writing...

So I wrote this little user interface for managing the "My Clippings"
file. It allows you to filter on the type of note you will be
searching on (notes, bookmarks or highlights), order by author, book
or date, and filter by text.

Usage
-----

The "My Clippings.txt" file should be available under the documents/
directory of your Kindle. You can either use it directly from the
Kindle, while it is mounted, or copy it over to your filesystem.

By default, kindleclip will open the file "My Clippings.txt" in the
current directory. You can specify which file to open as an argument
on invocation — as:

$ kindleclip.rb /media/Kindle/documents/My\ Clippings.txt

Disclaimer
----------

This program is in no way endorsed, promoted or should be associated
with Amazon. It is not –and does not aim to be– an official Kindle
project.

Participation
-------------

If you want to participate in the development of this software, please
clone from the main Git repository:

   git://github.com/gwolf/kindleclip.git

You can fork the repository (and I'll most probably pull your changes
just at a notice).

If you are not a coder, fear not! you can contact me directly for any
requests or suggestions. I am sometimes slow to manage my mail, but
will do my best to be attentive and quick.

Licensing
---------

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful, but
WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU
General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see
<http://www.gnu.org/licenses/>.

The sources for Kindleclip also include «setup.rb». This file is
Copyright © 2000-2005 Minero Aoki, and released under the GNU LGPL 2.1
license.

	— Gunnar Wolf <gwolf@gwolf.org>
