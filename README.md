Sass Boilerplate for generic CSS/HTML
=============
Done by akella with kind help of Coderiver guys.

I'm using this as a starting template for almost any project now.
It includes sprites, assorted mixins (aka code snippets), file structure, jquery+cycle+scrollto (most usable these days).
And, that's it.

You need to have Compass installed for it to work properly.

Structure
=============
`/sass/lib/base` - all the mixins and libs needed for us.

`/sass/screen.sass` - agregates all .sass files.

`/sass/main.sass` - styles for the mainpage.

Naming blocks
=============
I use BEM naming, meaning `.block` for independent block. `.block__element` for elements inside that block. And `.block_modification` for modification of the block.

`layouts.sass` consists of all the columns-header-footer stuff, all with `.l-*` prefixes. So you know its layout.

States of the blocks use prefix `.is-*`. For example `.is-running`, `.is-hidden`, `.is-open`.

Hooks for js should use prefix `.js-*`.
