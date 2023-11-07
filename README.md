# Unity-Scriptable-Object-Event-System
A system for creating events as Scriptable Objects, Creating them from the asset menu, and managing Actions when event is raised via Components.

Package includes  the scripts to create, raise, and listen for Game Events createable through the Unity Create Menu and create Unity Action
responses through the inspector. This is intended for easier management of events, the creation of interactions without having to create
a unique script for a simple action, and for scripts that may need to reference the same event to be fully decoupled.

The InspectorButtonAttribute script allows for the creation of a debug button in the inspector to raise the event
from within the inspector for testing.

1. Right click and create the event that will be used using the "Game Event" Object.
2. Place the "EventRaiser" Script on  the object in the scene that will raise the event and place the event(s)
   that will be raised into the list.
3. Place the "EventListener" Script on the object that will respond to the method call and setup the recquired responses.

