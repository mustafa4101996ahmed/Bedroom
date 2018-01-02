# Bedroom
Maya

## Introduction
For the Assignment 4 of the 3D Modelling and Animation course, I chose to animate my Bedroom. Due to certain complications I was not able to animate the bedroom as initially proposed in my Proposal, which was to animate the blanket falling onto the bed and placing itself. The main reason why this was not achieved was because it did not make sense as a random blanket fell from the ceiling. Instead, I’ve chosen to take a more realistic approach in terms of the animation itself and the lighting. My animation has been prepared using Key Frame Animations

## The Message
The message that I’ve tried to show was how the mood of the room can change with the direction of the sun, which is from a warmer feel to a cooler feel at night.

## Animation Techniques Applied
- Staging: I’ve used it to direct the user’s attention and make it clear what's of greatest importance to my scene.
- Timing: The timing of the animation simulates a day passing by from the perspective of the room.

## Lighting
For the Lighting I have used several elements:
- Physical Sun: Directional Light which projects its beams through the window cast a shadow of the window frame into the room
- Physical Sky: The Sky moves as the day progresses to show the the various colors of the sky that signify the time of the day
- Area Light: This is placed on the window and uses the portal light shader to absorb the light from the physical sky correctly and emits it as photons into the room for the Global Illumination to lighten up the room
- Point Light: 2 Point lights have been placed in the Lamps which emits photons for Global Illumination and casts shadows of the lamp cone into the room, thus lightening up the room

## Render Settings
- The initial render reset was set to Production.
- Then using Legacy Sampling, I set the Min Samples to 1 and Max Samples to 2.
- Global Illumination for the Area Light and Point Lights
- Final Gather for the Physical Sun and Sky.
- Size was set to HD540
- Individual images were rendered of various timings throughout the day to show the changes in lighting
 
