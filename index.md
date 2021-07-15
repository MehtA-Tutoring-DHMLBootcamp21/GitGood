<html>
    <body>
        <div class = "center">
            <h1>Midterm Project</h1>
            <h2>Isaac Ang, Daniel Suh, Abdulaziz Khader</h2>
            <h3>Predict Poem Setting Using Machine Learning</h3>
            <p>Method:
                <ol>
                    <li>Create a list of countries/cities for every poem using a pre-trained NLP model</li>
                    <li>Run through pycountries to help with edge cases and add these countries to the list</li>
                    <li>For poems that NLP and pycountries did not predict a location for, use word2Vec to associate objects in the poem with pycountries and output the country with the closest relationship to the poem's collection of objects</li>
                    <li>For poems that NLP and pycountries predicted several locations for, perform the same operation as above but this time compare the collection of objects to the locations NLP and pycountries predicted for the poem</li>
                </ol>
            </p>
            <h3>Numpy, NLTK, RE, SpaCy, Pycountry</h3>
            <ul>
                <li><a href="https://www.nltk.org/">NLTK Library</a></li>
                <li><a href="https://numpy.org/doc/">Numpy Library</a></li>
                <li><a href="https://docs.python.org/3/library/re.html">RE Library</a></li>
                <li><a href="https://spacy.io/api/doc/">SpaCy Library</a></li>
                <li><a href="https://pypi.org/project/pycountry/">Pycountry Library</a></li>
                <li><a href="https://www.sicara.ai/blog/2018-04-25-python-train-model-ntlk-stanford-ner-tagger">Stanford NER Article</a></li>
                </ul>
            <h3>View Our Code!</h3>
            <script src="https://gist.github.com/23danielsuh/9bedee24ffbab1f58aacbfe04ad22130.js"></script>
        </div>
    </body>  
</html>
