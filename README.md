# Window Info

Native module for OSX and Windows to get information about application windows running on a system.

## API

#### `listWindows(): Array<Window>`

Returns a list of all windows open on the system.

#### `windowRect(window: Window): Rect`

Returns the position and dimensions of a given window.

#### `windowTitle(window: Window): string | null`

Returns the title of a given window, otherwise `null`.

#### `isWindowFullScreen(window: Window): boolean`

Returns a boolean determining if a window is full screen.

## Don't like my code?

Make a fuckin' PR then...
