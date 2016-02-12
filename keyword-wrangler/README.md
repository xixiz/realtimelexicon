##First commit for the keyword-wrangler app in nodecraftsman##
Build on this.

###The Server###
The server is src/backend/index.js.

To start the server, simply cd into that directory and run 'node index.js'

###The Tests###
I decided to use cucumber tests, so all of the specifications as well as all
of the steps for completing the specifications are in features. The
specifications are .feature files and the tests are the .js files in
features/step-definitions

###Running the Tests###
In order to make running the tests easier, I made a test-script file in the
top level directory. In order to run the tests, simply run 'node test-script.js'
in the top level directory.