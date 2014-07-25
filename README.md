This core directory serves as the basis for the Floating Orchard custom WordPress theme (https://github.com/jacobarriola/floating-orchard-wp).

<h2>Sass</h2>

The site is built using Sass and follows general recommended practices per Sass' documention (http://sass-lang.com/documentation/file.SASS_REFERENCE.html).  As of this write up, Sass 3.3.8 (Magestic Maple) was used.

Generally speaking, Sass was utilized for nesting CSS, organizing stylesheets, & color variables.

<h3>Compass</h3>

Compass (http://compass-style.org/) was used to make using Sass easier as well as a few mixins.  Compass was also used to compile the CSS to compress for production.

<h2>Foundation</h2>

The site is built using Foundation front-end framework (http://foundation.zurb.com/docs/) using a mobile first approach.  Few modifications were made to the default install other than <code>row</code> widths.

<h3>Breakpoints</h3>
Breakpoints used are Foundations' default: small, medium and large (see http://foundation.zurb.com/docs/media-queries.html).

There are a few overrides to accommodate the design; the modifications can be found in the <code>../sass/_mediaqueries.scss</code> file.

<h3>Global styles</h3>

The <code>row</code> max width is 1200px, which is declared in <code>../sass/vendor/foundation/_settings.sccss</code>.

All <code>.scss</code> files are imported onto <code>style.scss</code> and outputted to <code>style.css</code>.