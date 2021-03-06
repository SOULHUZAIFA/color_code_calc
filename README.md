# Electronic Color Code Calculator excercise

## ECC Definition
SHIPCOM - EXCERCISE - The electronic color code (http://en.wikipedia.org/wiki/Electronic_color_code) is used to indicate the values or ratings of electronic components, very commonly for resistors. Write a class that implements the following interface. Feel free to include any supporting types as necessary.

## Description
This app implements an electronic color code calculator based on the information
found [here](http://en.wikipedia.org/wiki/Electronic_color_code) on Wikipedia
and the interface provided below:

```
public interface IOhmValueCalculator

{

   /// <summary>

   /// Calculates the Ohm value of a resistor based on the band colors.

   /// </summary>

   /// <param name="bandAColor">The color of the first figure of component value band.</param>

   /// <param name="bandBColor">The color of the second significant figure band.</param>

   /// <param name="bandCColor">The color of the decimal multiplier band.</param>

   /// <param name="bandDColor">The color of the tolerance value band.</param>

   int CalculateOhmValue(string bandAColor, string bandBColor, string bandCColor, string bandDColor);

}
```

## Tasks
- Write a class that implements the following interface. Feel free to include any supporting types as necessary.
- Using your favorite unit test framework, write the unit tests you feel are necessary to adequately test the code you wrote as your answer to question one.
- Create a Reactjs web interface that will allow someone to use the calculator you created in step one.
- Submit your code by a public or private repository like github, gitlab or bitbucket.

## Issues
- The above interface expects all four bands for the ohm value calculation but
  only wants a single int returned. Typically, when the fourth band (tolerance)
  is taken into consideration, a range of resistances are returned. At the
  least, two ints.

## Set Up
- Clone or download
- run in cmd in project root -npm i-

## Compile
- run in cmd in project root -npm run build-

## Run App
- run in cmd in project root -npm run start-