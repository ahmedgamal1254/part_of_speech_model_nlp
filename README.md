# part_of_speech_model_nlp
make Part of Speech from scratch not depand on libs like nltk

# techniques 
<uL>
  <li>Nltk</li>  
  <li>keras</li>
  <li>tensorflow</li>  
  <li>pickle</li>  
  <li>numpy</li>
</ul>

Note : i used nltk to load dataset supervised (word ,pos) in sentence
#### we use model Lstm many to many which input = output

introduction about POS

in grammar, a part of speech or part-of-speech (abbreviated as POS or PoS, also known as word class or grammatical category) is a category of words (or, more generally,
of lexical items) that have similar grammatical properties. Words that are assigned to the same part of speech generally display similar syntactic behavior (they play
similar roles within the grammatical structure of sentences), sometimes similar morphological behavior in that they undergo inflection for similar properties and even
similar semantic behavior. Commonly listed English parts of speech are noun, verb, adjective, adverb, pronoun, preposition, conjunction, interjection, numeral, article,
and determiner.

<h3 style="background-color:#263159;color:white;padding:20px">Steps :-</h3>

<ol>
    <li>import necessary libs</li>
    <li>load dataset for nltk</li>
    <li>Preprocess data</li>
    <li>convert sentences to numbers</li>
    <li>word embedding</li>
    <li>make model by Lstm</li>
    <li>evaluate model</li>
</ol>
