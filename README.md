<h1>HyperLex</h1>
  <div>
  <img class="resize" src="https://user-images.githubusercontent.com/21332532/66464553-884cee00-ea7f-11e9-806b-9573814d2591.png">   
  </div>
        <p><i><b>HyperLex</b></i> is a gold standard resource for measuring and evaluating how well semantic models capture <b>graded or soft lexical entailment</b> (also known as the <i>type-of, is-a, or hypernymy-hyponymy</i> relation) rather than semantic similarity or relatedness. It quantifies the extent of the semantic category membership and lexical entailment (LE) relation.</p>
        
<p>HyperLex provides <b>2616 word pairs</b> (2163 noun pairs and 453 verb pairs) with ratings on a scale 0-6, annotated according to the question: <i>"To what degree is X a type of Y?"</i>. Here are some examples:</p>

<table width='25%'>
            <tr>
                <th align='left'>Pair</th>
                <th align='left'>Rating</th> 
            </tr>
            <tr>
                <td>girl / person</td>
                <td>5.91</td> 
            </tr>
            <tr>
                <td>citizen / person</td>
                <td>5.18</td> 
            </tr>
      <tr>
                <td>person / citizen</td>
                <td>3.10</td> 
            </tr>
            <tr>
                <td>idol / person</td>
                <td>2.57</td> 
            </tr>
      <tr>
                <td>plant / animal</td>
                <td>0.08</td> 
            </tr>
      <tr>
                <td>to talk / to communicate</td>
                <td>5.55</td> 
            </tr>
      <tr>
                <td>to pray / to communicate</td>
                <td>2.90</td> 
            </tr>
        </table>

<p>HyperLex covers plenty of normed word types from the USF free-association database, and provides annotated examples of different WordNet-based lexical relations (i.e., hyponymy-hypernymy at different levels, co-hyponymy, synonymy, antonymy, meronymy-holonymy, no-relation). It also contains examples of different concreteness levels.</p>

<h2>Download</h2>
        <p>
        Download HyperLex <a href="https://github.com/cambridgeltl/hyperlex/blob/master/hyperlex-data.zip?raw=true">by clicking here</a>.</br>
  <p/>
  
  All design details are described in the following paper. Please cite it if you use HyperLex in your own work:<br/>
        </p>
        <p>
        <b>HyperLex: A Large-Scale Evaluation of Graded Lexical Entailment</b> <br/>
        Ivan Vuli&cacute;, Daniela Gerz, Douwe Kiela, Felix Hill, and Anna Korhonen. 
        Computational Linguistics, volume 43, number 4, pages 781-835, 2017.<br/>
        [<a href="https://www.aclweb.org/anthology/J17-4004.pdf">pdf</a>] [<a href="https://www.aclweb.org/anthology/J17-4004.bib">bib</a>]
        </p>
        
 <p>The provided archive includes the full HyperLex dataset, noun and verb subsets, as well as two different data splits (random and lexical) into training, development and test data. Please see the accompanying <i>readme</i> file for the file formats and further details.</p>
  
<h2>HyperLex in Other Languages and Cross-Lingual HyperLex</h2>
        <p>
  Similar repositories for three other languages <b>(German, Italian, Croatian)</b> based on the original English HyperLex are
        also available. You can download multilingual and cross-lingual HyperLex <a href="https://github.com/cambridgeltl/hyperlex/blob/master/cl-hyperlex-data.zip?raw=true">by clicking here</a>.</br>
  <p/>
  
  The multilingual and cross-lingual extensions of the original HyperLex data set are described in the following paper. Please cite it if you use the data in your own work:<br/>
        </p>
        <p>
        <b>Multilingual and Cross-Lingual Graded Lexical Entailment</b> <br/>
        Ivan Vulić, Simone Paolo Ponzetto, and Goran Glavaš.
        Proceedings of the 57th Annual Meeting of the Association for Computational Linguistics (ACL 2019), pages 4963-4974, 2019.<br/>
        [<a href="https://www.aclweb.org/anthology/P19-1490.pdf">pdf</a>] [<a href="https://www.aclweb.org/anthology/P19-1490.bib">bib</a>]
        </p>

<h3> Contact </h3>

<p>Please contact the first author (<a href="https://sites.google.com/site/ivanvulic/">Ivan Vuli&cacute;</a>) if you have any questions not addressed in the referenced papers and repo README files.</p>
