
# EXP 04 - RIFLE-BULLET SPAWN

## AIM:

To Attach Rifle with character mesh and implementation bullet spawn from Rifle.

## PROCEDURE:

1. Import the character mesh and rifle model into your game engine or development environment. Ensure that both assets are properly rigged and prepared for animation.

2. Create an attachment point on the character's hand or shoulder where the rifle will be attached. This can be achieved by adding a socket or bone to the character's skeleton.

3. Attach the rifle model to the character's attachment point using the appropriate parenting or socketing mechanism provided by your game engine. This will ensure that the rifle follows the character's movements and animations correctly.

4. Implement the logic for bullet spawning. You'll need to determine the position and direction from which the bullets should be spawned based on the rifle's barrel. Usually, this involves creating a spawn point on the rifle model, such as the barrel tip.

5. When the player triggers the shooting action (e.g., pressing a button or clicking the mouse), instantiate a bullet object at the spawn point you determined in the previous step. The bullet object should have its own movement and collision logic.

6. Set the initial velocity and direction of the bullet based on the rifle's orientation and any additional factors you want to consider, such as recoil or spread.

7. Continue updating the bullet's position and check for collisions or other interactions until
it reaches its target or goes out of bounds. Handle any necessary effects or damage calculations upon collision.

8. Repeat the bullet spawning process as needed whenever the player triggers the shooting action.

### TO IMPLEMENT SCORE WEIGHT:

1. Create a score variable: Declare a variable to keep track of the player's score. For example, you can initialize it to zero at the beginning of the game.

2. Detect bullet-object collision: Implement a collision detection system to detect when a bullet collides with an object. This can vary depending on the game engine or framework you are using. Typically, you would check for collisions between the bullet and the object using their respective collision shapes or bounding boxes.

3. Handle collision events: When a collision between a bullet and an object is detected, trigger a collision event or callback function. This function will be responsible for handling the specific actions associated with the collision.

4. Increase the score: Inside the collision event function, increment the score variable by a
certain amount. For example, you can add one point to the score every time a bullet hits an object.

5. Update the score widget: After increasing the score, update the score widget to display
the updated score value. This can be done by accessing the score widget element or object and setting its text or value to the updated score variable.

6. Display the score widget: Ensure that the score widget is visible to the player during gameplay. This might involve placing it in a prominent position on the screen or integrating it into the game's user interface (UI) system.

7. Repeat the process: Repeat steps 2 to 6 for each object that the player can interact with
or shoot at. Whenever a bullet collides with an object, increase the score and update the score widget accordingly.

8.  Optional: Add visual and audio feedback: To enhance the player's experience, you can consider adding visual and audio feedback when a bullet hits an object. For example, you might display a particle effect or play a sound effect to signify a successful hit


## OUTPUT:

### GUN:
![242312096-0fcba2f8-52e4-4374-b59f-2165846c6858](https://github.com/BHUVANESHWAR-BHUVIOP/RIFLE-BULLET-SPAWN/assets/94155099/26fcbecb-8d89-446f-ba99-8531fc817ba2)

### GUNACTOR:
![242315601-2bd0f7c5-b0cc-46e6-9cd4-96dffc0b4045](https://github.com/BHUVANESHWAR-BHUVIOP/RIFLE-BULLET-SPAWN/assets/94155099/ff6b23cf-8372-46a1-b01d-5eaf01cec277)

### BULLETACTOR:
![242315843-2c8fa646-257d-4acc-bb12-5fdb8bc2e590](https://github.com/BHUVANESHWAR-BHUVIOP/RIFLE-BULLET-SPAWN/assets/94155099/d1f22843-2cf6-4fe3-a411-d4292a12267d)


###  BLUEPRINTS FOR GUN SPAWN AND BULLET SPAWN:

![242316260-8ac82ecb-bb16-4e9f-b647-699af419325c](https://github.com/BHUVANESHWAR-BHUVIOP/RIFLE-BULLET-SPAWN/assets/94155099/2a83ced7-b995-4dd0-8bd9-29ae2f6ce13d)

![242316671-7a70f0e3-b7d1-4d02-b9ec-830d515f822f](https://github.com/BHUVANESHWAR-BHUVIOP/RIFLE-BULLET-SPAWN/assets/94155099/20e89729-bde1-4ee2-ba02-0202e5543eb4)

![242317352-47c681db-cf9b-46da-ac01-113aae3ca8c7](https://github.com/BHUVANESHWAR-BHUVIOP/RIFLE-BULLET-SPAWN/assets/94155099/ed7eccc4-b2d3-46fa-acd5-6f31fe4b0f83)

![242317619-4ac62e9c-cc77-468c-a363-2d32422ec77c](https://github.com/BHUVANESHWAR-BHUVIOP/RIFLE-BULLET-SPAWN/assets/94155099/c64ef28c-3c91-42e4-9481-5dec505ed2e0)


RESULT:
To Attach Rifle with character mesh and implementation bullet spawn from Rifle is implemented successfully
