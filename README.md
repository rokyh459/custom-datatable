  <h1>📊 Custom jQuery DataTable</h1>

  <p>This project demonstrates a fully customizable jQuery DataTable with styled search input, pagination, export buttons, and row length selector using DataTables.js and its extensions.</p>

  <h2>🚀 Features</h2>
  <ul>
    <li>Responsive layout</li>
    <li>Styled search box with placeholder</li>
    <li>Custom-styled pagination controls</li>
    <li>Export buttons (Copy, CSV, Excel, PDF, Print)</li>
    <li>Column visibility toggle</li>
    <li>Styled "Show entries" dropdown</li>
    <li>Select2 integration (optional)</li>
  </ul>

  <h2>📦 Dependencies (via CDN)</h2>
  <ul>
    <li>jQuery</li>
    <li>DataTables.js</li>
    <li>DataTables Buttons Extension</li>
    <li>JSZip & pdfMake (for Excel/PDF export)</li>
    <li>Bootstrap (optional for styling)</li>
    <li>Select2 (optional for custom dropdown)</li>
  </ul>

  <h2>📁 File Structure</h2>
  <pre><code>custom-jquery-datatable/
├── index.html
├── style.css
└── README.html
</code></pre>

  <h2>🔧 Setup Instructions</h2>
  <ol>
    <li>Clone or download the repository:</li>
  </ol>

  <pre><code>git clone https://github.com/your-username/custom-jquery-datatable.git
cd custom-jquery-datatable
</code></pre>

  <p>2. Open <code>index.html</code> in your browser to see the demo.</p>
  <blockquote>
    💡 No build tools required. Works directly in browser using CDN.
  </blockquote>

  <h2>🛠 Customization</h2>

  <h3>Length Menu</h3>
  <pre><code>lengthMenu: [
  [5, 10, 25, 50, 100, -1],
  [5, 10, 25, 50, 100, "All"]
],
pageLength: 10,
</code></pre>

  <h3>Language Settings</h3>
  <pre><code>language: {
  search: "_INPUT_",
  searchPlaceholder: "🔍 Search...",
  lengthMenu: "🔢 Show _MENU_ rows",
  paginate: {
    previous: "←",
    next: "→"
  }
}
</code></pre>

  <h3>CSS Styling</h3>
  <pre><code>.dataTables_filter input {
  padding: 6px 12px;
  border-radius: 8px;
  border: 1px solid #ccc;
}
</code></pre>

  <h2>✅ Live Demo</h2>
  <p>Include a link to GitHub Pages or <a href="#">JSFiddle/CodePen</a> (optional).</p>

  <h2>📄 License</h2>
  <p>This project is open-source under the MIT License.</p>

  <hr/>
  <p>Built with ❤️ using jQuery + DataTables.js</p>
