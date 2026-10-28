# Moyo-kodland-first-repository
meme_dict = {
            "CRINGE": "Something exceptionally weird or embarrassing",
            "LOL": "A common response to something funny ",
            "ROFL":"A response to a joke",
            "SHEESH":"A slight disapproval",
            "CREEPY":"Scary, ominus",
            "TO AGGRO":"To get aggressive/angry"    
            }
word = input("Type in a word you don't understand (use all capital letters!): ")
if word in meme_dict.keys():
       print(meme_dict[word])
else:
    print("Sorry, that word isn't in the dictionary.")