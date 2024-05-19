# js-for-react-native-11194085

TASK 4
ReadMe for Array Manipulation and User Profiles
# Student ID: 11194085
This project consists of these tasks:

1. ## arrayManipulation.js
   - This file contains two functions:
     - processArray(arr): This function takes an array of numbers as an argument and returns a new array where each even number is squared and each odd number is tripled.
     - formatArrayStrings(strArr, numArr): This function takes two arrays as arguments: an array of strings and an array of numbers processed by the processArray function. It modifies each string based on its corresponding number, capitalizing the entire string if the number is even and converting the string to lowercase if the number is odd.

2. ## userInfo.js
   - This file contains the createUserProfiles(names, modifiedNames) function, which takes an array of names and an array of modified names (from the formatArrayStrings function) as arguments. It returns an array of objects, each containing the original name, the modified name, and an auto-incremented ID starting from 1.