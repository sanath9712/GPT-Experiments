# CHATGPT-Experiments
This will be a repo to do series of experiments on ChatGPT. I have started with a random fact generator. I have used the Open AI API to generate random facts for topics through GPT 3.5 . These generated facts are currently being stored locally in a csv file and the Firebase DB on the cloud. This will be part of a bigger project which I am not fully sure about at this point of time. Even though the end goal of this project is uncertain, what is certain is that Messi is the GOAT.



Some crude ideas in mind:
- Random Fact Analysis: Going through all the random facts for a particular topic and trying to find out if there is someone/something that is very closely tied to this topic. For eg: Bengaluru(A topic) is the tech hub of india, so that could be mentioned in several random facts either explicitly or implicitly.

- Judging how much chatgpt contradicts itself in case of random facts about the same topic. For eg: An Average person takes 2000 steps a day and An Average person takes 10k steps a day are contradictory.

- Repetition: How often is the same fact repeated(Facts with same meaning) and what does that say about chatgpt's performance in generating random facts. As we collect more and more random facts, it is obvious that we will see similarities. But how soon do we see similarities spring up can be analysed. We can conduct some finer analysis to determine whether Chatgpt is not able to generate more facts or if the chosen topic is restricted in its scope.

- Validation of generated data: I intend to validate the generated data by comparing it with external resources like articles, blogs or any other piece of relevant information which can be found online and accordingly gauge the degree to which ChatGPT hallucinated while creating my data.


For all the above ideas, experiments will be conducted with different model hyperparameters, datasets to arrive at a holistic, well rounded conclusion.



Instructions to run the code (For Now):

Navingate to the src directory and run ```python datacreator.py```
