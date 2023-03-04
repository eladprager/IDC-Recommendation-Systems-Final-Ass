Source code: 
Notebook File



Instructions on how to run the code: 
Open the attached notebook in colab, drag u.data, u.item, u.user and the gzips to the colab content folder and run the notebook



Algorithm hyperparameters: 

FEATURES_EMBEDDING_DIMS = 512,

OCCUPATIONS_EMBEDDING_DIMS = 8,

ZIP_EMBEDDING_DIMS = 256,

GENRES_EMBEDDING_DIMS = 8,

DENSE_UNITS = [128, 256],

LEARNING_RATE = [0.001, 0.01],

BATCH_SIZE = 256,

Candidate Network EPOCHS: 15,

Candidate Network LOSS: 'sparse_categorical_crossentropy',

Ranking Network EPOCHS: 3,

Ranking Network LOSS: 'mse'
