⚛️ Counter Button (React App)

A simple React Counter App built using HTML and CDN links — no build tools or setup needed!
It demonstrates how React can be used directly in the browser to update UI dynamically.


---



## 🚀 Live Demo

🔗 [View on GitHub Pages](https://anit81.github.io/Counter-buttton/)



---

📝 Features

Increase and decrease the counter value

Reset the counter

Real-time updates using React’s useState hook



---

💻 Technologies Used

React (via CDN)

ReactDOM (via CDN)

HTML

CSS

JavaScript (ES6)



---

⚙️ How It Works

The app is written in a single HTML file that includes React and ReactDOM from a CDN.
The React code is written in a <script type="text/babel"> block, which uses JSX directly in the browser.

Example snippet:

<script type="text/babel">  
  function App() {  
    const [count, setCount] = React.useState(0);  
    return (  
      <div>  
        <h1>{count}</h1>  
        <button onClick={() => setCount(count + 1)}>Increase</button>  
        <button onClick={() => setCount(count - 1)}>Decrease</button>  
        <button onClick={() => setCount(0)}>Reset</button>  
      </div>  
    );  
  }  
  ReactDOM.render(<App />, document.getElementById('root'));  
</script>  
  
  
---  
  
📂 Project Structure  
  
Counter-buttton/  
│  
└── index.html   # Main file containing all React code  
  
  
---  
  
👩‍💻 Author: Anit81  
✨ Built with React and love for learning frontend development — no complicated setup, just creativity!  
  
---  
  
✅ Then:    
1. Go to your GitHub repo → click **Add file → Create new file**    
2. Name it:  
  
README.md  
  
3. Paste **everything above** into the box    
4. Click **Commit changes**  
  
After that, refresh your repository homepage — your README will appear beautifully formatted with headings, code blocks, and emojis 🌟

