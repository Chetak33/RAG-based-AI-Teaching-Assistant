# How to use this RAG AI Teaching Assistant on your own data
## Step 1 - Collect your videos
Move all your video files to the video folder

## Step 2 - Convert to MP3
Convert all video files to MP3 by running video_to_mp3

## Step 3 - Convert MP3 to json
Convert all MP3 files to json by running mp3_to_json

## Step 4 - Convert the json files to Vectors
Use the file preprocess_json to convert the json files to a dataframe with Embeddings and save it as a joblib pickle

## Step 5 - Prompt generation and feeding it to LLM
Read the joblib file and load in into the memory. then create a relevent prompt as per the user querry and feed it to the LLM