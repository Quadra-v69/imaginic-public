
</head>
<body>
  <h1>🧠 Imaginic API</h1>
  <p><strong>Convert prompts to AI-generated images via a proxy API and get them as base64.</strong></p>

  <h2>🚀 Usage</h2>
  <p>Send a POST request to:</p>
  <pre>https://imaginic.netlify.app/api/v2</pre>

  <p><strong>Request body (JSON):</strong></p>
  <pre>
{
  "prompt": "a man running in the street",
  "width": 1024,
  "height": 1024
}
  </pre>

  <p><strong>Sample <code>curl</code> request:</strong></p>
  <pre>
curl -X POST https://imaginic.netlify.app/api/v2 \
  -H "Content-Type: application/json" \
  -d '{"prompt":"a man running in the street","width":1024,"height":1024}'
  </pre>

  <p><strong>Response:</strong></p>
  <pre>
{
  "success": true,
  "base64": "data:image/png;base64,iVBORw0K..."
}
  </pre>

  <h2>🧪 <a href="/test">Try the Test Page</a></h2>

  <footer>
    <p>Created by <strong>Rantu Dev</strong></p>
    <p>
      🔗 <a href="https://github.com/quadra-v69" target="_blank">GitHub</a> |
      💼 <a href="https://linkedin.com/in/rantu-dev" target="_blank">LinkedIn</a> |
      🐦 <a href="https://x.com/Quadra_v69" target="_blank">X (Twitter)</a>
    </p>
  </footer>
</body>
</html>
