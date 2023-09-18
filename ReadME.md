# FPS-Demo
A demo 3D FPS project created using Unity. 

## Description:
This is a playable demo, but note that it is still a __Work in Progress__.

I created this demo project to experiment with 3D environments, using different lighting/shader techniques, as well as using Unity Post Processing to create aesthetic environments.

## Movement:
This project is equipped with a basic FPS character controller, allowing you to explore the environment.

__Script Files__: _PlayerMovement.cs_, _PlayerMovementAdvanced.cs_

### Walking:
Controlled as usual by keys __W__, __A__, __S__, __D__.
### Sprinting:
Controlled by holding __LShift__ while holding __W__.
### Crouching:
Controlled by holding __LCtrl__.
### Jumping:
Controlled by pressing __Space__.

## Respawn:
Respawning is currently handled via collision with objects with the 'outOfBounds' layer tag. To create custom scene elements that trigger a character respawn, simply assign the 'outOfBounds' layer tag to the parent of the element.
When the player is detected to have collided and set to respawn, the player's position is set to a RespawnLocation empty object within the scene. The oject or the location of the RespawnLocation object can be customized accordingly.

__Script Files__: _RespawnManager.cs_
(Alternatively, you can alter the above file to include more layer tags or customize respawn behavior.)

## Screenshots:
### Main Room:
![image](https://github.com/VictorAuYeung/FPS-Demo/assets/69711600/5457b419-3ccb-4924-9986-9cac247f5a7f)

### Corridors:
![image](https://github.com/VictorAuYeung/FPS-Demo/assets/69711600/e518734b-6c08-4dd5-a4d0-f2611c01628c)

### Demo with Animated Objects (Ventilation):
![image](https://github.com/VictorAuYeung/FPS-Demo/assets/69711600/e97258fb-59b2-4793-94e8-05411c24bf9c)

### Interactable Objects (Collide and Affect Carts):
![image](https://github.com/VictorAuYeung/FPS-Demo/assets/69711600/3f5e53bd-3407-457f-b583-5ef2635015e2)

### Skybox:
![image](https://github.com/VictorAuYeung/FPS-Demo/assets/69711600/3a30b575-1149-4ef0-8327-26ede24d2a82)


### More Coming Soon

## Attribution:
Imported assets used are free on the Unity Asset Store.
