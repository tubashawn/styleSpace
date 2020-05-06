1.  Fonts - must include the google font api in the html file for font classes to be available
        <link href="https://fonts.googleapis.com/css2?family=Abel&family=Manrope:wght@400&family=Open+Sans&family=Roboto&family=Spartan&display=swap" rel="stylesheet">
    
    Font options are .primaryFont ('Manrope' - default font), .secondaryFont ('Open Sans'), optFont1('Spartan'), .optFont2 ('Abel'), .optFont3('Roboto')

    Font weights are .skinnyFont (300), .standardFont (400 - default weight), heavyFont(600)

2. Buttons - a simple rounded edge button with some minor hover and click effects. Colors are currently set up with variables and actual color names for classes. Working on SASS to make editing the colors even easier.

    Button styles include the default rounded edge button (.btn), and a secondary square button with a border-bottom to highlight the button (.btn-secondary). to change from default color scheme, include default class and the color scheme class you would like to change it to. Colors are added after the base class name (.btn .btn-blue). There are also inverted color schemes to swap the colors of the font and background. These are designed only for the default button style (.btn-inverted-blue).
    
