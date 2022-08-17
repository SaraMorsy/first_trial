# first_trial_workflow

PLease note that varnish is builtin sandpaper package
Three main things I tried for the styling:


1- edit source code of Varnish package and then link it through pkgdown.yml in ~/site or config.yml in the main directory **this step requires R which is the reason I didinot use Github)**


2- created local css and java script files, edited the infrastructure and removed varnish dependencies (**this took the longest time and it only worked on external features not call out **  :confused:

3- edited the workflows to link varnish files **remember the sand_main.yml which I showed you in the meeting**


I feel the right step is the first step, there might be something I missed in editing the package and I think this where you want to start. The error message werenot helful, the workflow mentions where the  error in config files but it did not point out the errors in source code

Please note the ~/source in the varnish package contains CSS files, that's why I believe this where you should start. I edited it and added the ELIXIR-UK styles and linked it through ~/site/pkgdown.yml

Then tried to link it through ~/config.yml
