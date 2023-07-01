<h1 align = "center">Similarity comparison</h1>
<br/>
<h2 font_size = 10px;>Introduction of some improtant terms:</h2> 
<ul>
  <li><b><big>Cosine similarity</big></b> is a mathematical calculation that find the similarity between two words or sentences but in this code the similarity has been found between two words only that has been prompted by the user.</li>
  <br/>
  <li><b><big>TF_IDF<i>(term Frequency Inverse Frequency)</i></big></b> is a mathematicle calculation that finds the importance of each word in the document. </li>
 <b>Term Frequency (TF) : </b> It represents the frequency of a term within a document relative to the total number of terms in that document.
 <br/>Mathematically it can be represented as follows:<br/>
<p style="color: #808080;"> <br/><b>TF</b> = (Number of times term t appears in a document)/(Number of terms in the document)<br/> </p>
 <br/> <b>Inverse document frequency(IDF):</b> It is a measure used in information retrieval and text mining to quantify the importance of a term in a collection 
  of documents.<br/>
  <br/> Mathematically it can be represented as follows:<br/>
 <br/><p style="color: #808080"><b>IDF</b> = log(N/n), where, N is the number of documents and n is the number of documents a term t has appeared in.</p><br/>
 <br/><b>TF-IDF (Term Frequency-Inverse Document Frequency) : </b> TF-IDF (Term Frequency-Inverse Document Frequency) is a numerical representation that combines the local importance of a term within a document (TF) with its global significance in the collection (IDF).<br/>
 <p style="color: #808080";><b>TF-IDF</b> = TF*IDF</p>
  
  <br/>
  <li><b><big>Word Embedding</i></big></b> is a technique used in natural language processing (NLP) to represent individual words as real-valued vectors in a predefined vector space.</li>
  <br/>
  <li><b><big>BERT<i>(Bidirectional Encoder Representations from Transformers)</i></big></b> is a  pre-trained language model that is designed to pre-train deep bidirectional representations from unlabeled text by jointly conditioning on both left and right context in all layers.</li>
</ul>
<p> &nbsp;&nbsp;Please note that the prompted words are words that exist inside the dataset.</em></p><em>
  
<h2 font_size = 10px;>About the used dataset:</h2> 
<p> Dataset is collection of Arabic articles that can be used in different Arabic <b>NLP tasks</b> . The articles were collected using <b>Python scripts</b> written specifically for <b><a href="https://mawdoo3.com/">mawdoo3</a></b> website.

datasets have two columns [Title, article] , contains a total number of 5000 articles. </p>


<h2 font_size = 10px;>Requirements:</h2> 
<ul>
<li> First of all you need to extract the compressed file "Dataset!"</li>
<pre align ="left">import zipfile as zf
files = zf.ZipFile("Arabic_dataset.zip", 'r')
files.extractall("Arabic_dataset")
files.close()</pre>

<li> Now you need to install the required libraries:<br>
     &nbsp;&nbsp; torch  
     &nbsp;&nbsp; transformers <br>
     &nbsp;&nbsp; pandas <br>
     &nbsp;&nbsp; numpy <br> 
     &nbsp;&nbsp; scikit-learn <br> 
     &nbsp;&nbsp; regex <br> 
     &nbsp;&nbsp; strings <br> 
     &nbsp;&nbsp; python-math 
 <p align ="center">check the requirment.txt file.</p> 
</li>
<li> note: if your device is slow you can use <a <a href="https://colab.research.google.com/drive/1LV9h--LiKA3lgzChXQiGgamyakaNhJFy?usp=sharing">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a> to run the code on it. Also, activate the GPU via clicking on the runtime from the toolbar >>> change runtime type >>> Hardware accelerator >>>> GPU.</li> <br>
<li> Now you're ready to run your code. It's provided with more than one type such as .ipynb extention which is compatible with jupyter notebook & .py extention which is compatible with python file.</li>
</ul>
