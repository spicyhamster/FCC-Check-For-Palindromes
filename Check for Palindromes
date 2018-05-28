//Return true if the given string is a palindrome. Otherwise, return false.


function palindrome(str) {
  var a = str.toLowerCase();
  a = a.replace(/\W+/g,"");
  a = a.replace(/_+/g,"");
  var arr = a.split("");
  arr = arr.reverse();
  var rev = arr.join("");
  return a == rev;
}



palindrome("A man, a plan, a canal. Panama");  // should return true
