{"title":"Basic","meta":{"title":"Basic","description":"\n<p>Use SplitButton as Button.</p>\n","order":"0"},"codes":{"jsx":"import { SplitButton } from '@alifd/next';\n\nconst { Item } = SplitButton;\nconst menu = ['Undo', 'Redo', 'Cut', 'Copy', 'Paste'].map(item => <Item key={item}>{item}</Item>);\n\nReactDOM.render(<div>\n    <SplitButton label=\"Edit Document\">{menu}</SplitButton> &nbsp; &nbsp;\n    <SplitButton label=\"Edit Document\" type=\"primary\">{menu}</SplitButton>&nbsp;&nbsp;\n    <SplitButton label=\"Edit Document\" type=\"secondary\">{menu}</SplitButton><br /><br />\n</div>, mountNode);\n"},"body":"\n````jsx\nimport { SplitButton } from '@alifd/next';\n\nconst { Item } = SplitButton;\nconst menu = ['Undo', 'Redo', 'Cut', 'Copy', 'Paste'].map(item => <Item key={item}>{item}</Item>);\n\nReactDOM.render(<div>\n    <SplitButton label=\"Edit Document\">{menu}</SplitButton> &nbsp; &nbsp;\n    <SplitButton label=\"Edit Document\" type=\"primary\">{menu}</SplitButton>&nbsp;&nbsp;\n    <SplitButton label=\"Edit Document\" type=\"secondary\">{menu}</SplitButton><br /><br />\n</div>, mountNode);\n````","html":"<script>(function(){'use strict';\n\nvar _next = require('@alifd/next');\n\nvar Item = _next.SplitButton.Item;\n\nvar menu = ['Undo', 'Redo', 'Cut', 'Copy', 'Paste'].map(function (item) {\n    return React.createElement(\n        Item,\n        { key: item },\n        item\n    );\n});\n\nReactDOM.render(React.createElement(\n    'div',\n    null,\n    React.createElement(\n        _next.SplitButton,\n        { label: 'Edit Document' },\n        menu\n    ),\n    ' \\xA0 \\xA0',\n    React.createElement(\n        _next.SplitButton,\n        { label: 'Edit Document', type: 'primary' },\n        menu\n    ),\n    '\\xA0\\xA0',\n    React.createElement(\n        _next.SplitButton,\n        { label: 'Edit Document', type: 'secondary' },\n        menu\n    ),\n    React.createElement('br', null),\n    React.createElement('br', null)\n), mountNode);})()</script><div class=\"highlight\"><pre class=\"language-jsx\"><code class=\"language-jsx\"><span class=\"token keyword\">import</span> <span class=\"token punctuation\">{</span> SplitButton <span class=\"token punctuation\">}</span> <span class=\"token keyword\">from</span> <span class=\"token string\">'@alifd/next'</span><span class=\"token punctuation\">;</span>\n\n<span class=\"token keyword\">const</span> <span class=\"token punctuation\">{</span> Item <span class=\"token punctuation\">}</span> <span class=\"token operator\">=</span> SplitButton<span class=\"token punctuation\">;</span>\n<span class=\"token keyword\">const</span> menu <span class=\"token operator\">=</span> <span class=\"token punctuation\">[</span><span class=\"token string\">'Undo'</span><span class=\"token punctuation\">,</span> <span class=\"token string\">'Redo'</span><span class=\"token punctuation\">,</span> <span class=\"token string\">'Cut'</span><span class=\"token punctuation\">,</span> <span class=\"token string\">'Copy'</span><span class=\"token punctuation\">,</span> <span class=\"token string\">'Paste'</span><span class=\"token punctuation\">]</span><span class=\"token punctuation\">.</span><span class=\"token function\">map</span><span class=\"token punctuation\">(</span>item <span class=\"token operator\">=></span> <span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>Item</span> <span class=\"token attr-name\">key</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span>item<span class=\"token punctuation\">}</span></span><span class=\"token punctuation\">></span></span><span class=\"token punctuation\">{</span>item<span class=\"token punctuation\">}</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span>Item</span><span class=\"token punctuation\">></span></span><span class=\"token punctuation\">)</span><span class=\"token punctuation\">;</span>\n\nReactDOM<span class=\"token punctuation\">.</span><span class=\"token function\">render</span><span class=\"token punctuation\">(</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>div</span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n    </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>SplitButton</span> <span class=\"token attr-name\">label</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>Edit Document<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token punctuation\">{</span>menu<span class=\"token punctuation\">}</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span>SplitButton</span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\"> &amp;nbsp; &amp;nbsp;\n    </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>SplitButton</span> <span class=\"token attr-name\">label</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>Edit Document<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">type</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>primary<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token punctuation\">{</span>menu<span class=\"token punctuation\">}</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span>SplitButton</span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">&amp;nbsp;&amp;nbsp;\n    </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>SplitButton</span> <span class=\"token attr-name\">label</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>Edit Document<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">type</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>secondary<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token punctuation\">{</span>menu<span class=\"token punctuation\">}</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span>SplitButton</span><span class=\"token punctuation\">></span></span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>br</span> <span class=\"token punctuation\">/></span></span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>br</span> <span class=\"token punctuation\">/></span></span><span class=\"token plain-text\">\n</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span>div</span><span class=\"token punctuation\">></span></span><span class=\"token punctuation\">,</span> mountNode<span class=\"token punctuation\">)</span><span class=\"token punctuation\">;</span></code></pre></div>"}