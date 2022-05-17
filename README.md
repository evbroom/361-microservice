# 361-microservice

In the microservice folder, run <code>py birthday_wish.py</code> to start the microservice.

Once a valid relationship string has been entered in <code>relationship.txt</code>, up to 5 randomly selected greetings will be generated in <code>wishes.json</code> in a list.

## Example
Entering <code>friend</code> in <code>relationship.txt</code> will generate five greetings in <code>wishes.json</code>:

    {
        "greetings": ["Thank you for always helping me live life to the fullest. I couldn't ask for a better friend than you!", "You're older than you've been. But look on the bright side, you're younger now than you'll ever be!", "Happy birthday to my best friend. We are getting older, but we still have fun. In fact, we'll probably be up to same shenanigans when we are in an old folks home together!", "You make me laugh harder than anyone else. You've made me laugh so hard I peed myself. You are my best friend and always will be. I hope your birthday is as wonderful as you are!", "It's your birthday, now you can bask in the glow of all those birthday candles on your cake!"]
        }

If an invlid relationship string is entered into <code>relationship.txt</code> then <code>wishes.json</code> will contain:

    {
        "greetings": "This relationship is not valid. Please search for a different relationship."
    }

Valid relationship strings are: <code>'brother-in-law', 'boss', 'aunt', 'teacher', 'brother', 'grand-son', 'friend', 'son', 'sister', 'girlfriend', 'uncle', 'nephew', 'grandfather', 'student', 'father-in-law', 'wife', 'fiance', 'grand-daughter', 'mother', 'boyfriend', 'niece', 'cousin', 'colleague', 'grandmother', 'daughter', 'father', 'sister-in-law', 'mother-in-law', 'husband'</code>.