# be-persisting [TODO]

be-persisting, [be-persistent](https://github.com/bahrus/be-persistent), [be-obsessing](https://github.com/bahrus/be-obsessing) overlap quite a bit.  They are all concerned with storing user data locally.

The differences in a nutshell:

be-persisting (this package) focuses on storing data in IndexedDB, and is configured primarily through "Hemingway notation" -  complete English statements (including the name of the attribute).

be-obsessing does the same, but focusing on session storage.

be-persistent works both with IndexedDB and Session Storage (and local storage), but is configured purely via JSON.