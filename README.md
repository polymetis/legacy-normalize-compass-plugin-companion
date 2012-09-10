##Legacy Compass Normalize Plug-in Companion

In the most recent version of both the official [Normalize.css](http://necolas.github.com/normalize.css/) and [the compass companion plugin](https://github.com/jzorn/compass-normalize-plugin) support for legacy browsers has been cut. Despite the fact this is the correct thing to do there are still occasions where we will need for the legacy code. e.g. A client asks for better IE support or something else peculiar.  

One solution is to simply roll back the version number of the compass compass but then we risk losing upstream revisions which we may be depending on for the project in question. So I thought I would take all the depreciated code and put it in a style sheet for us to import when the need arises.

On the future of this project: I will keep this in sync with the series one of Normalize.css but I am not doing anything else with it. It is merely an effort to make the need to import this to a project easier.

Pull requests are both encouraged and welcome.
