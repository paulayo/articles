# Build Your Own Navbar/Menu in Angular Using NG Bootstrap

This repository contains the article for creating navbar components in angular using ngbootstrap, fontawesome.

** We generate our navbar component using the angular CLI
ng g c navbar -m app.module


** Create an ensure-module-loaded-once.guard.ts in our core folder

** Use it in our core.module.ts
** Create font-awesome module in our core folder where will would import it once and export it to every part of our application that need it.


 ng g m core/font-awesome --routing false -m core.module


Extend the ensure-module-loaded-once.guard.ts in our core.module.ts, font-awesome.module.ts, ng-bootstrap.module.ts.

Ensure to add necessary imports

We also setup our NG Bootstrap module and apply the following configuration
 
ng g m core/ng-bootstrap -m core.module
ng g m core/font-awesome -m core.module

We, then add necessary imports

** After the core module setup is done, we begin the implementation of our navbar by:
1. Structure our template presentation
2. Apply Bootstrap classes to modify our template struture
3. Add native styling to visually organize our font, color, background-color and media queries
4. 
