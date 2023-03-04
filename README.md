Source code: <br />
Notebook File 
<br />
<br />
Instructions on how to run the code: <br /> 
Open the attached notebook in colab, drag u.data, u.item, u.user and the gzips to the colab content folder and run the notebook 
<br />
<br />
Algorithm hyperparameters: <br /> 
FEATURES_EMBEDDING_DIMS = 512,<br />
OCCUPATIONS_EMBEDDING_DIMS = 8,<br />
ZIP_EMBEDDING_DIMS = 256,<br />
GENRES_EMBEDDING_DIMS = 8,<br />
DENSE_UNITS = [128, 256],<br />
LEARNING_RATE = [0.001, 0.01],<br />
BATCH_SIZE = 256,<br />
Candidate Network EPOCHS: 15,<br />
Candidate Network LOSS: 'sparse_categorical_crossentropy',<br />
Ranking Network EPOCHS: 3,<br />
Ranking Network LOSS: 'mse'<br />
