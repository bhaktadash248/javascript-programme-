# javascript-programme-
1. Palindrome Check
   function isPalindrome(str) {
    // Convert the string to lower case and remove non-alphanumeric characters
    const cleanedStr = str.toLowerCase().replace(/[^a-z0-9]/g, '');
    // Compare the string with its reverse
    return cleanedStr === cleanedStr.split('').reverse().join('');
}

console.log(isPalindrome("A man, a plan, a canal: Panama")); // true
console.log(isPalindrome("hello")); // false
