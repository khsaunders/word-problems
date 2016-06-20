// Create a function called notBad that takes a single argument, a string.
// it should find the first appearance of the substring 'not' and 'bad'.
// If the 'bad'follows the 'not', then it should replace the whole 'not'...'bad' substring with 'good' and return the result.
// If it doesnt find 'not' and 'bad' in the right sequence (or at all), jsut return the original sentence.

// Oh god. Why.


//This simply shows me the position of the words I'm looking for:
//This method was found when I searched for 'keywords substring' and appeared in a StackOverflow forum
// var string1 = "The movie was not bad",
//     substring = "not" && "bad";
// console.log(string1.indexOf(substring));

var string = "This movie was not bad"
string.search("not" && "bad")

I know this will have some kind of replace() feature to it. But it's simply a matter of being able to identify the string first.

Interesting to see how others have solved this:
Aaron's method for solving this.


function notBad (string){
if (strong.search('not bad') > 0){
  console.log(string.replace "not bad", "good"));
  }
else {
  console.log(string);
  }
}

notBad("Josta is not bad");
notBad("Mad Max is amaze ");

Actually works! Cool! Commit this to memory. 
