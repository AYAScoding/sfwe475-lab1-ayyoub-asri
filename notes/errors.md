

- "^": Allows automatic updates to any future version that does not break backward compatibility 
- "Major": Incremented when there are breaking API changes.
- "Minor": Incremented when new functionality is added in a backward-compatible manner.
- "Patch Number": Incremented when backward-compatible bug fixes are made.

node_modules is excluded from git because it's too large and so innecessary  since there are files 'package.json and package-lock.json' that keeps track of the project dependancies , so that anyone can get the project envirement up and running just by using those two files.