# Crestron-Fonts
Vectorizing of several crestron Style Icons, and conversion in to Fonts for web development
    <div>
        <p>Similar to <a href="https://www.w3schools.com/icons/fontawesome_icons_intro.asp">FontAwesome,</a> Creston Neo, creates fonts out of the Crestron Neo Style</p>
        Follow the same guidelines in the link.  Just change any reference for fa to crf, and fa- to crneo-. You will be able to:  <br>
        <ul>
            <li>
                Add an icon into your project and make them any size any color:
            </li>
            <li>
                Make them rotate:
            </li>
            <li>Spin Them:</i></li>
            <li>
                Stack Them Together to make new ones!
            </li>
        </ul>
        Inspect this demo.html, and the sytle.css for extra styles to help you make the icons show here.
    </div>
    
How to Use:

On you initialized yarn/npm project, run
    
    
This will install the fonts in the node_modules folder. The imortant folders are structure is:
node_modules
```|---ay-crestron-fonts
    |---css
    |   |---crestronfonts.css
    |   |---neo.css
    |---webfonts
    |---demo.html```

The CSS folder contains the CSS styles to call the fonts in webfont by name instead of code, and important style for the stacking, animation, etc.
The webonts, is where the core vector fonts in several formats are located
demo.html can be run (by right clicking in visual studio and Opening in <a href="https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer">Live Server</a> (it must be installed) where all the fonts and examples can be seend.

To install simple add these two lines to your index.html, or appropiate location in any of the js frameworks
```  <link rel="stylesheet" href="./node_modules/ay-crestron-fonts/css/crestronfonts.css">
     <link rel="stylesheet" href="./node_modules/ay-crestron-fonts/css/neo.css">```
