<div class="container">
    <h1>📧 Spam Detection Project (Naive Bayes Classifier)</h1>
    <p>This project implements a <strong>Spam Detection System</strong> using the <strong>Naive Bayes</strong> algorithm. It includes executable Python files, generated output files, and directories for training/testing datasets.</p>
    <h2>📦 Project Contents</h2>
    <h3>🔹 Executable Files</h3>
    <ul>
        <li><code>spam_detector.py</code> – Contains core functions for classification.</li>
        <li><code>train.py</code> – Trains the model and generates <code>model.txt</code>.</li>
        <li><code>test.py</code> – Produces <code>result.txt</code> and <code>evaluation.txt</code>.</li>
    </ul>
    <h3>📄 Output Files</h3>
    <ul>
        <li><code>model.txt</code> – Vocabulary + probabilities.</li>
        <li><code>result.txt</code> – Classification results.</li>
        <li><code>evaluation.txt</code> – Evaluation metrics + confusion matrix.</li>
    </ul>
    <h3>📁 Source Directories</h3>
    <ul>
        <li><strong>train/</strong> – Training emails.</li>
        <li><strong>test/</strong> – Testing emails.</li>
    </ul>
    <h2>📖 Naive Bayes Overview</h2>
    <div class="box">
        Naive Bayes is a probabilistic classifier based on <strong>Bayes' Theorem</strong> with independence assumptions.
        It works extremely well for text classification such as spam filtering.
    </div>
    <p>It calculates probabilities of a message being Spam or Ham based on word occurrence. The higher probability wins.</p>
    <h2>🧪 Execution Instructions</h2>
    <ol>
        <li>Run <code>spam_detector.py</code> – Loads helper functions.</li>
        <li>Run <code>train.py</code> – Creates <code>model.txt</code>.</li>
        <li>Run <code>test.py</code> – Generates <code>result.txt</code> and <code>evaluation.txt</code>.</li>
    </ol>
    <h2>📚 References</h2>
    <ul>
        <li><a href="https://courses.cs.washington.edu/courses/cse312/18sp/lectures/naive-bayes/naivebayesnotes.pdf" target="_blank">Notes on Naive Bayes (Jonathan Lee)</a></li>
        <li><a href="https://en.wikipedia.org/wiki/Naive_Bayes_classifier" target="_blank">Wikipedia – Naive Bayes</a></li>
        <li><a href="https://www.youtube.com/watch?v=8aZNAmWKGfs" target="_blank">YouTube – Spam Detection with Naive Bayes</a></li>
        <li><a href="https://www.youtube.com/watch?v=EGKeC2S44Rs" target="_blank">YouTube – Text Classification Naive Bayes</a></li>
        <li><a href="https://manisha-sirsat.blogspot.com/2019/04/confusion-matrix.html" target="_blank">Confusion Matrix Explained</a></li>
        <li><a href="https://www.pythonforengineers.com/build-a-spam-filter/" target="_blank">Build a Spam Filter</a></li>
    </ul>
    <footer>
        ✨ Created by <strong>Shahzad Akram</strong> —  Spam Detection using Naive Bayes
