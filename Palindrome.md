**A palindrome is a word that reads identically backward or forward**    

RADAR, CIVIC, KAYAK and RACECAR are all examples of a palindrome    

An algorithm that can determine wether a word is a palindrome is as follows:  
Put the word in question in a list  
If the list only contains one letter it is a palindrome  
If not, compare the first and last letters of the list. If they are different then the word is not a palindrome  
Then, compare the second and second last letters. Keep repeating this process(third and third last, fourth and fourth last etc..) until:  
**A**: You run out of letters, in which case the word is a palindrome  
**B**: You find a pair that are different, in which case the word is not a palindrome

**For Example:**   
If the word 'DEFIED' was being tested  
The first and last letters are the same so move onto the next stage  
The second and second last letters are the same so move onto the next stage  
The third and third last letters are NOT the same meaning 'DEFIED' is NOT a palindrome

