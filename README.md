# Kevin-Earley-Website
_Kevin Earley's personal website and blog_

A Senior at Sharon High School, Kevin Earley has been progressively developing this site, since October of 2016, as a part of his in-school internship, with the Sharon High School Technical Literacy Department, through the SHS Help Desk program. When asked to blog his efforts in the program last year, and being told that he could choose any blogging platform, Kevin thought "Why not make one from scratch?". It was a fantastic oppurtunity to try out web development skills that he had been eager to learn. Now a year old, Kevin is working to overhaul the blog and grow it's scope to act as his personal website _and_ blog, for the very same reason he embarked on the project in the first place, to try out new web development skills.
  
However, this time around it's not purely about "web" development. With this update to the blog, one of Kevin's goals is to turn his site into a "progressive web app" or "PWA", which is essentially a hybrid site that users access, first, through a web browser, but then, static site elements are cached on the users device, so the site is at least partially functional offline. Upon reconnection to a network, PWA's update dynamic content. This concept is taking on a very notable trend in the industry, because of how much more accessible it makes web content to it's users, even in offline situations. It also increases loading times, as some elements are already downloaded. This repository will chronicle all updates that Kevin makes to the site and his learning process.

**Site URL:** https://KevinEarley.me

**Repository URL:** https://github.com/kearley2018/kevin-earley-website

**Kevin on Linkedin:** https://www.linkedin.com/in/kevin-earley

**Kevin's email address:** kearley2018@gmail.com

**More info on the SHS Tech Help Desk program:** https://helpdeskshs.wordpress.com

_________________________________________________________________________________________________

## Style Guide
### Repo Folder Structure
**Below is a map of the folder structure of this repo, with an explanation of the contents of each.** _DISCLAIMER: In some cases, certain code will not be found in the folder or files that make the most sense for it to be within. This is simply due to the tendency for certain code to be difficult to categorize in a way that is sensical by human standards._
  * **front-end:** _design and user experience config and static textual copy_
    * **dynamic-config:** _dynamic ui and structural elements, like major layout alterations, for responsive design, and animated features_
      * **in-visit-alterations:** _dynamic changes to the ui, based on user interaction, during their site visit_
        * **design-experience:** _dynamic changes to the ui, based on user interaction, for the sake of design aesthetic_
        * **functional-experience:** _dynamic changes to the ui, based on user interaction, for the sake of functionality_
      * **responsive:** _dynamic changes to the ui, at page-load, for the sake of display in many environments and situations_
    * **structure:** _static structure, content input spaces, and minor responsive design rules, like adjusting to width_
      * **custom-frame:** _site-specific structural frame, which houses polymer elements_
        * **html:** _nested HTML structure_
        * **html-min:** _minimized HTML structure_
        * **jade:** _nested structure written in Jade, an HTML framework_
      * **polymer-elements:** _custom reusable elements_
        * **html:** _nested HTML structure_
        * **html-min:** _minimized HTML structure_
        * **jade:** _nested structure written in Jade, an HTML framework_
    * **style:** _all stylesheets/aesthetic styling rules_
      * **plugins-frameworks:** _third-party styling_
        * **polymer-elements:** _polymer element styling_
      * **sheets:** _all fully custom stylesheets_
        * **css:** _fully custom CSS styling_
        * **css-min:** _minimized fully custom CSS styling_
        * **sass:** _fully custom styling written in Sass, a CSS framework_
    
  * **back-end:** _data-translation, transformation, and dynamics rules_
    * **search:** _all data-translation rules related to the main search and sorting_
    * **posts:** _all data-translation rules related to blog posts_
      * **post-creation:** _all data-translation rules related to creating blog posts_
      * **post-management:** _all data-translation rules related to managing blog posts_
    * **notifications:** _all data-translation rules related to notifications and pwa notification triggers_
      * **notification-creation:** _all data-translation rules related to creating notifications_
      * **notification-management:** _all data-translation rules related to managing notification data_
    * **comments:** _all data-translation rules related to commenting_
    * **category-spotlight:** _all data-translation rules related to selecting the featured content in category pages_
    * **category-page-creation:** _all data-translation rules related to creating category pages_
    * **analytics:** _all data-translation rules and third-party code related to analytics_
    
  * **data-tables:** _data store tables acted upon by the back-end files and dynamic textual copy_
    * **post-management:** _all post data, acted upon by rules in `**/back-end/posts`_
    * **notifications:** _all notification data, acted upon by rules in `**/back-end/notifications`_
    * **comments:** _all commenting data, acted upon by rules in `**/back-end/comments`_
    * **category-spotlight-data:** _all data related to featured content, on category pages, acted upon by rules in `**/back-end/category-spotlight`_
    * **category-pages:** _all data related to creating category pages, acted upon by rules in `**/back-end/category-page-creation`_
    * **analytics:** _all analytics computation data, acted upon by rules in `**/back-end/analytics`_
    
  * **assets:** _dynamic and static media assets store_
    * **data-assets:** _all dynamic media assets, acted upon by rules in `**/back-end` & `**/front-end/dynamic-config`_
      * **cad:** _all dynamic CAD media assets_
      * **images:** _all dynamic image media assets_
      * **gifs:** _all dynamic GIF media assets_
      * **pano:** _all dynamic panoramic media assets_
      * **sfx:** _all dynamic sound effect assets_
      * **music:** _all dynamic music media assets_
      * **video:** _all dynamic video media assets_
    * **design-assets:** _all static media assets_
      * **cad:** _all static CAD media assets_
      * **images:** _all static image media assets_
      * **gifs:** _all static GIF media assets_
      * **pano:** _all static panoramic media assets_
      * **sfx:** _all static sound effect assets_
      * **music:** _all static music media assets_
      * **video:** _all static video media assets_
      
