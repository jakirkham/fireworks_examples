#Install

1. MongoDB (uses C++ so compiling is best)
2. pycrypto (has C so compiling is best)
3. FireWorks (and dependencies, rest are pure Python so pip is fine)
4. iPython Notebook (obviously :) )

#Configure

##MongoDB

For MongoDB, it expects to use the path `/data/db/` as its `dbpath` by default. So, either add this path and relax the restrictions on the directory or specify a different path. MongoDB can be setup to fork and spool to disk or it can be run directly and allowed to dump into a terminal. The latter is trivial and can be done by running `mongod`. Other options can be found by running `mongod --help`.

##FireWorks Web GUI

Kindly, they provide a Web GUI to check job statuses. To get running is straightforward, just run `lpad webgui` and it will open in the browser. Uses Flask.

##iPython

Nothing special. Just run `ipython notebook` in the repo and you are ready to go.

#Run

Pull up notebooks and run them to try it out and, of course, have fun!
