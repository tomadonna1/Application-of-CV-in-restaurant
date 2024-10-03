<h1>Hands-Free Food Ordering: A Gesture-Based Interface for Restaurants</h1>

<h2>Project Description</h2>

<p>This is a university project. The motivation behind this project is to 
propose a gesture-based food ordering system to enhance the dinning experience for those with hearing impairments. The system works by the user navigating the food menu by raising gesture "5". To confirm
the order they raise a thumps up, to cancel the raise a thumps down.</p>

<h2>🎥 Demo</h2>

<p>Check out the demo of <strong>Hand gesture ordering</strong> in action below!</p>
<img src="picture.png" alt="Demo" style="max-width:100%;">

[![Watch the video](https://github.com/tomadonna1/Application-of-CV-in-restaurant/picture.png)](https://www.youtube.com/watch?v=y6HRzDvJ3Po)

<p align="center">
  The demo could also be found at: https://www.youtube.com/watch?v=y6HRzDvJ3Po
</p>

<p><em>In the demo, you can see a real-time drawing of "I ❤️ U" using hand gestures.</em></p>

<h2>✨ Features</h2>
<ul>
  <li>⚡ Real-time hand landmarks detection</li>
  <li>✍️ Gesture-based drawing visualization</li>
  <li>🖥️ Easy to use interface</li>
  <li>🎯 High accuracy with <strong>MediaPipe</strong></li>
  <li>🎨 Customizable drawing colors and shapes</li>
</ul>

<h2>⚙️ Installation</h2>

<p>Follow the steps below to set up and run this project on your local machine.</p>

<h3>📦 Prerequisites</h3>
<p>Ensure you have Python installed on your system. Then install the necessary libraries.</p>

<pre><code>pip install opencv-python mediapipe</code></pre>

<h3>🛠️ Cloning the Repository</h3>
<p>Clone the repository to your local machine:</p>

<pre><code>git clone https://github.com/your-username/HandDraw.git
cd HandDraw</code></pre>

<h3>▶️ Running the Project</h3>
<p>Once installed, you can run the project by executing the Python script.</p>

<pre><code>python hand_love.py</code></pre>

<p>You will see a window pop up, and the camera will start capturing hand gestures in real-time, turning them into drawings.</p>

<h2>🚀 Usage</h2>
<ol>
  <li>📸 Make sure your camera is enabled and pointing toward your hand.</li>
  <li>🖍️ Use your index finger to choose a color on the screen.</li>
  <li>🖌️ Use your index finger and thumb to draw on the screen.</li>
  <li>🎉 Explore different gestures to create fun shapes and designs!</li>
</ol>

<h2>🧠 How it Works</h2>

<ul>
  <li>📷 <strong>MediaPipe</strong> detects hand landmarks in real-time from the camera input.</li>
  <li>🖼️ <strong>OpenCV</strong> processes these landmarks and converts them into drawing strokes on the screen.</li>
  <li>✋ The program allows users to draw by moving their hands, simulating pen-like behavior in the air.</li>
</ul>

<h2>🔮 Future Improvements</h2>
<ul>
  <li>🧩 Adding more gesture types for different actions (e.g., undo, change color).</li>
  <li>🤚 Extending the project to recognize multiple hands and gestures simultaneously.</li>
  <li>🖥️ Enhancing the UI for a more interactive experience.</li>
</ul>
