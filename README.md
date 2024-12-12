# bayareacoders
Colab Notebook containing the demo to use for the event Bay Area Coders Collective

We have 2 variations on how to use models in the following pipeline in Dataflow

We have 2 variations on how to use models in the following pipeline in Dataflow
1. Through Hugging Face to download the model locally and do local inference using Dataflow ML to generate a transcript
2. Using a Vertex.ai endpoint to do remote inference and using the vertex.ai libraries in Dataflow without leveraging Dataflow ML to generate a summary of the audio file

For this lab we assume that you are using some audio file capturing a conversation similar to the one provided in the  following dataset from Kaggle:
[Kaggle Speaker audio](https://www.kaggle.com/datasets/vjcalling/speaker-recognition-audio-dataset/data)

You can access the colab notebook content from: 
bayareacoders/BayArea_Coders_Collective_Dataflow_ML_.ipynb
