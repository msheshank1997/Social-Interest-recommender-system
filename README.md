# Social Interest  Recommender system

Team Project for CMPE 256 Large Scale Analytics Course in Summer 2019

The project was developed in google collab a notebook editor based on IPython.

We used Google Colab to make the notebook runnable directly in a browser from any OS (Python code runs in cloud on a virtual machine in a google server), moreover Colab guarantees read and write access to our Google Drive where we stored the datasets in a simple and fast way.

The project description is in CMPE256_Team11_Final_Project.docx and below. The code and the discussion of the experiments are in the notebook CMPE256.ipynb . Dataset files are in the data folder.

# Project description 

Used  WikiMID dataset in the form of tab separated values (TSV)

For every user ui , given his/her Wikipedia-mapped interests, finds a set of CATEGORIES representing a synthesis of the shown preferences. In general, you should have less categories than interests (categories should “synthesize” a user’s main interests).

Note that there is no pairwise correspondence between wikipages and semantic interests. The latter are collectively extracted from the full set of wikipages for each user.

You may use any semantic resource (Wikipedia categories, DBPedia, Babelnet..) and any method you can invent or find in literature 

Implementation steps and approaches used:

- Data preanalysis and processing (PCA dimensionality reduction)
- Extracting categories from interests (Mini batch Kmeans clustering)
- Generate clusters of silimar uses(K means clustering with euclidean distance)
- Associate new user to appropriate cluster(Collaborative and content based filtering approaches)
- Rank top 3 pages out of 6 pages (Knowledge based filtering)

More technical details are in docs folder.

Explanation is in :  https://www.youtube.com/watch?v=ZNdsnOQUllk&t=3s


