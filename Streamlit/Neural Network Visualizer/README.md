## Neural Network Visualizer.

<h3>The aim of this project is to visualize the outputs of each layer in a Neural Network. <br> 
1) First the Flask server is made active, wherein the model is loaded. <br>
2) The server accepts the post request and responds back with the prediction as well as the random image generated. <br>
3) The web app is made via Streamlit. <br>
4) Upon clicking on the "Generate Image" Button, a post request is sent to the ML Flask server. <br>
5) The response is loaded and the output of the various layer is displayed on the screen. <br>
<br>

## Steps to run the project.

1) The only file you need to run is [jupyter file](Walkthrough.ipynb) <br><br>
2) All the remaining files {app.py, ml_server.py, model.h5} will be automatically created with the help of "%%writefile" magic function in jupyter. <br><br>
3) Run the Flask server [ml_server.py](ml_server.py) on terminal using the command : <br>
  <i>python ml_server.py</i> <br><br>
4) Open another terminal and run the Streamlit application [app.py](app.py) using the command : <br>
  <i>streamlit run app.py</i> <br><br>
5) Go to the [url](https://localhost:8501) to view the streamlit application. <br>
<br>

#Note : <br>
  The Flask application should not be closed in between. It will be running on this [site](https://localhost:5000/)


