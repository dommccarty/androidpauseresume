# androidpauseresume
A module which reports app lifecycle events to the Javascript side. Just instantiate it, store it in Alloy.Globals, and listen to the "change" event. The event is a dictionary with five keys: onResume, onPause, onDestroy, onStart, and onStop, and the values are all either ```true``` or ```false```.
