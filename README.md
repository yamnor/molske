[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://molske.streamlitapp.com/)

# molske ✍️

A Streamlit app that reads a molecule sketched with _hexagon-shaped_ **atoms** and _hand-drawn_ **bonds** to convert it into 2D & 3D structures, and predict its chemical properties.

## How to play

https://yamlab.net/Files/molske.mp4

* **Black**, **blue**, and **red** hexagonal-shaped parts are recognized as
  carbon (**C**), nitrogen (**N**), and oxygen (**O**) atoms, respectively.
* **Green**, **red**, and **yellow** lines shown on the video screen represent
  **single**, **double**, and **triple** bonds, respectively.
* Chemical structures can be drawn in [skeletal formula](https://en.wikipedia.org/wiki/Skeletal_formula).
  Hydrogen (**H**) atoms are automatically added according to the detected chemical structure.

## Notice

* This web app is hosted on a cloud server ([Streamlit Cloud](https://streamlit.io/))
   and videos are sent to the server for processing.
* No data is stored, everything is processed in memory and discarded,
  but if this is a concern for you, please refrain from using this app.

## Local installation

```
git clone https://github.com/yamnor/molske.git
cd molske
pip install -r requirements.txt
```

## How to run

```
streamlit run molske.py
```

## Author

* This web app is developed by [Yamamoto, Norifumi (@yamnor)](https://twitter.com/yamnor).      
* You can follow me on social media:
  [GitHub](https://github.com/yamnor) | 
  [LinkedIn](https://www.linkedin.com/in/yamnor) | 
  [WebSite](https://yamlab.net).
