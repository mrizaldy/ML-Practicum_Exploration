Introduction
Jigsaw is a unit within Alphabet that builds technology to make the world safer. In 2017, the team set out to address online harassment and developed Perspective API. The goal of Perspective API is to increase participation, quality, and empathy of online conversation at scale. Developers and publishers can use Perspective to identify and filter text that inhibits constructive dialogue on online forums by analyzing the content of comments for potentially offensive text, including threats, insults, profanity, and toxic language.

Perspective API takes comment text as input and returns a "score" from 0 to 1 that indicates the probability that the comment is similar to toxic comments it's seen in the past. A score of 0 signifies 0% probability that the comment is toxic, a score of 1 signifies 100% probability that the comment is toxic, and a score of 0.5 signifies a 50% probability that the comment is toxic (i.e., that the model is not sure).

Problem Statement
After the initial launch of Perspective API, external users discovered a positive correlation between identity terms containing information on race or sexual orientation and toxicity score. For example, the phrase "I am a gay black woman" received a toxicity score of 0.87. In this case, the identity terms were not being used pejoratively, so this example was classified incorrectly. Where did things go wrong?
