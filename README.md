# counting-vowels-
#one way (without input)
#count the vowels in a string 
def vowel_counting(input_string):
    vowel = "aeiouAEIOU"
    vowel_count = 0

    for i in input_string:
        if i in vowel:
            vowel_count +=1
    return vowel_count
        
my_string = 'my name is Elina, and i do a python project'
print("The amount of vowels in this sentences: ", vowel_counting(my_string))

#here is another way with input
def count_vowels(input_string):
    vowels = 'aeiouAEIOU'
    vowel_count = 0
    
    for char in input_string:
        if char in vowels:
            vowel_count += 1
    
    return vowel_count

my_string = str(input("enter your message here, and we will count the amount of vowels: "))
print("Number of vowels in the string:", count_vowels(my_string))
