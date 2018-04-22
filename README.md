# css-grid-layout
TeamTreehouse/Tracks/Web Design

:::::::::::::::::::::::::::::CSS GRID LAYOUT:::::::::::::::::::::::::

About this Course:

CSS Grid Layout provides a built-in, more efficient way of designing grid-based layouts in the browser. It brings a new set of properties, functions and flexible units that let you control the exact placement and sizing of grid components.

What you'll learn:
1. Declaring row and column tracks
2. Setting gutters between rows and columns
3. Creating flexible and responsive grid layouts without media queries
4. Using Grid with Flexbox

:::::Introducing Grid Layout:::::
Grid Layout provides a set of properties, functions and flexible units that let you control the sizing, positioning and spacing of content. You can build layouts faster and more easily than any layout tools you've relied on in the past.

->Understanding Grid:
CSS Grid Layout lets you simplify your HTML, so you can write simpler markup and rely just on CSS to control your page's design.

Resources:
1. https://gridbyexample.com/
2. http://labs.jensimmons.com/
3. https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout
4. https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout/Relationship_of_Grid_Layout

->Grid Concepts and Terminology:
Before you begin building layouts with CSS Grid, you should understand some of the concepts and terminology behind it.

Resources:
1. https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout/Basic_Concepts_of_Grid_Layout#The_Grid_container
2. https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout/Basic_Concepts_of_Grid_Layout#Grid_Lines
3. https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout/Basic_Concepts_of_Grid_Layout

->Defining a Grid:
Now that you know the basic concepts and terminology behind CSS Grid layout, you're ready to learn the first steps in creating a Grid: defining the grid container and setting up columns.

Resources:
1. https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout/Basic_Concepts_of_Grid_Layout#Grid_Tracks
2. https://developer.mozilla.org/en-US/docs/Glossary/Grid
3. https://developer.mozilla.org/en-US/docs/Web/CSS/grid-template-columns

->Setting Grid Rows:
You can control how much vertical space a row takes up by defining row tracks. The grid-template-rows property creates rows in your grid.

Resources:
1. https://developer.mozilla.org/en-US/docs/Web/CSS/grid-template-rows
2. https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout/Auto-placement_in_CSS_Grid_Layout#Anonymous_grid_items

->Introducing fr, a Flexible CSS Length Unit: 
Grid layout introduces a new length unit, fr (or fraction), a flexible unit designed for creating grid tracks that expand and contract based on the free space in the grid.

Resources:
1. https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout/Basic_Concepts_of_Grid_Layout#The_fr_Unit
2. https://css-tricks.com/introduction-fr-css-unit/

->Set Tracks with repeat() Notation:
The CSS Grid repeat() function saves you time and helps keep your CSS maintainable. repeat() offers a shortcut for repeating patterns of tracks, which keeps you from having to write the same values over and over again.

Resources:
1. https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout/Basic_Concepts_of_Grid_Layout#Track_listings_with_repeat()_notation
2. https://developer.mozilla.org/en-US/docs/Web/CSS/repeat

->Flexible Track Sizing with minmax():
One of the most useful features in Grid Layout is the minmax() function. minmax() lets you set a grid track's minimum and maximum size.

Resources: 
1. https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout/Basic_Concepts_of_Grid_Layout#Track_sizing_and_minmax()
2. https://developer.mozilla.org/en-US/docs/Web/CSS/minmax

->Repeat Tracks with auto-fill and auto-fit:
Grid layout lets you set items to automatically wrap and adjust to fit their container's width. This lets you create designs that respond to different browser widths. The Grid Layout repeat notation supports two keywords -- auto-fill and auto-fit -- to help with this.

Resources:
1. https://developer.mozilla.org/en-US/docs/Web/CSS/repeat#Values

->The Explicit and Implicit Grid:
When you create a grid layout with the grid-template-rows and grid-template-columns properties, you are defining what's called an "explicit grid". What happens if there are too many grid items to fit inside the grid you defined? To handle this uncertainty, Grid Layout provides an "implicit grid." The implicit grid is automatically generated by the grid container to position any extra items outside of the explicit grid.

