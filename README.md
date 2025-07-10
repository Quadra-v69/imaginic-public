<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Imaginic API - Image Proxy Service</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      max-width: 720px;
      margin: auto;
      padding: 2rem;
      line-height: 1.6;
    }
    code {
      background: #f4f4f4;
      padding: 2px 4px;
      border-radius: 4px;
    }
    pre {
      background: #f9f9f9;
      padding: 1rem;
      border-radius: 8px;
      overflow-x: auto;
    }
    footer {
      margin-top: 3rem;
      font-size: 0.9rem;
    }
    a {
      color: #007acc;
      text-decoration: none;
    }
  </style>
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
