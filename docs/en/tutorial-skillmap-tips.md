# Tips for tutorials and skillmaps

A few tips that I have discovered while working with tutorials and skillmaps.

-   Test your skillmaps and tutorials in private / incognito windows. Any problems with permissions should surface this way.
-   The MakeCode servers may cache your skillmaps and tutorials. Because of that, you will need to push a new release anytime you make a change. That brings me to my next tip!
-   You *really* need to do the source code file management with a MakeCode editor. The `pxt.json` file is crucial to your tutorials and skillmaps working. If it is malformed or if something is missing, then something is bound to break.
-   Once you create the project in a MakeCode editor and push it to GitHub, then you can use any tool that you like to edit existing files (*e.g.*, Visual Studio Code).
-   To add new Markdown files, use the file explorer tool within a MakeCode editor. This will ensure that the `pxt.json` file gets updated correctly.
-   You can use another git management tool (*e.g.*, GitHub CLI, Visual Studio Code) to push assets used in your tutorials and skillmaps (*e.g.*, images) to your GitHub repo.
-   Use a MakeCode editor to push new releases of your project. Creating a release using standard git tools will not purge cached data from MakeCode's servers.
-   If a tutorial or skillmap uses custom assets (*e.g.*, background images, sprite animations, melodies), then create a separate repository to serve as an "asset pack."