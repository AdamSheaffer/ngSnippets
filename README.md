# ngSnippets
Angular snippets for Visual Studio

To add these to your visual studio, download these .snippet files and add them to the folder:
`C:\Users\[USERNAME]\Documents\Visual Studio 2015\Code Snippets\JavaScript\My Code Snippets`

Afterwards, go in Visual Studio and hit Ctrl-K, Ctrl-B to get in your code-snippet manager. Make sure that these files
are listed under the "My Code Snippets" folder when viewing JavaScript.

The snippets are:

`ngController`

```
(function () {
    'use strict';

    function _$MY_CONTROLLER() {
        var vm = this;
    }

    angular.module('_$MY_MODULE')
        .controller('_$MY_CONTROLLER', _$MY_CONTROLLER);

})();
```

### AND

`ngService`

```
(function () {
    'use strict';

    function _$MY_SERVICE() {
        var self = this;
    }

    angular.module('_$MY_MODULE')
        .service('_$MY_SERVICE', _$MY_SERVICE);

})();
```
