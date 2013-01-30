!SLIDE
# Foundation

* Naming sucks
* So does consistency

!SLIDE
# Foundation

* Common API payloads
* Common controller helpers for building payloads
  - errors
  - metadata
  - result


CODECODECODECODECODE

!SLIDE
# Foundation

  * Base class for remote objects
  * Auto resource location
  * Open up payload envelope
  * Querying (active dev)

CODECODECODECODECODE

!SLIDE
# User Service

* User Auth
* Ngin special treatment
* current_user for future apps

!SLIDE
# User Service

![oauth2](oauth2.png)

!SLIDE
# User Service
## Permissions

![youshallnotpass](http://images.wikia.com/legomessageboards/images/2/28/You-shall-not-pass.jpeg)

!SLIDE
# User Service
## Permissions & Groups

* Flat

![plank](http://www.planking.me/wp-content/uploads/2012/11/bulldog_first_time_planking.jpg)

!SLIDE
# User Service
## Permissions

* Client-side interpretation (not a browser)
* Backends => Elmer (we'll get there)
* Clients => 401s

!SLIDE
# Elmer
## Not a gem for rabbit hunters

![fudd](http://userserve-ak.last.fm/serve/_/4739327/Elmer+Fudd+Elmer_Fudd_A_Wild_Hare.jpg)

!SLIDE
# Elmer

![user](http://fc02.deviantart.net/fs71/i/2011/027/9/5/fight_for_the_user_by_nostrildarmus-d385u9h.jpg)

!SLIDE
# Elmer

* Users!
* Built on Foundation
* OAuth2 Redirect (token grant type) workflow
* Access Token passing

CODECODECODECODECODECODECODE

!SLIDE
# Elmer

* Permission checks
* DSL for defining cascading

CODECODECODECODECODECODECODE

!SLIDE
# Elmer

* Groups

CODECODECODECODECODECODECODE
