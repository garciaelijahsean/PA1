**ALPHABET SOUP PROBLEM:** Create a function that takes a string and returns a string with its letters in alphabetical order.

def alphabet_soup(string):

    return "".join(sorted(string))

    print(alphabet_soup("hello"))
    print(alphabet_soup("Aing"))
    print(alphabet_soup("keyboard"))
    print(alphabet_soup("jupyter"))

**Functions and how they work:** 

sorted(string) -> This function takes the input and sorts the characters in alphabetical order, (regardless if it is capitalized or not), and outputs a list of characters 

"".join() -> This function joins the list of characters into a single string 

**EMOTICON PROBLEM:** Create a function that changes specific words into emoticons. Given a sentence as a string, replace the words smile, grin, sad and mad with their corresponding emoticon:

def emotify(sentence): 
    
    if "smile" in sentence:
        return sentence.replace("smile", ":)")
    elif "grin" in sentence:
        return sentence.replace("grin", ":D")
    elif "sad" in sentence:
        return sentence.replace("sad", ":((")
    elif "angry" in sentence:
        return sentence.replace("angry", ">:(")
    else:
        return sentence
    
    print(emotify("Make me smile"))
    print(emotify("You made me grin"))
    print(emotify("Why are you sad?"))
    print(emotify("I am angry"))

**Functions and how they work:** 

if "(emoticon)" in sentence: -> An if statement. If conditions are met, it executes the code under it. If not, then moves to another if statement (elif (else if)).

.replace(word, emoticon) -> This function swaps the word with its matching emoticon. 
- "smile" -> :)
- "grin" -> :D
- "sad" -> :((
- "angry" -> >:(


**UNPACKING LIST PROBLEM:** Unpack the list writeyourcodehere into three variables, being first, middle, and last, with middle being everything in between the first and last element. Then print all three variables.

def my_List(something):

    first = something[:1]
    middle = something[1:-1]
    last = something[-1:]
    
    print("First: ", first)
    print("Middle:", middle)
    print("Last: ", last)
    print("")

**Functions and how they work:** 

something[:1] -> This function takes the first element of the list 

something[1:-1] -> This function takes everything in between the first and last elements 

something[-1:] -> This function takes the last element of the list 
