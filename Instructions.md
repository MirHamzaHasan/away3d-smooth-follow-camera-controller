# Introduction #
Quick how to guide.

# Details #

Create the controller, and set the camera property.

cameraController = new CharacterFollowController(camera, null);

After the model is loaded, set the controller target.

cameraController.lookAtObject=character.ghostObject.skin;

In your loop, call the update function.

cameraController.update();