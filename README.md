## ITCSS
ITCSS stands for *Inverted Triangle CSS*

### TL;DR

Layer | Description
------|------------
Settings | used with preprocessors and contain font, colors definitions, etc.
Tools | globally used mixins and functions. It’s important not to output any CSS in the first 2 layers.
Generic | reset and/or normalize styles, box-sizing definition, etc. This is the first layer which generates actual CSS.
Elements | styling for bare HTML elements (like H1, A, etc.). These come with default styling from the browser so we can redefine them here.
Objects | class-based selectors which define undecorated design patterns, for example media object known from OOCSS
Components | specific UI components. This is where majority of our work takes place and our UI components are often composed of Objects and Components
Trumps | utilities and helper classes with ability to override anything which goes before in the triangle, eg. hide helper class

### Modules
Package Name | Layer | Github Repo
-------------|-------------|---------
inuit-defaults | settings | https://github.com/inuitcss/settings.defaults
inuit-responsive-settings | settings| https://github.com/inuitcss/settings.responsive
inuit-functions | tools | https://github.com/inuitcss/tools.functions
inuit-mixins | tools | https://github.com/inuitcss/tools.mixins
inuit-responsive-tools | tools | https://github.com/inuitcss/tools.responsive
inuit-tools-widths | tools | https://github.com/inuitcss/tools.widths
inuit-normalize | generic | https://github.com/inuitcss/generic.normalize
inuit-box-sizing | generic | https://github.com/inuitcss/generic.box-sizing
inuit-reset | generic | https://github.com/inuitcss/generic.reset
inuit-shared | generic | https://github.com/inuitcss/generic.shared
inuit-headings | base | https://github.com/inuitcss/base.headings
inuit-paragraphs | base | https://github.com/inuitcss/base.paragraphs
inuit-lists | base | https://github.com/inuitcss/base.lists
inuit-images | base | https://github.com/inuitcss/base.images
inuit-page | base | https://github.com/inuitcss/base.page
inuit-block | objects | https://github.com/inuitcss/objects.block
inuit-box | objects | https://github.com/inuitcss/objects.box
inuit-buttons | objects | https://github.com/inuitcss/objects.buttons
inuit-flag | objects | https://github.com/inuitcss/objects.flag
inuit-layout | objects | https://github.com/inuitcss/objects.layout
inuit-list-bare | objects | https://github.com/inuitcss/objects.list-bare
inuit-list-block | objects | https://github.com/inuitcss/objects.list-block
inuit-list-ui | objects | https://github.com/inuitcss/objects.list-ui
inuit-media | objects | https://github.com/inuitcss/objects.media
inuit-pack | objects | https://github.com/inuitcss/objects.pack
inuit-tables | objects | https://github.com/inuitcss/objects.tables
inuit-tabs | objects | https://github.com/inuitcss/objects.tabs
inuit-clearfix | trumps | https://github.com/inuitcss/trumps.clearfix
inuit-headings-trumps | trumps | https://github.com/inuitcss/trumps.headings
inuit-spacing | trumps | https://github.com/inuitcss/trumps.spacing
inuit-spacing-responsive | trumps | https://github.com/inuitcss/trumps.spacing-responsive
inuit-widths | trumps | https://github.com/inuitcss/trumps.widths
inuit-widths-responsive | trumps | https://github.com/inuitcss/trumps.widths-responsive
inuit-print | trumps | https://github.com/inuitcss/trumps.print
