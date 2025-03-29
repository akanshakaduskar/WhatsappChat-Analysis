<h1>📌 WhatsApp Chat Analyzer</h1>

<p>🔍 <strong>A powerful WhatsApp Chat Analysis tool</strong> that preprocesses, cleans, and visualizes chat data. Gain deep insights into <strong>message trends, user activity, and time-based patterns</strong> with ease!</p>

<hr>

<h2>🚀 Features</h2>
<ul>
    <li>✅ <strong>Preprocess WhatsApp Chat Data</strong> (Extracts timestamps, senders, and messages)</li>
    <li>✅ <strong>Detailed Message Statistics</strong> (Total messages, words, links, media shared)</li>
    <li>✅ <strong>Top Users & Active Hours</strong> (Find most active participants & message distribution)</li>
    <li>✅ <strong>Custom Stopwords Filtering</strong> (Supports Hinglish stopwords)</li>
    <li>✅ <strong>Visualizations</strong> using <code>Matplotlib</code> & <code>Seaborn</code></li>
</ul>

<hr>

<h2>📂 Project Structure</h2>
<pre>
📂 WhatsApp-Chat-Analyzer
│-- 📄 app.py              # Main application script
│-- 📄 helper.py           # Helper functions for processing
│-- 📄 preprocessor.py     # Text preprocessing module
│-- 📄 chat.txt            # Sample chat data
│-- 📄 stop_hinglish.txt   # Hinglish stopwords list
│-- 📄 README.md           # Project documentation
│-- 📄 requirements.txt    # Dependencies (if needed)
</pre>

<hr>

<h2>🛠️ Installation</h2>

<h3>1️⃣ Clone the Repository</h3>
<pre>
git clone https://github.com/&lt;your-username&gt;/WhatsApp-Chat-Analyzer.git
cd WhatsApp-Chat-Analyzer
</pre>

<h3>2️⃣ Install Dependencies</h3>
<pre>
pip install -r requirements.txt
</pre>
<p><em>(If <code>requirements.txt</code> is missing, manually install the required libraries:)</em></p>
<pre>
pip install pandas matplotlib seaborn numpy
</pre>

<h3>3️⃣ Run the Application</h3>
<pre>
python app.py
</pre>

<hr>

<h2>📊 How It Works</h2>

<ol>
    <li>📂 <strong>Upload WhatsApp chat export (<code>chat.txt</code>)</strong></li>
    <li>▶️ <strong>Run <code>app.py</code></strong> to process chat data</li>
    <li>🔍 <strong>The script extracts metadata:</strong>
        <ul>
            <li>📅 Date & Time</li>
            <li>🧑‍🤝‍🧑 Usernames</li>
            <li>💬 Messages & Links</li>
        </ul>
    </li>
    <li>📈 <strong>Generate Insights & Visualizations</strong>
        <ul>
            <li>🏆 Most active users</li>
            <li>⏰ Message frequency over time</li>
            <li>🔍 Word & emoji analysis</li>
        </ul>
    </li>
    <li>🛠️ <strong>Filter messages using custom stopwords</strong></li>
</ol>

<hr>

<h2>📈 Sample Insights</h2>

<ul>
    <li>🟢 <strong>Most Active Users</strong></li>
    <li>📊 <strong>Messages Sent per Hour</strong></li>
    <li>📅 <strong>Daily/Monthly Message Trends</strong></li>
    <li>💬 <strong>Top Words & Emoji Usage</strong></li>
</ul>



https://github.com/user-attachments/assets/0c594fdc-ea61-4417-9906-4b100cbb787f



<hr>

<h2>🤝 Contributing</h2>

<p>Want to enhance the project? Feel free to:</p>
<ul>
    <li>🛠️ <strong>Fork</strong> the repository</li>
    <li>✨ Add new features</li>
    <li>🔄 Submit a <strong>pull request</strong></li>
</ul>

<hr>

<h2>👩‍💻 Author</h2>
<p><strong>Akansha Kaduskar</strong></p>
<p>📧 <a href="mailto:akanshakaduskar@gmail.com">akanshakaduskar@gmail.com</a></p>
<p>🔗 <a href="https://github.com/akanshakaduskar">GitHub Profile</a></p>

<h2>📜 License</h2>
<p>This project is open-source under the <strong>MIT License</strong>.</p>
