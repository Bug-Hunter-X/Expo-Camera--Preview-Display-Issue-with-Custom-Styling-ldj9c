# Expo Camera Preview Issue

This repository demonstrates a bug where the Expo Camera component's preview fails to display correctly when certain styling is applied. The preview may appear blank or show distorted images.

## Bug Description

The problem arises from interactions between the `Camera` component's dimensions and its surrounding layout.  Incorrect `flex` styles or improperly specified dimensions prevent the camera preview from rendering properly. 

## How to Reproduce

1. Clone this repository.
2. Run `npm install`.
3. Run `expo start`.
4. Observe the distorted or missing camera preview in the app.

## Solution

The solution involves carefully setting the dimensions and flexbox styles for the camera component and its container to ensure proper rendering. The corrected code is provided in `bugSolution.js`.

## Technologies Used

* Expo
* React Native