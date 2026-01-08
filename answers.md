1. In one sentence: What does res.render(view, data) do?
renders a server-side template into HTML using the provided data and sends the resulting HTML as the HTTP response.

2. What is the difference between <%= %> and <%- %>?
outputs escaped HTML, while <%- %> outputs unescaped/raw HTML.

3. Where does Express look for EJS templates (folder path)?
Express looks for EJS templates in the views/ directory by default