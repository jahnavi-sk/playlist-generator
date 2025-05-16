# Playlist Generation 



### Folders


##### ./creating

- To create the chroma db with the songs information, please follow the ```playlist.ipynb``` file.
- To create the sentiment analysis model, please follow ```sentiment.ipynb```
- Make sure to update the csv file names accordingly
- Also ensure the system has Ollama installed and model 'mistral' and 'llama 3.2' have been pulled.



#### ./frontend
- The frontend folder
- To install dependencies:
  ```
    npm i
  ```
- To run it:
  ```
    npm run dev
  ```

#### ./backend
- The backend folder
- Please follow the sql schema, and update the config file accordingly.
- To install dependencies
  ```
    pip install -r requirements.txt
  ```
- To run it:
  ```
    uvicorn app.main:app --reload
  ```
  

