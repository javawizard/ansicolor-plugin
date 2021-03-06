0.4.1 (Next)
=====

* Added support for default text and background color sequences (resetting color changes) - [@ejelly](https://github.com/ejelly).

0.4.0
=====

* [#17](https://github.com/dblock/jenkins-ansicolor-plugin/issues/17), [#26](https://github.com/dblock/jenkins-ansicolor-plugin/pull/26): Log text is not replaced with markup anymore, just supplemented - [@ejelly](https://github.com/ejelly).
* [#19](https://github.com/dblock/jenkins-ansicolor-plugin/issues/19): Actually remove escape sequences from log stream - [@ejelly](https://github.com/ejelly).
* Properly nest HTML elements - [@ejelly](https://github.com/ejelly).
* Added support for ANSI underline double - [@ejelly](https://github.com/ejelly).
* Using `commons-lang` to HTML-encode color output - [@dblock](https://github.com/dblock).
* Failure to annotate console output will be logged as a warning - [@dblock](https://github.com/dblock).

0.3.1
=====

* [#10](https://github.com/dblock/jenkins-ansicolor-plugin/issues/10): Fix: broken colored console output from jobs that used a previous version of AnsiColor - [@dblock](https://github.com/dblock).

0.3.0
=====

* Upgraded to JANSI 1.9 - [@chirino](https://github.com/chirino).
* [#5](https://github.com/dblock/jenkins-ansicolor-plugin/issues/5): Fix: improper handling of default background and foreground color reset - [@dblock](https://github.com/dblock).
* [#7](https://github.com/dblock/jenkins-ansicolor-plugin/pull/7): Fix: corrupt strings that contain non-ASCII characters - [@takai](https://github.com/takai).
* [#9](https://github.com/dblock/jenkins-ansicolor-plugin/pull/9): Added support for configuring color mapping - [@harrah](https://github.com/harrah).

0.2.1
=====

* Upgraded to JANSI 1.7

0.2.0
=====

* Added support for concealed ANSI blocks that produced garbled output.

0.1.2
=====

* Official release that supports ANSI color, bold and underline.

