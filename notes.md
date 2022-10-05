⇨ ⇦ ⇧ ⇩ ⏺️ ▶️ 📝

# body = The selector(Defines/targets the elements that we're applying rule to )    #Inside{}= Declaration(Property value pairs that target specific thing about element were modifying)

# Add this code to each HTML document used (Influences how box model on wepage is calculated-makes more sense when computing diff between each element )
📝html{
    box-sizing: border-box;
}

# Q: How to use fonts that have been imported/downloaded from goodle play store?

# Code📝 Meanings (CSS) 
    - color: is for font 
    - margin:0 ↦ allows view to stretch all the way to edges()
    - position: relative; ↦  allows us to nudge header elements against canvas of body in diff direcetion & set the position of childeren element of header
    - padding: rem; rem == Shorthand property to set values for the thickness of the padding area. If left is omitted, it is the same as right. If bottom is omitted it is the same as top, if right is omitted it is the same as top. The value may not be negative.
    - <ul> (unordered list items) default style is bullet points 
    - text-decoration: none; ⇨ Used to take away underline for eCommerce
    ▶️nav{}
        📝display: inline; ⇨ Makes our header (Products, About, Contact) displaty horizontal
    
    ▶️main{}
        📝margin: 1rem auto; ⇨ 'auto' allows our wepage to adapt to any viewport

    ▶️footer{}
       📝position: fixed; ⇨ Fixes it in a position no matter where you scroll on the page

# Specificity
    ⩥ Cascading stylesheets--all else being equal, further down we go between diff rules/code the more likley it will win in a fight trying to select the same property for same element
        the more specific rule, the more probable it is to be selected in conflict

• For the <nav> in CSS ⇾ To get specific with our rule set, we created a ◆'descendent selector' (choose 'child element' to reference with your rule set in CSS)