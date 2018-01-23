# Python-Session-4---Assignment-2
Function to covert a list of words into a corresponding list of integers

Function to determine if one alphabet is a vowel or not

def Length_of_words(a):
    a = input("Enter list of words separated by 'space': ")
    c = list(map(lambda b: len(b), a.split(" ")))
    return (c)

Words = Length_of_words("Word")
print (Words)

def Vowels(a):
    a = a.lower()
    b = ("a", "e", "i", "o", "u")
    if a in b:
        return (True)
    else:
        return (False)
    
Solution = Vowels("h")
print (Solution)
