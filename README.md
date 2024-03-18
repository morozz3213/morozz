# Morozz

Morozz is a Node.js module for performing various astronomy calculations such as calculating planetary positions, determining moon phases, and predicting upcoming celestial events.

## Installation

You can install Morozz via npm: `npm install morozz`

## Usage

```javascript
const AstroCalc = require('astrocalc');

// Example usage
const date = new Date();
console.log(AstroCalc.calculatePlanetaryPositions(date));
console.log(AstroCalc.determineMoonPhase(date));
console.log(AstroCalc.predictCelestialEvents());
```



