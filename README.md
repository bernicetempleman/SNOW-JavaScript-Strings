# SNOW-JavaScript-Strings
- JavaScript strings are used for storing and manipulating text.
- A JavaScript string is zero or more characters written inside quotes.
- You can use single or double quotes
![image](https://user-images.githubusercontent.com/12488769/148701152-04a2c76d-2e5e-4e57-b5cd-586885016be6.png)

- You can use quotes inside a string, as long as they don't match the quotes surrounding the string
![image](https://user-images.githubusercontent.com/12488769/148701156-cf0cef17-0143-4fb8-82e8-a1530b050254.png)

## String length
To find the length of a string, use the built-in length property
![image](https://user-images.githubusercontent.com/12488769/148701190-ba2808d4-a14c-4aa3-96fb-8676745087b0.png)

## Strings can be objects
- JavaScript strings are primitive values, created from literals:
let firstName = "John";
- But strings can also be defined as objects with the keyword new:
let firstName = new String("John");

# JavaScript String Methods
## Extracting parts of strings
### There are 3 methods for extracting a part of a string:
- slice(start, end)
- substring(start, end)
- substr(start, length)

## slice
slice() extracts a part of a string and returns the extracted part in a new string.
The method takes 2 parameters: the start position, and the end position (end not included).

JavaScript counts positions from zero. First position is 0.
If a parameter is negative, the position is counted from the end of the string.
If you omit the second parameter, the method will slice out the rest of the string

## substring()
- substring() is similar to slice().
The difference is that substring() cannot accept negative indexes.
If you omit the second parameter, substring() will slice out the rest of the string

## substr()
substr() is similar to slice().
The difference is that the second parameter specifies the length of the extracted part.
If you omit the second parameter, substr() will slice out the rest of the string.
If the first parameter is negative, the position counts from the end of the string.

## replace string content
![image](https://user-images.githubusercontent.com/12488769/148701301-b1cef3b8-6105-4d85-8f2f-525beccd56d4.png)

![image](https://user-images.githubusercontent.com/12488769/148701321-ebe6b116-a83c-4ff7-b871-25363d8b1355.png)

![image](https://user-images.githubusercontent.com/12488769/148701327-f80861fe-789b-486e-96e6-31b884ebd90c.png)

## Converting to Upper and Lower case
A string is converted to upper case with toUpperCase()
A string is converted to lower case with toLowerCase()
concat() joins two or more strings
The trim() method removes whitespace from both sides of a string
The charAt() method returns the character at a specified index (position) in a string
The charCodeAt() method returns the unicode of the character at a specified index in a string

## JavaScript String search
The indexOf() method returns the index of (the position of) the first occurrence of a specified text in a string


## String.lastIndexOf()

The lastIndexOf() method returns the index of the last occurrence of a specified text in a string

![image](https://user-images.githubusercontent.com/12488769/148701398-0a771e55-efab-4d8f-a5bc-b64b853cd52d.png)

Both indexOf(), and lastIndexOf() return -1 if the text is not found

## String,Includes()
The includes() method returns true if a string contains a specified value.
![image](https://user-images.githubusercontent.com/12488769/148701418-c7b5537e-4f85-40ed-92fd-1d296e651411.png)

## String.startsWith()
The startsWith() method returns true if a string begins with a specified value, otherwise false
![image](https://user-images.githubusercontent.com/12488769/148701434-0f513a9c-86e6-4685-b654-951dd6b84180.png)

## String.endsWith()
The endsWith() method returns true if a string ends with a specified value, otherwise false

![image](https://user-images.githubusercontent.com/12488769/148701445-cb0ce395-8de5-4422-a7ff-9e03dcb370d1.png)