Resources:
1. https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout/Basic_Concepts_of_Grid_Layout#The_implicit_and_explicit_grid
2. https://css-tricks.com/difference-explicit-implicit-grids/

->Control the Auto-placement of Grid Items:
Knowing why and how implicit grid tracks are created is important when working with grid layout. You might not always know exactly how many items will be in your grid container. What if you need to size or position implicit tracks a certain way? That could get tricky, because there could be any number of implicit tracks.

Resources:
1. https://developer.mozilla.org/en-US/docs/Web/CSS/grid-auto-rows
2. https://developer.mozilla.org/en-US/docs/Web/CSS/grid-auto-columns
3. https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout/Basic_Concepts_of_Grid_Layout#The_implicit_and_explicit_grid

->Firefox Grid Inspector Tool:
The Firefox web browser provides a helpful tool that lets you visualize, inspect and debug your grid layout in the browser. The Grid inspector tool overlays a representation of the grid on top of your grid container. That way you're able to inspect your grid tracks, grid lines, gutters and more.

Resources:
1. https://developer.mozilla.org/en-US/docs/Tools/Page_Inspector/How_to/Examine_grid_layouts
2. https://www.mozilla.org/en-US/firefox/channel/desktop/#nightly
3. https://developer.mozilla.org/en-US/Firefox/Developer_Edition
4. https://bugs.chromium.org/p/chromium/issues/detail?id=728062

->Position Items by Grid Lines:
CSS Grid lets you exercise even greater control by specifying the placement of individual grid items. You can use grid line numbers to control how items are placed, by applying properties directly to a grid item. This gives you precise control over grid item placement, size and order.

Resources:
1. https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout/Basic_Concepts_of_Grid_Layout#Positioning_items_against_lines
2. https://developer.mozilla.org/en-US/docs/Web/CSS/grid-row-start
3. https://developer.mozilla.org/en-US/docs/Web/CSS/grid-row-end
4. https://developer.mozilla.org/en-US/docs/Web/CSS/grid-column-start
5. https://developer.mozilla.org/en-US/docs/Web/CSS/grid-column-end
6. https://developer.mozilla.org/en-US/docs/Web/CSS/length#Viewport-percentage_lengths

->Negative Grid Lines and Shorthand Syntax:
Grid lines also have negative indexes. You can reference grid lines starting from the far right or bottom edges of the grid, using negative line numbers. In this video, you'll learn more line placement tips and a shorthand syntax for positioning items by line number.

Resources:
1. https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout/Line-based_Placement_with_CSS_Grid#Counting_backwards
2. https://developer.mozilla.org/en-US/docs/Web/CSS/grid-row
3. https://developer.mozilla.org/en-US/docs/Web/CSS/grid-column
4. https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout/Line-based_Placement_with_CSS_Grid
5. https://alligator.io/css/css-grid-layout-span-keyword/
6. https://www.sitepoint.com/seven-ways-you-can-place-elements-using-css-grid-layout/

->Placing Elements Using Grid Template Areas:
CSS Grid provides a feature that lets you create named grid areas, then you use those names to position items on the grid. First, you'll use the grid-area property to assign a custom name to each grid area. Then you'll use the grid-template-areas property to define how the layout looks, by referencing those custom named areas.

Resources:
1. https://developer.mozilla.org/en-US/docs/Glossary/Grid_areas
2. https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout/Grid_Template_Areas
3. https://developer.mozilla.org/en-US/docs/Web/CSS/grid-area
4. https://developer.mozilla.org/en-US/docs/Web/CSS/grid-template-areas

->Adjust the Grid with Media Queries:
Learn how grid template areas make adjusting your layout at different breakpoints quick and easy.

->Using Grid with Flexbox3:
CSS Grid is not meant to replace Flexbox. Flexbox and Grid are complementary layout tools, and each have their specialties.

Resources:
1. https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout/Relationship_of_Grid_Layout#Grid_and_flexbox
2. https://css-tricks.com/css-grid-replace-flexbox/
3. https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout
4. https://rachelandrew.co.uk/css/cheatsheets/grid-fallbacks
5. https://twitter.com/guilh/status/870706512364060672





