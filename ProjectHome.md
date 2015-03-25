Regfuzz is a collection of program and scripts for testing regular expression robustness using randomly generated valid and invalid regular expressions.

The base implementation is in C, but a swig interface definition is included along with [samples](http://code.google.com/p/regfuzz/source/browse/#svn/trunk/examples) of its use in multiple other languages ranging from pl/sql to javascript and C#.

This toolkit, while rudimentary, uncovered numerous bugs in multiple engines across platforms and languages.