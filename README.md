# <ins>Website layout clone using CSS Grid and CSS Flexbox.</ins>

## <ins>The project</ins>

I was asked to copy a site layout I had been shown.

The original can be found ([here:](https://webflow.com/made-in-webflow/website/mogeektesting)) 

The original was not created using either CSS Flexbox or CSS Grid, instead it seems to be reliant on float positioning to achieve its style.

My design while aesthetically similar, does not however include the filter functionality of the original.

***
***

### <ins>CSS Flexbox:</ins>

This was used for the top banner containing links styled as buttons.

I won't lie and say it was easy, flexbox still gives me a bit of a challenge, however I believe I am slowly getting used to the declarations I need to make to manipulate both the flex-container and flex-items.

One thing I need to remember, is that flexbox is a layout best used when:
    
1. Manipulating content in a 1 dimensional format e.g. row or column.

2. It works best when you don't know the sizes of the content you intend to work with in the future, but you know there will be future content to fit.

3. It works well for creating nav/menu bars.


Styling the links into looking like buttons is not new to me as I've used a slightly more advanced version in my text game (see text-game repo here).
It was the easiest part to style for this part of the layout.

### <ins>CSS Grid:</ins>

This was used for the rest of the layout to hold the images of numbers.

I find the process of CSS Grid a lot more intuitive and straight forward.

Create the grid-container, assign columns and rows.
Follow that up with assigning track numbers to the content using grid-row-start/grid-row-end and/or grid-column-start/grid-column-end , in the place I would like it to go.

You can take an item like image number 10, which originally lined up under image number 7, and assign it a new position e.g under image number 8.

You can even span columns and rows.

***
***

## <ins>My Thoughts:</ins>

I really enjoyed this project, it was fun watching the grid-items fall into place exactly as I directed them.

I also enjoyed the fact that, while it still gives me some trouble, CSS Flexbox is getting easier to manipulate.

Going forward I will definitely be using more CSS Grid in my projects, but now it will be used in conjuction with CSS Flexbox if I need to build say a nav bar.

I would also like to learn Javascript to give my page the same level of interactiveness as the original.

<p class="codepen" data-height="300" data-default-tab="html,result" data-slug-hash="gOBNGOw" data-user="BrummieQuinn" style="height: 300px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;">
  <span>See the Pen <a href="https://codepen.io/BrummieQuinn/pen/gOBNGOw">
  CSS Flexbox and CSS Grid</a> by Gina (<a href="https://codepen.io/BrummieQuinn">@BrummieQuinn</a>)
  on <a href="https://codepen.io">CodePen</a>.</span>
</p>
