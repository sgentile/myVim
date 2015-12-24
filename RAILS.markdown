http://www.vim.org/scripts/script.php?script_id=1567

“:R” – This jumps to a related piece of code. For instance, if your cursor is in the “edit” part of your controller, it will jump you to the edit.html.erb view for that controller.
“:Rview NAME_OF_VIEW” – This is great for when your in a controller and you want to jump straight to one of the views. I only use this command to jump to partials because I can specify the files name.
“:Rcontroller NAME_OF_CONTROLLER” – same as the previous mentioned except for the controller.
“:Rmodel NAME_OF_MODEL” – same as the previous two, but for the model
“:Rserver” – This actually will start the server for you without having to go into the terminal
“:Rserver!” – notice the “!” on the end? that stop the server for you
“:Rpreview” – this jumps you right to your browser to preview your site
“:Rfind FILE_TO_FIND” – by far this is my favorite command. This will find any file in your RoR directory. This one you really need to experiment with for yourself to understand how it works but it’s really nice.
“:Renvironment” – takes you to your environment file, but you can also do :Rfind environment and it will find it.
