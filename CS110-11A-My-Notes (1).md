# CS110 Action 11A — My seminar and engine experiment

Learner / folder: [add your name or approved identifier]
Engine route: unity
Work mode: solo
My personal repository / one Canvas submission link: https://github.com/miomio08/11A---Mio
Team repository: Working solo — no team repository required

## GitHub checks before and after work

Before work: I checked my local project and GitHub repository and confirmed they were connected and up to date.
Personal repository URL: https://github.com/miomio08/11A---Mio I checked that my files, images, and links were accessible.
Worked solo: I worked solo and used my personal repository.

## 1. Our Attention Accord — shared plan/reference

n/a

## My personal attention brief

I will investigate: How C# scripts control objects and behaviors in Godot.
I need to understand: How properties and methods create visible changes in the game.
I will capture: My code, screenshots, tests, and results.
I will return with: Three working behaviors and one extension.
My evidence will be saved at: 11A/Evidence/Whiteboard/
How this helps our team build: It helps me understand how to use C# in Godot and build better game behaviors.

## 2. My seminar notes

[Not recorded yet — complete this section.]

## My host translation

Engine/version/language: Godot 4.7.2 .NET / C#
Familiar C# idea -> engine equivalent: C# class/method -> Godot node script and callbacks
Who calls initialization and repeated updates?: Godot calls _Ready() once when the node is ready, and _Process() repeatedly every frame.
One discovery I shared with the team: Godot automatically calls _Ready() for initialization and _Process() every frame, so the engine controls when those methods run.

## 3. My individual base

My source files/scene: Main.tscn with Node2D → Player (Sprite2D) and Player.cs.
Starting values and prediction: Player starts at (400, 300). I predicted it would move left/right, spin, and change color.
Actual movement/rotation/color result: The Player moved left and right, continuously rotated, and changed color between blue/purple shades.
The class/property/method responsible: The Player class controls the Sprite2D. Position controls movement, Rotation controls spinning, Modulate controls color, and _Process() updates them repeatedly.
Frustration or error, and how I investigated: The Player initially appeared in the corner and did not bounce correctly. I checked the scene, texture, script, and movement code, then fixed the position and movement code and tested it again.

## 4. My experiment and return to the team

My question/prediction: How can I change the basic behavior to make the Player move continuously while also rotating and changing color?
Change beyond the base: I added automatic left-and-right movement as an extension.
Observed result or exact error/next step: The Player moved, rotated, and changed color. I had a C# double to float error, so I added an explicit cast and tested it again.
Prefab or saved scene and two-instance comparison: I used a saved Main.tscn scene with one Player instance. I did not make a second instance.
What I promised -> What I actually returned: I promised to investigate how C# controls Godot objects and return working behaviors. I returned a working Player with movement, rotation, color change, and an extension.

## Source and evidence

[Link my project, scene, whiteboard screenshots/photos, base/extension evidence and checked source. All my authored work belongs in this personal repository.]

My individual engine base status: [working / blocked — explain].
My individual extension status: [result / error and next step].
Help received: [describe].

Commit and push all my authored work, including board captures, notes, project and evidence, to my personal repository. Open the pushed files/images and test the personal URL and applicable team URL/member links. Submit the one personal repository URL in Canvas; this README contains the team link if applicable. This export is not Canvas submission.
