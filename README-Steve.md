See
  https://help.github.com/articles/using-jekyll-with-pages
for more on using Jekyll with github-pages.  Notably:

Execute
  bundle exec jekyll serve
in the root directory to build and serve the page.

Use
  bundle update
in the root directory to update jekyll dependencies

# To convert images:

## Using ImageMagick to convert an image to another format:
 convert file.tif file.jpg

## Using ImageMagick to resize a file (for e.g. creating thumbnails):
 convert -resize x100 file.jpg file_thumb.jpg

## Acting on multiple files (examples):
rename "s/ /-/" *
   849  for fn in `ls -1 *tif`; do pref=`echo $fn | awk 'BEGIN {FS="."};{print $1}'`; convert $pref.tif $pref.jpg; done
  862  for fn in `ls -1 *jpg`; do pref=`echo $fn | awk 'BEGIN {FS="."};{print $1}'`; convert -resize x100 ${pref}.jpg ${pref}_thumb.jpg; done
  888  for fn in `ls -1 halloween*.jpg`; do echo $fn; mv $fn ${fn//halloween/2008-10-31-CMIA-halloween_}; done
