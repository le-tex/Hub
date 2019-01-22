Hub
===

Flattened DocBook plus CSSa.

The unaltered DocBook Publishers V5.1CR1-1 RNG schema is included here (might have included DocBook as a submodule but didn’t find docbook.rng in its repo).

CSSa is included as a submodule from https://github.com/le-tex/CSSa

SVG 1.1 (rng files from http://www.w3.org/Graphics/SVG/1.1/rng/) modifications: 
 
 * Removed relaxng.dtd references
 * define and ref elements of 'set' and 'image': replaced with 'svg-set' and 'svg-image'

Cloning
-------

git clone https://github.com/le-tex/Hub hub

cd hub

git submodule init

git submodule update

