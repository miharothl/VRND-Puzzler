# Puzzler Starter Project

This project is part of [Udacity](https://www.udacity.com "Udacity - Be in demand")'s [VR Developer Nanodegree](https://www.udacity.com/course/vr-developer-nanodegree--nd017).

## Versions
- Unity 2017.1.0
- GVR Unity SDK v1.60.0
- iTween v2.0.7


# Puzzler

As part of my coursework with Udacity, I designed tested and iterated on a
mobile VR expirience called Puazzler. In this game, players enter a gloomy
dungeon with surreal looking orbs, and are asked to solve a puzzle similar
to a simon says to move on.

Check out the ![video](https://youtu.be/pnki555tHZU)

## Process Section

# Statement of Purpose:

# Persona

for this reason I created a user persona called Bob. Bob is a x year old gamer
and has minimal expirience with VR. Bob likes playing gemas, but doesn't
allweay get the time he needs to play them. He spend most of this gaming time
on theh commute to work. He likes to solve puzzels.

[image]

## Sketches

Here are some conceptual sketches I created to lay down the design of the
project.

![Sketch](Media/sketch-01.jpg)

## User Testing

### User test 1

### User test 2

## Break down of the final piece

First I built the dungeon. I started with the front wall, built the middle
layer and the back wall.

![image-01](Media/image-01.png)
![image-02](Media/image-02.png)
![image-03](Media/image-03.png)

Then I added barrels and torches to make the dungeon look more interesting.

![image-04](Media/image-04.png)

I've added the orbs and wired them up with the game script provided by the
Udacity. I've spent quite some on setting up the lights. I pointed purple spot light 
into the orbs. I used soft shadows. For the torches I used dark orange point
lights. I made sure all the objects are static and then baked the light. The
scene in the dungeon looked a bit scary, which was cool.

![image-06](Media/image-06.png)

Then I created the UI to start and restart the game. I used canvas, put it into the world coordinates and put
the text and buttons onto it.

![image-07](Media/image-07.png)

I put the dungeon into the mountains. Once I've added the [fog](https://www.youtube.com/watch?v=TChSVtI4GEk) the scene looked
really cool. 

![image-09](Media/image-09.png)
![image-11](Media/image-11.png)

During the testing I've got complains that the torches don't have fire. I was
surprised how easy it is to create the fire in Unity. I've created the particle
system, added the fire texture, adjusted some of the settings and the fire was
there. Awesome!

![image-12](Media/image-12.png)

## Conclusion

The project was very interesting and the best thing of all was watching my
kids playing the puzzle and having fun in the VR world.

## Next Steps

In the next project we'll have to build the museum in virtual realty. For a change we are
not provided with a starter project which is a bit scary but also very cool as
we'll have to build the museum from scratch.

# Link to additional work

https://github.com/miharothl/



