# Installation #

  * Download **snipper-0.1.py**,
  * place all templates in ~/.vim/templates/
The script will search for files that contain the filetype and are xml files.
> > So if you have templates for python, you could name them python-templates.xml and    place that file in ~/.vim/templates
> > If you have scribes installed you can link ~/.vim/templates/ to ~/.scribes/templates
  * You need vim with python enabled to use this script


To let the script work place these lines in your .vimrc:

pyfile ~/.vim/scripts/snipper-0.1.py  (or the place where you have downloaded snipper)
imap 

&lt;tab&gt;

 

&lt;C-o&gt;

:python template.trigger()

&lt;CR&gt;


autocmd BufRead **python template.reInit()**

# Use #
enter a defined template and press tab
_more information will folow_