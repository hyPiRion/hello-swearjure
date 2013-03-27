# hello-swearjure

`Hello, World!` application in Swearjure. Prints out `Hello, World!` in the
terminal window and exits.

hello-swearjure uses only 9 alphanumerical characters, 7 distinct ones, on a
single line: `meta ns-map`. This is currently needed once for `project.clj`, and
once for the application (only one for multiple files, theoretically).

## Usage

As of now, you can run hello-swearjure by issuing the following command:

    $ lein run

*You must use Leiningen 2.1.0 or higher to run this program.* The program will
 otherwise crash, as it needs Leiningen to run on Clojure `1.5.x`.

For unknown reasons, it is currently impossible to make this program as a
standalone jar file. If you have attempted to do so, ensure you perform `lein
clean` before attempting to run the program again.

## License

Copyright © 2013 Jean Niklas L'orange

Distributed under the Eclipse Public License, the same as Clojure.
