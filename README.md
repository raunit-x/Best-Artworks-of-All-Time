# Best-Artworks-of-All-Time
<h1>About</h1>
<p>A collection of artworks of the 50 most influential artists of all time.
  You can find the dataset <a href='https://www.kaggle.com/ikarus777/best-artworks-of-all-time'>here</a>
</p>
<ol>
  <li>Find the classification colab notebook: <a href='https://colab.research.google.com/drive/1W7ChMvOfmd55SNl_oDGanQ-YUeLyKeEL?usp=sharing'>here</a></li>
  <li>Find the visualisation colab notebook: <a href='https://colab.research.google.com/drive/1hkLf-aLjA_STAw7zg8xaxXyFSYpSI9za?usp=sharing'>here</a></li> 
</ol>
<h3>1. Visualization</h3>
<h4>Resized artworks</h4>
<img src='/Plots/Artworks.png' width="800">
<h4>Nationality of artists</h4>
<img src='Plots/nationality.png'>
<h4>Genre against frequency of artworks on Age Groups</h4>
<img src='Plots/genre_with_paintings.png'>
<h4>KDE Plots</h4>
<p float="left">
  <img src="Plots/age_kde.png" width="400" />
  <img src="Plots/birth_kde.png" width="400" />
</p>
<h3>2. Artist from Artwork; Classification (Transfer Learning: ResNet50)</h3>
<h4>Accuracy and Loss function plots</h4>
<img src='Artist from Art classification/plots.png' width="800">
<h6>Validation Accuracy: <b>0.828</b></h6>
<h6>Training Accuracy: <b>0.99</b></h6>
<h4>Confusion Matrix</h4>
<img src='Artist from Art classification/confusionMatrix (1).png' width='800'>
<h4>Artist from art right off the web</h4>
<img src='Artist from Art classification/own url.png' width='400'>
<h6>Note: CNNs are sensitive to distributions so an edited web image might completely put off the classifier</h6>
<h6>Dropout or other regularisation techniques should definitely help to reduce high variance</h6>
