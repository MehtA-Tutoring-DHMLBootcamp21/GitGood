Midterm Project by Isaac Ang, Daniel Suh, and Abdulaziz Khader
Task: Predict poem setting using machine learning. 

Method:
- Create a list of countries/cities for every poem using a pre-trained NLP model
- Run through pycountries to help with edge cases and add these countries to the list
- For poems that NLP and pycountries did not predict a location for, use word2Vec to associate objects in the poem with pycountries and output the country with the closest relationship to the poem's collection of objects
- For poems that NLP and pycountries predicted several locations for, perform the same operation as above but this time compare the collection of objects to the locations NLP and pycountries predicted for the poem
