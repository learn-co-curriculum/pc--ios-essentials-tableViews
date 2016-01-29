# Table Views

Here we go, team.  The real-deal.  The big-time.  Apps with multi-views.  The whole app world is about to open up to you.

![big time](http://i.giphy.com/iNUq5rs9KSrFm.gif)



## Objectives

1. Connect a series of view controllers with *show* segues.
2. Embed a stack of view controllers in a navigation controller.


## Segues

To allow your user to navigate between view controllers, a path between them called a **segue** (pronounced "seg-way") can be created in your storyboard. We are going to learn one of the most commonly used — the *show* segue.  

## `UINavigationController`

A navigation controller is special view controller that provides a navigation toolbar at the top of the screen and *contains and manages* a stack of view controllers. The navigation controller automatically provides a back button when there is more than one view controller in its stack.

#### *Show* Segues

Go back to the storyboard. Add a show segue between the first two view controllers in the stack: select the button which reads `Ask me the questions, Bridgekeeper.` and `control`+`drag` a line to the second view controller containing the question `What is your name?`. Select *show* in the menu that pops up and a show segue will be created between this button and the next view controller.

![](https://curriculum-content.s3.amazonaws.com/ios-segues-and-nav-controllers-unit/gorge_show_segue.png)


#### Embed in Navigation Controller

Let's put our stack of view controllers into a navigation controller. In the storyboard, select the initial view controller which is left-most in the stack and symbolized with the arrow facing into the left side of the view controller. Then in the Xcode taskbar, open the `Editor` menu, hover over the `Embed in >` sub-menu and select the `Navigation Controller` option. 

![](https://curriculum-content.s3.amazonaws.com/ios-segues-and-nav-controllers-unit/gorge_xcode_embed_navcon_menu.png)



<p data-visibility='hidden'>View <a href='https://learn.co/lessons/pc--ios-essentials-tableViews' title='Table Views'>Table Views</a> on Learn.co and start learning to code for free.</p>
