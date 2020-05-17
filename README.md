# SMOL JUICE

Unity asset that provides juicy feedbacks to improve the gamefeel of your game.

## FEATURES

### POP

Use tweens to change the scale in and out of a game object.

* IN TIME
* IN EASE
* OUT TIME
* OUT EASE
* WAIT TIME
* MODE
* SCALE
* ENABLED

### SHAKE

Shake a game object.

* TIME
* MAGNITUDE
* FADE 
* ENABLED

### FLASH

Change the color of a game object.

* COLOR
* BRIGHTNESS
* IN TIME
* WAIT TIME
* OUT TIME
* ENABLED

### SOUND 

* AUDIO CLIP
* VOLUME
* MONO
* ENABLED

## METHODS

### START JUICE

Start a selected juice.

```
SmolJuice.Start(gameObject, order);
```

* gameObject -> The game object that you want to start the juice. (NOTE THAT THIS OBJECT MUST HAVE A JUICE COMPONENT)
* order -> The order from up to down of the component in the game object's inspector. (ONLY RELATED TO OTHERS JUICE COMPONENTS) You can leave this empty if your game object only has one juice component.

### STOP JUICE

Stop a current active juice.

```
SmolJuice.Stop(gameObject);
```

* gameObject -> The game object that you want to stop the juice. (NOTE THAT THIS OBJECT MUST HAVE A JUICE COMPONENT)

## GETTING STARTED

* Add a juice component to a game object.
* Set the parameters as you like.
* Start the juice through code...
```
SmolJuice.Start(gameObject);
```
...and that's it!
