# Krackhardt's Cognitive Social Structures
Transcription of the 21 directed adjacency matrices in the Appendix of Krackhardt's 1987 "Cognitive Social Structures" paper.

Each file in the `krackhardt_data` folder is named `krack_X.csv` where X is an integer between 1 and 21. Each csv file corresponds to a slice of Krackhardt's High-Tech management cognitive social structures data. Each file has 21 rows and 21 columns and is in the 0/1 format of the adjacency matrix.

21 employees in management at a tech company were approached to answer a survey. Each person was asked to answer the question "Who would Y go to for help or advice at work?" followed by a list of the 20 other management employees. They had to answer this for each employee Y in management (including themselves). Thus adjacency matrix Y captures Y's perception of who each person in management goes to for help or advice. Note that the Yth row of the Yth adjacency matrix contains the ground truth of who Y goes to for help or advice (it is Y's answer to the question "Who would Y go to for help or advice at work?"

An aggregation of this data [can be found online here](http://vlado.fmf.uni-lj.si/pub/networks/data/WaFa/default.htm). The data set provided at this website contains 3 layers, where the first layer is an aggregate of the 21 data matrices where row i was taken from the ith adjacency matrix. Thus the first layer is the "ground truth" of who each person goes to for help or advice at work. Layer two is the answer to the question "Who is your friend" for each person in management. Layer three is the answer to the question "Who do you report to?"

[Krackhardt, David. "Cognitive social structures." Social networks 9.2 (1987): 109-134.](https://www.andrew.cmu.edu/user/krack/documents/pubs/1987/1987%20Cognitive%20Social%20Structures.pdf) 
