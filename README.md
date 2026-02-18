# In Class Activities
## Week 1
### Activity 1
Double check that itch.io and GitHub have properly updated when submitting any assignment. For example, open your itch.io link in an incognito tab to make sure it works.

### Activity 2
1. 10
2. 2
3. It would print "hello world" to the console every frame the program is running
4. MonoBehaviour
5. It would print "x = 10" to console at program start up
6. Argument. To send a variable into a method's parameter to allow more flexible use of methods (rather than hard coding every function)
7. You cannot directly call the class name Transform, as it isn't static. You have to call the instance variable of type Transform (_playerTransform)

### Activity 3
[Link to HW1 Notes](https://docs.google.com/document/d/1FBSt1IHePMj8a95307bpUR8aoZhdvcjZGS16ntWBc2M/edit?usp=sharing)


## Week 2
### Activity 1
![week-2-diagram](https://github.com/user-attachments/assets/8f14d8ac-e3ae-4de8-9b6a-7ebcd1861ac0)

### Activity 2
During class, I started/created all of the scripts and game objects, and put the relevant components on (most of) them. I also added the coin prefab and finished the jump logic. Here is the link to the [commit](https://github.com/UCI-GDIM32-W25/mg2-oop-review-the-elig/commit/389fd2a95e7abe81eb855e77a3a5a9c8b74d6167).


## Week 3
__Buddy Name:__ Jess
![m3-breakdown](https://github.com/user-attachments/assets/b8451815-9101-400e-8297-23c4f5fb4552)


## Week 4 (Buddy: Jess)
### Activity 1
At runtime (`Awake()`), the `Locator` script logic checks for extra instances of a `Locator` object and destroys them. This prevents multiple instances of a `Locator` object from existing, making sure it's a singleton.

### Activity 2
![week4-diagram1](https://github.com/user-attachments/assets/06921fe6-f93b-4dc9-b02d-ae6d2116cc91)
![week4-diagram2](https://github.com/user-attachments/assets/18172155-1979-4514-be94-f171723f326f)

### Activity 3
In class, I forked the GitHub repo and created the Unity project. Then I imported the sprites and formatted them correctly to be used. Then I ran to the club I'm late for :) [Link](https://github.com/the-elig/mg4-basic-game-architecture/commit/39df36baed9690386f9f2c5a69386c97f8991c09)


## Week 5
### Activity 1
The class design is functional. As it were, this would probably be about how I did it based on my previous experience with OOP. However, since I am less familiar with interfaces, I would probably only create an abstract `Item` class with abstract methods for all items, especially since this project was so small. 

### Activty 2
Model: `ScriptableObjects`
View: `DialogueBubble` and `InventoryUI`
Controller: `EnemyClass` and `PlayerClass`

### Activity 3 (scenario 1: rhythm game)
- each beat should be a prefab (so it has a `Transform` and a sprite) with a `ScriptableObject` for the data associated with it (key, final location, etc.)
- in addition, each beat type would have a script dictating its movement/speed (in an abstract `Beat` class with different beat types as its children)
- `HitNote()` event, so we should probably have a singleton

### Activity 4
Jasmine Caicedo, Giovanni Solorio, and Eli Gutierrez's
[Project Proposal](https://docs.google.com/document/d/1GxlGKB6HPG_Q6x96TOvyybNU5x_lLUS-DKCN9NGH8AQ/edit?usp=sharing)


## Week 6
### Activity 1
- `Gizmos` can be used to visualize player collision with other objects, which can be useful for checking interaction distance
- breakpoints are great for quick, clear debugging. `Debug.Log()` can be a bit tedious, especially if you aren't sure what you are checking for
- much easier to visualize going through the code with breakpoints rather than having a print out in every function to see if it triggers when it should
- document the code you write, good in general, and for merge conflicts

### Activity 2
Jasmine Caicedo, Giovanni Solorio, and Eli Gutierrez's
[Final Project Proposal](https://docs.google.com/document/d/1GxlGKB6HPG_Q6x96TOvyybNU5x_lLUS-DKCN9NGH8AQ/edit?usp=sharing)


## Week 7
### Activity 1
- Finite State Machine useful for keeping track of duck's behavior patterns (mutually exclusive movement: wander and pursue)
- `Gizmos` (for visualization) combined with `Raycasting` (for logic) is super useful for tracking aggro
- `Physics.Raycast()` returns a boolean value (true/false) depending on whether it hits something

### Activity 2 & 3
Jasmine Caicedo, Giovanni Solorio, and Eli Gutierrez's Project Breakdown
![week7-diagram](https://github.com/user-attachments/assets/109790dd-058c-4d07-8c91-1b22447dc22e)

### Activity 4
[Project Assignments](https://docs.google.com/document/d/1sehPNIdyI6lp60o5EtXhbFXRd0Idz6kQugv0XU2nbt0/edit?usp=sharing)

### Activity 5
I started and [completed 3D player movement](https://github.com/the-elig/GDIM32-Final/commit/001c69900cb39dcce9a7c96e1553cf3364b13014), which included creating the game object, the script, and working the camera. 
