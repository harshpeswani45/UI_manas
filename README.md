<h1> Running The App </h1>
<h2> Install Streamlit: </h2>
pip install streamlit<br><br>

<h2> Run The App </h2>
streamlit run UI.py

<h1>Modifications Required in the code :- </h1>

<h2> Loading The Model </h2>

In load_model function load the model (by either importing the model or use pickel/joblib), then return model variable.

<h2> Fetching The Output </h2>

Question is in the question variable. Input answer is in the input_answer variable , use the question and the input_answer to fetch the required output using model variable.
