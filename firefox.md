# You should be using Firefox
## Background 
I'll keep the actual background information about Mozilla as a company pretty
short, and leave researching them as an exercise for the reader. I will say that
the team behind Firefox is easily more ethical and on your side compared to
Google, and actively works to give you as much control over every aspect of your
browsing experience.

## Basic Customization
Poking around Firefox's settings shows the basic stuff that every browser has,
and I wont spoonfeed every step in there because it's unnecessary, but I'll
highlight a few cool features.

## Advertising And Tracking
Preferences -> Privacy & Security -> Enhanced Tracking Protection

Changing to Custom and blocking all third party cookies and tracking content
in all windows will shut down almost all intrusive advertising, without
installing a full-on adblocker. 

A second step is to go down to Cookies and Site Data and turn on deleting
cookies and site data when Firefox is closed. If you still want to stay logged
in to certain web sites you can add permissions for those sites right above
this option, but at least on my machine this is not currently working so I have
this setting turned off.

### Configuration editor preferences:
One interesting option that isn't yet in the default features is First Party
Isolation. Enabling it requires us to go into the `about:config` settings
however. Simply type `about:config` into your address bar and you will see the
advanced preferences in Firefox. Search for `privacy.firstparty.isolate` and
either double click it or set it's value to `true`.

This setting restricts cookies, cache, and other site data so it can only be
used by the first party domain name. This stops advertising from following and
tracking your behavior across different sites you visit.

Or...

## Multi-account Containers
[Multi-Acount Containers](https://addons.mozilla.org/en-US/Firefox/addon/multi-account-containers/)
are Firefox's solution to websites that track you even in other tabs. According
to the description *"it separates website storage into tab-specific Containers.
Cookies downloaded by one Container are not available to other Containers."*
This is a more general-purpose version of mozilla's Facebook Container. This one
does not automatically work on facebook but instead can work on anything with
some setup.

Once set up, even links clicked from another web site will automatically open
different containers

