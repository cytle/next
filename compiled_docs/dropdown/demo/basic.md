{"title":"基本","meta":{"title":"基本","description":"\n<p>最简单的用法。</p>\n","order":"0"},"codes":{"jsx":"import { Dropdown, Menu } from '@alifd/next';\n\nconst menu = (\n    <Menu>\n        <Menu.Item>Option 1</Menu.Item>\n        <Menu.Item>Option 2</Menu.Item>\n        <Menu.Item>Option 3</Menu.Item>\n        <Menu.Item>Option 4</Menu.Item>\n    </Menu>\n);\n\nReactDOM.render(\n    <Dropdown trigger={<a>Hello dropdown</a>} afterOpen={() => console.log('after open')}>\n        {menu}\n    </Dropdown>, mountNode);\n"},"body":"\n\n````jsx\nimport { Dropdown, Menu } from '@alifd/next';\n\nconst menu = (\n    <Menu>\n        <Menu.Item>Option 1</Menu.Item>\n        <Menu.Item>Option 2</Menu.Item>\n        <Menu.Item>Option 3</Menu.Item>\n        <Menu.Item>Option 4</Menu.Item>\n    </Menu>\n);\n\nReactDOM.render(\n    <Dropdown trigger={<a>Hello dropdown</a>} afterOpen={() => console.log('after open')}>\n        {menu}\n    </Dropdown>, mountNode);\n````","html":"<script>(function(){'use strict';\n\nvar _next = require('@alifd/next');\n\nvar menu = React.createElement(\n    _next.Menu,\n    null,\n    React.createElement(\n        _next.Menu.Item,\n        null,\n        'Option 1'\n    ),\n    React.createElement(\n        _next.Menu.Item,\n        null,\n        'Option 2'\n    ),\n    React.createElement(\n        _next.Menu.Item,\n        null,\n        'Option 3'\n    ),\n    React.createElement(\n        _next.Menu.Item,\n        null,\n        'Option 4'\n    )\n);\n\nReactDOM.render(React.createElement(\n    _next.Dropdown,\n    { trigger: React.createElement(\n            'a',\n            null,\n            'Hello dropdown'\n        ), afterOpen: function afterOpen() {\n            return console.log('after open');\n        } },\n    menu\n), mountNode);})()</script><div class=\"highlight\"><pre class=\"language-jsx\"><code class=\"language-jsx\"><span class=\"token keyword\">import</span> <span class=\"token punctuation\">{</span> Dropdown<span class=\"token punctuation\">,</span> Menu <span class=\"token punctuation\">}</span> <span class=\"token keyword\">from</span> <span class=\"token string\">'@alifd/next'</span><span class=\"token punctuation\">;</span>\n\n<span class=\"token keyword\">const</span> menu <span class=\"token operator\">=</span> <span class=\"token punctuation\">(</span>\n    <span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Menu</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Menu.Item</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">Option 1</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Menu.Item</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Menu.Item</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">Option 2</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Menu.Item</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Menu.Item</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">Option 3</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Menu.Item</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Menu.Item</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">Option 4</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Menu.Item</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n    </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Menu</span></span><span class=\"token punctuation\">></span></span>\n<span class=\"token punctuation\">)</span><span class=\"token punctuation\">;</span>\n\nReactDOM<span class=\"token punctuation\">.</span><span class=\"token function\">render</span><span class=\"token punctuation\">(</span>\n    <span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Dropdown</span></span> <span class=\"token attr-name\">trigger</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>a</span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">Hello dropdown</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span>a</span><span class=\"token punctuation\">></span></span><span class=\"token punctuation\">}</span></span> <span class=\"token attr-name\">afterOpen</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span><span class=\"token punctuation\">(</span><span class=\"token punctuation\">)</span> <span class=\"token operator\">=></span> console<span class=\"token punctuation\">.</span><span class=\"token function\">log</span><span class=\"token punctuation\">(</span><span class=\"token string\">'after open'</span><span class=\"token punctuation\">)</span><span class=\"token punctuation\">}</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n        </span><span class=\"token punctuation\">{</span>menu<span class=\"token punctuation\">}</span><span class=\"token plain-text\">\n    </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Dropdown</span></span><span class=\"token punctuation\">></span></span><span class=\"token punctuation\">,</span> mountNode<span class=\"token punctuation\">)</span><span class=\"token punctuation\">;</span></code></pre></div>"}