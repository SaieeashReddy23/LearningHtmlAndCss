display : grid :-

        -> the container of the grid items should begiven this property

-> grid-template-columns and grid-template rows :

        -> these are used to structure the rows and columns of the grid . if the value is not mentioned then they will be Auto by default means they expand to fill the container space.

        -> grid-template-rows : 1fr 1fr 2fr

        -> fr are fraction units used in grid and they are the most popularly used.

-> gap-column , gap-row :-

        -> these properties are used to keep gap between rows and columns

-> grid-column , grid-row :-

        -> these are used in the grid child item to make it expand more than 1 column and row

        -> grid-column = 1/3   => here 1 nad 3 are the grid lines . it means this element will expand along the column side from column 1 to column 3

-> grid line names :-

        -> grid-template-columns : [start] 100px 100px [end] 100px

-> grid-template-areas :-

        -> for each item we will give it a name and using that name we will create the grid template structure

        -> grid-area : itemName  for each item we can use this to se the area name.

        -> grid-template-areas :

          "a a b"
          "a a b"
          "c c b"
          "d d d"
          "e f f

-> order property :-

        -> this is used on the items in the grid . if order value is given less value then it will be placed at the beginning . if given higher value then  placed at end.

        ->

-> repeat :-

        -> this is used instaed of typing the values multiple times.

-> justify-content and align-content :-

        -> all the items vertically or horzontally align

-> align-items and justify-items :-

        -> all the content inside the item. vertically or horizontally aligned.

-> align-self and justify-self :-

        -> to control the item content. these properties are used inside the grid cell.
