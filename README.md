#PyOhio_talk_2013

Notes and slides for talk on Code Reading


###Writing small programs is no longer a problem, how to transition to longer ones?

* learn from others, check out open source projects
* better yet, look at what interests you and contribute
 * you'll learn:
   * how to partition programs, (e.g. modules, objects, utilities)
   * see other's pattern usage:
     * Architectural patterns, (e.g. MVC, event-driven)
     * Design patterns
     * even simpler ones that never got their own name

###How to wrap your mind around big programs
 * There is only one book on this, "Code Reading"
   * We will pull out what we can from this, but it's examples are not in Python ...
 * Oddly enough, a lot of techniques here are inspired by an book on teaching reading for content: "Content Area Reading"
   * you can't read code, "cover to cover" and get much of a handle on it
   * you need strategies, (remember SQ3R?) our teachers tried ...
   * you need to go "multimodal"
     * pictures
     * sounds, (hey, talk out loud!)
     * motion, (hey, play is good!)
   * you need ways to check your understanding
   * you need ways to "lift the hood"

###We will illustrate this by looking at the open source program, "Plover"
   * What is this program supposed to do?
   * Speculate how you would do that
   * Read with an eye to how they did it & how that compares to your idea
   * check out the module structure, speculate from their names what they might do
   * any Architectural, (i.e. App-wide), pattern being used?
   * check out classes, their variables and methods
     * do the names make sense?
* Mnemonic tools
   * using pictures
   * give your memory a hand (Anki)
* Analysis tools
   * outliners: Leo, VOom
   * grep
* Under the hood tools
   * Ipython
   * Winpdb
* Probing for understanding with Tests
