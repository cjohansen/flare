# Flare

Flare brings enlightened failure reports to your [clojure.test](http://richhickey.github.io/clojure/clojure.test-api.html) tests.

Latest version is:

```clojure
[flare "0.1.0-SNAPSHOT"]
```

## Usage

Flare is activated by calling `flare.clojure-test/install!`.

To use Flare with [Leiningen](http://leiningen.org/), merge the following with your project.clj:

```clojure
{:profiles
 {:dev
  {:injections
   [(require 'flare.clojure-test)
    (flare.clojure-test/install!)]}}}
```

Run your tests, using your favourite test runner, and enjoy the enlightenment Flare brings to your failing tests.

## License

Copyright © 2014 Anders Furseth

Distributed under the Eclipse Public License either version 1.0 or (at
your option) any later version.
