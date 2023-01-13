# health care bot

Try it out under https://mingz6.github.io/health-care-chatbot/.

- NPM install

Insert the following code to .\health-care-chatbot\node_modules\react-scripts\config\webpack.config.js
line 305
    resolve: {
      fallback: { 
        "stream": require.resolve("stream-browserify")
        },

- NPM run 


