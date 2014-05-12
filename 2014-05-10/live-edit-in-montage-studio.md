(Real Time) Live Edit in Montage Studio
===========================

Montage Studio offers a preview of the application you are building or editing with (real time) Live Edit capabilities.
Unlike other products that just offer you live reload of resources, the Live Edit features of the preview allow you to see the changes at the same time you make them.
There's no need for save and the changes also apply to dynamic parts of your application.

In this blog post I'm going to show different scenarios where the Live Edit feature works its magic.

Component Changes
-----------------

The best way to understand how real time live edition is considerably better than live reload is to edit the flow component of Popcorn. You can immediately get a felling of how your changes impact the application. You don't even need to learn how this advanced component works, you can just _see_ how it works.
<video src="popcorn-flow-edit-3.mp4">

You can also connect as many clients as you want to the preview and see how your changes impact several different devices at once, in real time.
In the next video you can see how many letters you can fit (or can't) into the Category Button on all three different devices at once.
<video src="popcorn-multiple-category-3.mp4">

Structural Changes
------------------

While performing editions and see them in real time is great the Live Edit is not limited to changes of existing components.
You can also change the structure of your application by adding and removing components and the Live Edit will follow in real time.
<video src="todo-add-button-label.mp4">

When you change a component all instances of that component in the preview will update to reflect your new changes.
<video src="todo-add-multiple-components.mp4">

This is not limited to the components you explicitly declared in your application but also to components that are dynamically created by the repetition.
<video src="todo-add-component-repetition.mp4">

A typical scenerio when editing your application is to make changes to components that are not always visible. Quite often you have components that are only visible in certain states of your application. Sometimes these states are not easy to get into, they require several taps or clicks to put the application into that particular state.
Under this scenario classic application development forces you into the cycle of:

 1. Change
 2. Save
 3. Reload
 4. Perform operations to put app into desired state
 5. Repeat from point 1

This can be very time consuming, specially if you have to repeat this for every device you need to test your application with.
With real time Live Edit it can be shorten to:

 1. Perform operations to put app into desired state
 2. Change * (times needed)

This way you can focus on what is really important for you as an application developer: changing the application until it fits your needs.

In the next video I'm editing the FriendDetail component to add more fields to it and a bit of styling. I can see my changes immediataly without having to reload the application and following the initial steps to see the FriendDetail component on the screen.
<video src="state-change-component.mp4">

Style Changes
-------------

Real time edition of CSS stylesheets is also supported and you don't need to constantly hit save just to see them being applied.

<video src="todo-update-css.mp4">

The main goal of real time Live Edit is to increase the time the developer spends on making the application the way it wants to.
This is acomplished by reducing all repetitive tasks not strictly related to the developers goal: creating an application.

At Montage Studio we believe that real time feedback is the key to speed up development time as it reduces the change / see change cycle to a single task: change.
