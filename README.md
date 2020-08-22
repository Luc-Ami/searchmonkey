# searchmonkey
How to build Searchmonkey 0.9 series ?
Install dependencies (please have a look on configure.ac file : libgtk3, libzip, poppler-glib are mandatory ; please install libraries AND headers)
Install all developpement tools : gcc compiler, autotools, internationalization tools (gettext, inttl ..)

Then type :
cmod+x configure
./configure
make

if no errors :

sudo make install

otherwise :
check errors and install missing tools and/or dependencies


