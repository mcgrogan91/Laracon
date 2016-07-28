# Taylor Otwell - Laravel 5.3 Overview

* Released in a week or two.  Code released soon
* Routes now have web, api
* Webpack replaces browserify in elixer build
* make::auth now uses Vue
* Don't need to inherit from Controller for controllers
* Queue workers can have  time out set
* Mail has new syntactic sugar with mail classes.  No more ugly closures! Easy queuing
* Notifications
    * via - how do we send the notification?
        * Returns driver array, can inspect notifiable to determine types
        * Can have states
        * Queueable
* Packages can register their own migrations without having to export them into yours

### Scout

Full text searching, drivers update search products. (Algolia)

### Auth Driver: Laravel Passport

OAuth 2 server - API authentication
