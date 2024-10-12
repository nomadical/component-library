# SСD Component Library Documentation

skymind-component-library includes components to reuse around SkyCell Customer Product Apps

## Install

To use any of the helpers provided by this library:

1. Install it as an npm package. Run this command in your scene's project folder:

   ```
   npm install skymind-component-library
   ```

2. Add this line at the start of your game.ts file, or any other TypeScript files that require it:

   ```ts
   import * as magic from 'skymind-component-library'
   ```

## Usage

### < use case 1 >

To use, import some `<GenericComponent>` component from the skymind-component-library library to the entity.

<GenericComponent> requires two arguments when being constructed:

- `start`: Vector3 for the start position
- `duration`: duration (in seconds)

MyAmazingComponent can optionally also take the following argument:

- `color`: Color4 value for the color. If not provided, the default value is `Color4.Red()`

This example uses MyAmazingComponent to do `< insert use case >` to an entity over a period of 2 seconds:

```ts
import GenericComponent from 'myAmazingLibrary'


const GenericWrapper = () => {
    return <GenericComponent />;
};

export default GenericWrapper;

```

...

## Copyright info

This scene is protected with SkyCell licence.
