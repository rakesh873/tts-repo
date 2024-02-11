# install pyttsx3 version
import pyttsx3
# create a variable to initialize the pyttsx3
text_sp = pyttsx3.init()
# create a variable to user input
user_inf = input("enter what do you want to convert text to speech:")
# say method is used to convert user input to speech
text_sp.say(user_inf)
# runandwait method is used to run and wait until conversion
text_sp.runAndWait()
