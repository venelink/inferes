# The INFERES dataset

train size = 6444 

test size = 1612

# Columns

ID : the unique ID of the instance

Premise 

Hypothesis

Label: cnt, ent, neutral

Topic: 1 (Picasso), 2 (Columbus), 3 (Videogames), 4 (Olympic games), 5 (EU), 6 (USSR)

Anno: ID of the annotators (in cases of undergrads or crowd - the ID of the group)

Anno_Type: strategy used to generate the data: Generate, Rewrite, Crowd, and Automated

Dataset is split stratified by a key that combines Label + Annotator + Annotation_type

Disclaimer: official results in the paper are done via k-fold cross validation and average across multiple runs. Experiments with this split might differ slightly.
