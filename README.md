# twigcodingchallenge

The rand variable generates a random number to create an array with. The n variable is an integer less than the rand integer that is used to divide the 
arr array. The arr array crates the array and it's values.

The groupArrayElements function takes parameters arr and n. It initialises an index for the loop with value 0, calculates the length of the array and
initialises and temp array to hold the values of the divided array.

The loop runs from the initial index value through the number of elements in the array and uses the "slice()" method to create a new array from the updated
index integer to the index n integer and holds the updated array inside the mychunk variable. The new myChunk array is them pushed into the temporary array.

When the loop is completed, the tempArray is returned and logged in the ouput of the browsers console.

To run the code and check the results, open the HTML file and open the developer tools to check the console.
