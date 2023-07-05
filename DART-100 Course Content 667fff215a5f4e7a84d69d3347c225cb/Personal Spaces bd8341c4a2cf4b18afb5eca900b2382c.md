# Personal Spaces

Exercise Format: Multiple Unique Files
Figma File: Done
ID: 11.2
Lesson: 11. Proximity
Text: Ready for Review
Type: ⚡️ Exercise
Video: File Ready

## Objective

Create an intimate portrait of your life by collaging and animating photographs of inanimate objects. 

## Exercise Instructions

### 1. Photograph some things

As you go about your day, pay attention to the spaces and objects around you. 

Is there a specific location that you find meaningful or important? How do the objects in the area reflect or document the events of everyday life? By examining the objects, we can gain insight into the daily routines, customs, and experiences of the people who lived there. We can learn about their beliefs, values, and activities. 

Take high-quality photos of objects and locations that somehow illustrate your life or identity. 

********************************Photography Tips********************************

- Turn off your flash. Natural lighting will always look more attractive and dynamic.
- Use the [rule of thirds](https://digital-photography-school.com/rule-of-thirds/). Imagine the frame is divided into thirds horizontally and vertically; by aligning points of interest at the intersections of those lines, your shots will feel slightly asymmetrical and more interesting.
- Check your focus. On a smartphone, tap an object to focus, and check the photo after you take it to ensure things are clear.
- Frame for depth. Don’t point your camera straight at a wall, but step to the side so you’re shooting *****along***** the wall. Or include bits of objects to establish a foreground, middle ground, and background (even if some things are out of focus). Think about where you can stand to best the best angle, which might mean squatting or raising your camera up high.
- Or frame from above. When photographing objects, a top-down shot can feel symmetrical, clear, and analytical — think: food shots or biological specimens. It depends on the genre and concept of your final design.
- Know your camera. The lenses on smartphone cameras are wide-angle, which means you can fit a lot of stuff in the frame. Their tiny size means that images will display a very deep [depth-of-field](https://photographylife.com/what-is-depth-of-field), which means that practically everything in the frame appears in-focus. These cameras simply can’t achieve the cinematic look of a long lens and shallow depth-of-field that screams *************professional*************  to most people. “Portrait mode” simulates this effect, but I would avoid using effects or zooming in (which you can always do later) and simply shoot with the camera as it is. If you have a camera with interchangeable lenses, you can read more about lens types online.

### 2. Import to Figma

In the Figma file for this exercise, create a new Page and label it with your name. 

Create a new Frame and start importing some of your favorite photos. The size and aspect ratio for this project is up to you, but it should be greater than 1000px in at least one dimension. 

### 3. Design a composition

Create a visually nuanced and engaging design using **at least 4 of your photos.** 

You could approach this as a kind of photo-collage, recalling the Cubist collage work we looked at in the [Texturizer](Texturizer%2049fade63cbdd4a21aebc5a1d86ccf1ed.md) exercise. 

Or you could design this an explicit “document” such as any of the following:

- A map
- A comic
- An instruction manual
- Administravia (bureaucratic paperwork)
- Anthropological research
- ???

However you approach this, emphasize the idea of **proximity** through careful placement and spacing of elements. Use closeness, distance, and alignment to convey how related things are.

### 4. Imagine a Hover Effect

Now we’re going to make your design interactive, and create animations that trigger when your mouse hovers over elements — adding in another layer of *********proximity********* in the form of the user’s cursor. 

You need to animated at least one element, but it can *just be one* if you want. 

Think about what could change in your composition: scale, color, opacity, blending modes, etc. (Animating position won’t work well because the element needs to stay in one place for users to easily hover over it.)

You can duplicate your Frame to play around with hover states if you want. 

### 5. Create a component

<aside>
📺 Video

</aside>

For one element that you intend to animate, drag it outside of your main Frame and convert it into a [Component](https://help.figma.com/hc/en-us/articles/360038662654-Guide-to-components-in-Figma). These are typically used when you have more than one instance of something (e.g. a button) that you want to maintain consistently throughout a large design file. All instances of a Component can be updated at once. 

![Component-varients.png](Personal%20Spaces%20bd8341c4a2cf4b18afb5eca900b2382c/Component-varients.png)

Add a Variant Property to your Component, and then click the purple ➕ Plus button in the main canvas to create a second Variant. 

Adjust the second Variant to achieve your desired “hover state,” that will display when users hover their cursors over it. (Just watch the video if you’re confused.)

Then switch to the Prototype panel and drag a connection from your first Variant to the second one; set this to “While hovering” and “Smart animate.” You can adjust the timing of the animation here.

Now add an “instance” of your Component back into your design — you don’t need to duplicate the Frame like we did for time-based animations, it will just work. 

But launch the prototype with the ▶️ Play button to make sure it works. 

You can add more animated Components for additional elements if desired. 

## Submission

1. In the Figma file, select “File » Save to Version History” to ensure your work is saved. You will be prompted to enter a description, so just write “Finished!” or whatever message you like. This action is automatically associated with your username so you don’t need to write your name. 
2. Get the share link for the Prototype and submit that to Canvas.