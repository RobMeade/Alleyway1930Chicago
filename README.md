# Alleyway, 1930s Chicago
This project focused on creating a set of modular 3D assets to create an environment using Unreal Engine.  I shortlisted a few ideas before finally deciding on an alleyway at night.  To add some focus and specifics, I decided I set the scene in Chicago in the 1930s, somewhat inspired by the Road to Perdition movie.

## Research
Quite extensive research was carried out for this project.  Whilst gathering images for moodboards I came across one of a fire escape, I was able to reach out to the professional photographer who had taken it.  He kindly sent me additional copies, in their original raw format and also in a larger size.  This enabled me to really zoom in on the detail on the fire escape.

I wanted to add some form of dumpster in the alleyway so began researching American dumpsters and read about the history of the Dempster Dumpster.  With further research I made contact with the grandson of George Dempster who was able to provide me with schematics of various models, but importantly, this carried with it dimension information which was of huge benefit whilst modelling.

For the scale of the environment itself I turned my attention to Chicago's Municipal Code, I was able to look back through older versions and revision history.  With a lot of time I was able to find all manner of information from the minimum widths of alleyways, dimensions for windows that would be used as fire escapes, their height from the floor, dimensions for fire escapes, including step width, height and so much more.

The research side of this project was really interesting and it made creating models to scale a lot easier.

When considering props for the scene I against spent time researching those specific areas, for example, the breweries that were in Chicago at that time.  The dimensions of the beer bottles in use, the dimensions of the crates that the beer bottles were stored in (I was able to get some of that information from eBay!).  

Moodboards were created for the theme, props and environment assets.

## Development
Using the site plan and front elevations I was able to start greyboxing the environment.  The UE4 mannequin model was added in various places within the scene to maintain a scale reference.  The greyboxing took several iterations.

I began modelling the larger assets first, this included the buildings, and then their components such as the doors, shutters, and windows.  Variations of several assets were created to provide variety and break up any repetitive patterns.  The fire escape asset was created next, as it was a little more complicated being made of multiple components.  Finally the smaller prop assets like bottles, crate, tarps, trash cans, and vents were created.

The assets were imported in to Unreal Engine (4.22), replacing their placeholders.  The scene was iterated over several times, adding and moving props until it began to feel right.

Lighting, volumetric fog, and post processing also took many iterations.  Having removed faces from the 3D models that were not necessary, I found then that light-bleed became an issue and needed to resolve that by adding simple primitives to block the light.  In hindsight, choosing a scene at night for my first environment project was, not the best idea.  Too dark, too light, too dark, too light, it was quite frustrating.  Whilst it was a good learning process, it did consume a lot of time, and unveiled just how much I didn't know.

There is much that could still be done with this scene to improve it, modelling, texturing, and lighting are not my strongest areas, but I learnt a lot by working on this project which was my original aim.

## Camera Work
In order to take iterative screenshots from the same points throughout the development I added a series of cameras to the level.  I added some simple code in Blueprint that would enable me to press keyboard numbers 1, 2, 3, or 4 and change the view to the specific camera.  As the cameras were persistant, I was able to take screenshots from the exact same location each time, which helped to demonstrate the progress I had made.

## Moodboards

Fencing<br/>
![Fencing Moodboard](/Images/Fencing-Moodboard.jpg)

Crates and Bottles<br/>
![Crates and Bottles Moodboard](/Images/CratesAndBottles-Moodboard.jpg)

## Plans

Site Plan and Front Elevations<br/>
![Site Plan and Front Elevations](/Images/SitePlanAndFrontElevations.jpg)

## Iterative Screenshots

Environment<br/>
![Environment Iterations](/Images/Screenshots-Environment.jpg)

Lighting<br/>
![Lighting Iterations](/Images/Screenshots-Lighting.jpg)

## Beauty Shots

Finished Scene<br/>
![Beauty Shots](/Images/BeautyShots.jpg)

## Asset List

### Environment

- Arch
- Building (variant A)
- Building (variant B)
- Building (variant C)
- Building (variant D)
- Building (variant E)
- Building (variant F)
- Building buttress
- Door (building C)
- Door (building F)
- Double doors (building D)
- Fence panel (variant A)
- Fence panel (variant B)
- Fence panel (variant C)
- Fence panel (variant D)
- Fence post
- Fire escape
- Metal shutter (right)
- Metal shutter (left)
- Quoin base
- Ramp
- Step
- Window sill (variant A)
- Window sill (tvariant B)
- Window sill (variant C)
- Window (variant A)
- Window (variant B)
- Window (variant C)
- Window bars (window A)
- Window bricked up (window A)

### Props

- Crate stack with tarp (variant A)
- Crate stack with tarp (variant C)
- Crate (tvariant A)
- Crate stack (variant A)
- Crate stack (variant B)
- Crate stack (variant C)
- Dempster Dumpster
- External light fixture (variant A)
- External light fixture (variant B)
- Steinie bottle 12oz
- Trash can
- Trash can lid
- Vent