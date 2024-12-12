# Bay Area Coders Collective  - Dataflow ML
Colab Notebook containing the demo to use for the event Bay Area Coders Collective

#### Description
We have 2 variations on how to use models in the following pipeline in Dataflow

We have 2 variations on how to use models in the following pipeline in Dataflow
1. Through Hugging Face to download the model locally and do local inference using Dataflow ML to generate a transcript
2. Using a Vertex.ai endpoint to do remote inference and using the vertex.ai libraries in Dataflow without leveraging Dataflow ML to generate a summary of the audio file

For this lab we assume that you are using some audio file capturing a conversation similar to the one provided in the following dataset from Kaggle:
[Kaggle Speaker audio](https://www.kaggle.com/datasets/vjcalling/speaker-recognition-audio-dataset/data)

#### What is needed:
- Need a GCS bucket containing the audio files you want to use for testing with the right permissions (Read) set to the user authenticate with on this notebook


#### Accessing the notebook:
You can access the colab notebook content from: 
[bayareacoders/BayArea_Coders_Collective_Dataflow_ML_.ipynb](https://github.com/c-damien/bayareacoders/blob/main/BayArea_Coders_Collective_Dataflow_ML_.ipynb)

or directly: 

[![Colab](https://camo.githubusercontent.com/96889048f8a9014fdeba2a891f97150c6aac6e723f5190236b10215a97ed41f3/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667 'Colab')](https://colab.research.google.com/github/c-damien/bayareacoders/blob/main/BayArea_Coders_Collective_Dataflow_ML_.ipynb)
