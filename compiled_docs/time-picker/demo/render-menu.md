{"title":"自定义渲染时间选择菜单","meta":{"title":"自定义渲染时间选择菜单","description":"\n<p>可以通过 <code>renderTimeMenuItems</code> 来自定义渲染下拉菜单每一项。</p>\n","order":"5"},"codes":{"jsx":"import { TimePicker } from '@alifd/next';\n\nconst renderTimeMenuItems = (list) => {\n    return list.map(({ label, value }) => {\n        return {\n            value,\n            label: value > 9 ? String(value) : `0${value}`\n        };\n    });\n};\n\nReactDOM.render(<TimePicker renderTimeMenuItems={renderTimeMenuItems} />, mountNode);\n"},"body":"\n\n````jsx\nimport { TimePicker } from '@alifd/next';\n\nconst renderTimeMenuItems = (list) => {\n    return list.map(({ label, value }) => {\n        return {\n            value,\n            label: value > 9 ? String(value) : `0${value}`\n        };\n    });\n};\n\nReactDOM.render(<TimePicker renderTimeMenuItems={renderTimeMenuItems} />, mountNode);\n````","html":"<script>(function(){'use strict';\n\nvar _next = require('@alifd/next');\n\nvar renderTimeMenuItems = function renderTimeMenuItems(list) {\n    return list.map(function (_ref) {\n        var label = _ref.label,\n            value = _ref.value;\n\n        return {\n            value: value,\n            label: value > 9 ? String(value) : '0' + value\n        };\n    });\n};\n\nReactDOM.render(React.createElement(_next.TimePicker, { renderTimeMenuItems: renderTimeMenuItems }), mountNode);})()</script><div class=\"highlight\"><pre class=\"language-jsx\"><code class=\"language-jsx\"><span class=\"token keyword\">import</span> <span class=\"token punctuation\">{</span> TimePicker <span class=\"token punctuation\">}</span> <span class=\"token keyword\">from</span> <span class=\"token string\">'@alifd/next'</span><span class=\"token punctuation\">;</span>\n\n<span class=\"token keyword\">const</span> <span class=\"token function-variable function\">renderTimeMenuItems</span> <span class=\"token operator\">=</span> <span class=\"token punctuation\">(</span><span class=\"token parameter\">list</span><span class=\"token punctuation\">)</span> <span class=\"token operator\">=></span> <span class=\"token punctuation\">{</span>\n    <span class=\"token keyword\">return</span> list<span class=\"token punctuation\">.</span><span class=\"token function\">map</span><span class=\"token punctuation\">(</span><span class=\"token punctuation\">(</span><span class=\"token parameter\"><span class=\"token punctuation\">{</span> label<span class=\"token punctuation\">,</span> value <span class=\"token punctuation\">}</span></span><span class=\"token punctuation\">)</span> <span class=\"token operator\">=></span> <span class=\"token punctuation\">{</span>\n        <span class=\"token keyword\">return</span> <span class=\"token punctuation\">{</span>\n            value<span class=\"token punctuation\">,</span>\n            label<span class=\"token operator\">:</span> value <span class=\"token operator\">></span> <span class=\"token number\">9</span> <span class=\"token operator\">?</span> <span class=\"token function\">String</span><span class=\"token punctuation\">(</span>value<span class=\"token punctuation\">)</span> <span class=\"token operator\">:</span> <span class=\"token template-string\"><span class=\"token template-punctuation string\">`</span><span class=\"token string\">0</span><span class=\"token interpolation\"><span class=\"token interpolation-punctuation punctuation\">${</span>value<span class=\"token interpolation-punctuation punctuation\">}</span></span><span class=\"token template-punctuation string\">`</span></span>\n        <span class=\"token punctuation\">}</span><span class=\"token punctuation\">;</span>\n    <span class=\"token punctuation\">}</span><span class=\"token punctuation\">)</span><span class=\"token punctuation\">;</span>\n<span class=\"token punctuation\">}</span><span class=\"token punctuation\">;</span>\n\nReactDOM<span class=\"token punctuation\">.</span><span class=\"token function\">render</span><span class=\"token punctuation\">(</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">TimePicker</span></span> <span class=\"token attr-name\">renderTimeMenuItems</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span>renderTimeMenuItems<span class=\"token punctuation\">}</span></span> <span class=\"token punctuation\">/></span></span><span class=\"token punctuation\">,</span> mountNode<span class=\"token punctuation\">)</span><span class=\"token punctuation\">;</span></code></pre></div>"}