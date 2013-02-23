My Sass template (by akella), or boilerplate, whatever =) I should invent some cool name later on.
=============

I'm using this as a starting template for almost any project now.
It includes sprites, assorted mixins (aka code snippets), file structure, jquery+cycle+scrollto (most usable these days).
And, that's it.

You need to have Compass installed for it to work properly.

Structure
=============
`/sass/libs` - all the mixins and libs needed for us.

`/sass/_mixins.scss` - agregates all those libraries and some common styles

`/sass/screen.scss` - agregates all .scss files.

Naming blocks
=============
I use BEM naming, meaning `.block` for independent block. `.block__element` for elements inside that block. And `.block_modification` for modification of the block.

`layouts.css` consists of all the columns-header-footer stuff, all with `.l-*` prefixes. So you know its layout.

States of the blocks use prefix `.is-*`. For example `.is-running`, `.is-hidden`, `.is-open`.

Hooks for js should use prefix `.js-*`.
