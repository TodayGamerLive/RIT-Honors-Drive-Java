RIT-Honors-Drive-Java
=====================

Java version of the RIT Honors Drive Program.

So far the program has the following capabilities:
* Authenticate into drive
* List the contents of any folder (recursive)

I know it's not much, but it's a start.


Setup Instructions
------------------

* There are a lot of things you need to add to eclipse:
  1 Eclipse Web Tools (WTP):  http://download.eclipse.org/releases/kepler/
    * From there I got:
      * JavaScript Dev Tools
      * WST Common Core
      * WST Server Core
      * WST XML Core
    * There are also some JSF plugins that we may want to look into if we go down that route for templating
  2 Google App Engine Java SDK: https://dl.google.com/eclipse/plugin/4.3 
  3 Google Plugin for Eclipse: https://dl.google.com/eclipse/plugin/4.3
  4 Google Web Toolkit
    * This is like the JSF, we may not actually end up using it
  5 m2e - Maven Integration for Eclipse: http://download.eclipse.org/technology/m2e/releases
    * Maven is BEAUTIFUL  I didn't really appreciate it before, but it allows you to set up all the dependencies and libraries for a project.  So when I needed to add the gson library, I added an entry to it and it automatically downloaded/configured it!
  6 egit:  http://download.eclipse.org/releases/kepler
    * I'm not sure I have thie 100% correctly set up for github, but it should be helpful
* It is my understanding that the launch configurations will be transferred with the project.  There should be ones to launch the dev server using google and using maven, and one to deploy to GAE using maven.
* The "Google" menu should also allow you to deploy.  But since the local testing does work, you shouldn't need to do that super frequently.
* Hopefully all you'll need to do is import the project into eclipse (fingers crossed!)
