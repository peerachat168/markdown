---


---

<h2 id="get---employee-list">GET - Employee List</h2>
<pre class=" language-mermaid"><svg id="mermaid-svg-ij40GcOgRhd4oEy6" width="100%" xmlns="http://www.w3.org/2000/svg" height="353" style="max-width: 694px;" viewBox="-50 -10 694 353"><style>#mermaid-svg-ij40GcOgRhd4oEy6{font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:16px;fill:#000000;}#mermaid-svg-ij40GcOgRhd4oEy6 .error-icon{fill:#552222;}#mermaid-svg-ij40GcOgRhd4oEy6 .error-text{fill:#552222;stroke:#552222;}#mermaid-svg-ij40GcOgRhd4oEy6 .edge-thickness-normal{stroke-width:2px;}#mermaid-svg-ij40GcOgRhd4oEy6 .edge-thickness-thick{stroke-width:3.5px;}#mermaid-svg-ij40GcOgRhd4oEy6 .edge-pattern-solid{stroke-dasharray:0;}#mermaid-svg-ij40GcOgRhd4oEy6 .edge-pattern-dashed{stroke-dasharray:3;}#mermaid-svg-ij40GcOgRhd4oEy6 .edge-pattern-dotted{stroke-dasharray:2;}#mermaid-svg-ij40GcOgRhd4oEy6 .marker{fill:#666;stroke:#666;}#mermaid-svg-ij40GcOgRhd4oEy6 .marker.cross{stroke:#666;}#mermaid-svg-ij40GcOgRhd4oEy6 svg{font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:16px;}#mermaid-svg-ij40GcOgRhd4oEy6 .actor{stroke:hsl(0,0%,83%);fill:#eee;}#mermaid-svg-ij40GcOgRhd4oEy6 text.actor > tspan{fill:#333;stroke:none;}#mermaid-svg-ij40GcOgRhd4oEy6 .actor-line{stroke:#666;}#mermaid-svg-ij40GcOgRhd4oEy6 .messageLine0{stroke-width:1.5;stroke-dasharray:none;stroke:#333;}#mermaid-svg-ij40GcOgRhd4oEy6 .messageLine1{stroke-width:1.5;stroke-dasharray:2,2;stroke:#333;}#mermaid-svg-ij40GcOgRhd4oEy6 #arrowhead path{fill:#333;stroke:#333;}#mermaid-svg-ij40GcOgRhd4oEy6 .sequenceNumber{fill:white;}#mermaid-svg-ij40GcOgRhd4oEy6 #sequencenumber{fill:#333;}#mermaid-svg-ij40GcOgRhd4oEy6 #crosshead path{fill:#333;stroke:#333;}#mermaid-svg-ij40GcOgRhd4oEy6 .messageText{fill:#333;stroke:#333;}#mermaid-svg-ij40GcOgRhd4oEy6 .labelBox{stroke:hsl(0,0%,83%);fill:#eee;}#mermaid-svg-ij40GcOgRhd4oEy6 .labelText,#mermaid-svg-ij40GcOgRhd4oEy6 .labelText > tspan{fill:#333;stroke:none;}#mermaid-svg-ij40GcOgRhd4oEy6 .loopText,#mermaid-svg-ij40GcOgRhd4oEy6 .loopText > tspan{fill:#333;stroke:none;}#mermaid-svg-ij40GcOgRhd4oEy6 .loopLine{stroke-width:2px;stroke-dasharray:2,2;stroke:hsl(0,0%,83%);fill:hsl(0,0%,83%);}#mermaid-svg-ij40GcOgRhd4oEy6 .note{stroke:hsl(60,100%,23.3333333333%);fill:#ffa;}#mermaid-svg-ij40GcOgRhd4oEy6 .noteText,#mermaid-svg-ij40GcOgRhd4oEy6 .noteText > tspan{fill:#333;stroke:none;}#mermaid-svg-ij40GcOgRhd4oEy6 .activation0{fill:#f4f4f4;stroke:#666;}#mermaid-svg-ij40GcOgRhd4oEy6 .activation1{fill:#f4f4f4;stroke:#666;}#mermaid-svg-ij40GcOgRhd4oEy6 .activation2{fill:#f4f4f4;stroke:#666;}#mermaid-svg-ij40GcOgRhd4oEy6:root{--mermaid-font-family:"trebuchet ms",verdana,arial,sans-serif;}#mermaid-svg-ij40GcOgRhd4oEy6 sequence{fill:apa;}</style><g></g><g><line id="actor974" x1="75" y1="5" x2="75" y2="342" class="actor-line" stroke-width="0.5px" stroke="#999"></line><rect x="0" y="0" fill="#eaeaea" stroke="#666" width="150" height="65" rx="3" ry="3" class="actor"></rect><text x="75" y="32.5" dominant-baseline="central" alignment-baseline="central" class="actor" style="text-anchor: middle; font-size: 14px; font-weight: 400; font-family: Open-Sans, &quot;sans-serif&quot;;"><tspan x="75" dy="0">Admin</tspan></text></g><g><line id="actor975" x1="293" y1="5" x2="293" y2="342" class="actor-line" stroke-width="0.5px" stroke="#999"></line><rect x="218" y="0" fill="#eaeaea" stroke="#666" width="150" height="65" rx="3" ry="3" class="actor"></rect><text x="293" y="32.5" dominant-baseline="central" alignment-baseline="central" class="actor" style="text-anchor: middle; font-size: 14px; font-weight: 400; font-family: Open-Sans, &quot;sans-serif&quot;;"><tspan x="293" dy="0">System</tspan></text></g><g><line id="actor976" x1="519" y1="5" x2="519" y2="342" class="actor-line" stroke-width="0.5px" stroke="#999"></line><rect x="444" y="0" fill="#eaeaea" stroke="#666" width="150" height="65" rx="3" ry="3" class="actor"></rect><text x="519" y="32.5" dominant-baseline="central" alignment-baseline="central" class="actor" style="text-anchor: middle; font-size: 14px; font-weight: 400; font-family: Open-Sans, &quot;sans-serif&quot;;"><tspan x="519" dy="0">Database</tspan></text></g><defs><marker id="arrowhead" refX="9" refY="5" markerUnits="userSpaceOnUse" markerWidth="12" markerHeight="12" orient="auto"><path d="M 0 0 L 10 5 L 0 10 z"></path></marker></defs><defs><marker id="crosshead" markerWidth="15" markerHeight="8" orient="auto" refX="16" refY="4"><path fill="black" stroke="#000000" stroke-width="1px" d="M 9,2 V 6 L16,4 Z" style="stroke-dasharray: 0, 0;"></path><path fill="none" stroke="#000000" stroke-width="1px" d="M 0,1 L 6,7 M 6,1 L 0,7" style="stroke-dasharray: 0, 0;"></path></marker></defs><defs><marker id="filled-head" refX="18" refY="7" markerWidth="20" markerHeight="28" orient="auto"><path d="M 18,7 L9,13 L14,7 L9,1 Z"></path></marker></defs><defs><marker id="sequencenumber" refX="15" refY="15" markerWidth="60" markerHeight="40" orient="auto"><circle cx="15" cy="15" r="6"></circle></marker></defs><text x="184" y="80" text-anchor="middle" dominant-baseline="middle" alignment-baseline="middle" class="messageText" dy="1em" style="font-family: &quot;trebuchet ms&quot;, verdana, arial, sans-serif; font-size: 16px; font-weight: 400;">search employee list</text><line x1="75" y1="113" x2="293" y2="113" class="messageLine0" stroke-width="2" stroke="none" marker-end="url(#arrowhead)" style="fill: none;"></line><text x="406" y="128" text-anchor="middle" dominant-baseline="middle" alignment-baseline="middle" class="messageText" dy="1em" style="font-family: &quot;trebuchet ms&quot;, verdana, arial, sans-serif; font-size: 16px; font-weight: 400;">query employee</text><line x1="293" y1="161" x2="519" y2="161" class="messageLine0" stroke-width="2" stroke="none" marker-end="url(#arrowhead)" style="fill: none;"></line><text x="406" y="176" text-anchor="middle" dominant-baseline="middle" alignment-baseline="middle" class="messageText" dy="1em" style="font-family: &quot;trebuchet ms&quot;, verdana, arial, sans-serif; font-size: 16px; font-weight: 400;">return employee data</text><line x1="519" y1="209" x2="293" y2="209" class="messageLine1" stroke-width="2" stroke="none" marker-end="url(#arrowhead)" style="stroke-dasharray: 3, 3; fill: none;"></line><text x="184" y="224" text-anchor="middle" dominant-baseline="middle" alignment-baseline="middle" class="messageText" dy="1em" style="font-family: &quot;trebuchet ms&quot;, verdana, arial, sans-serif; font-size: 16px; font-weight: 400;">return employee list</text><line x1="293" y1="257" x2="75" y2="257" class="messageLine1" stroke-width="2" stroke="none" marker-end="url(#arrowhead)" style="stroke-dasharray: 3, 3; fill: none;"></line><g><rect x="0" y="277" fill="#eaeaea" stroke="#666" width="150" height="65" rx="3" ry="3" class="actor"></rect><text x="75" y="309.5" dominant-baseline="central" alignment-baseline="central" class="actor" style="text-anchor: middle; font-size: 14px; font-weight: 400; font-family: Open-Sans, &quot;sans-serif&quot;;"><tspan x="75" dy="0">Admin</tspan></text></g><g><rect x="218" y="277" fill="#eaeaea" stroke="#666" width="150" height="65" rx="3" ry="3" class="actor"></rect><text x="293" y="309.5" dominant-baseline="central" alignment-baseline="central" class="actor" style="text-anchor: middle; font-size: 14px; font-weight: 400; font-family: Open-Sans, &quot;sans-serif&quot;;"><tspan x="293" dy="0">System</tspan></text></g><g><rect x="444" y="277" fill="#eaeaea" stroke="#666" width="150" height="65" rx="3" ry="3" class="actor"></rect><text x="519" y="309.5" dominant-baseline="central" alignment-baseline="central" class="actor" style="text-anchor: middle; font-size: 14px; font-weight: 400; font-family: Open-Sans, &quot;sans-serif&quot;;"><tspan x="519" dy="0">Database</tspan></text></g></svg></pre>
<pre><code>/api/admin/employees
</code></pre>
<p><strong>Parameters</strong></p>

<table>
<thead>
<tr>
<th>Name</th>
<th>Type</th>
<th>Mandatory</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td>search</td>
<td>string</td>
<td>no</td>
<td></td>
</tr>
<tr>
<td>employeeStatus</td>
<td>string</td>
<td>no</td>
<td></td>
</tr>
<tr>
<td>percentLogMin</td>
<td>number</td>
<td>no</td>
<td></td>
</tr>
<tr>
<td>percentLogMax</td>
<td>number</td>
<td>no</td>
<td></td>
</tr>
<tr>
<td>lineManager</td>
<td>array</td>
<td>no</td>
<td></td>
</tr>
<tr>
<td>site</td>
<td>array</td>
<td>no</td>
<td></td>
</tr>
<tr>
<td>submittedOnly</td>
<td>boolean</td>
<td>no</td>
<td></td>
</tr>
<tr>
<td>month</td>
<td>string</td>
<td>no</td>
<td></td>
</tr>
<tr>
<td>years</td>
<td>number</td>
<td>no</td>
<td></td>
</tr>
<tr>
<td>sort</td>
<td>string</td>
<td>no</td>
<td></td>
</tr>
<tr>
<td>sortDir</td>
<td>string</td>
<td>no</td>
<td>ASC, DESC</td>
</tr>
<tr>
<td>page</td>
<td>number</td>
<td>no</td>
<td></td>
</tr>
<tr>
<td>pageSize</td>
<td>number</td>
<td>no</td>
<td></td>
</tr>
</tbody>
</table><p><strong>Response  - 200</strong></p>
<pre class=" language-json"><code class="prism  language-json"><span class="token punctuation">{</span>
   <span class="token string">"content"</span><span class="token punctuation">:</span> <span class="token punctuation">[</span>
   	<span class="token punctuation">{</span>
   		<span class="token string">"uuid"</span><span class="token punctuation">:</span> <span class="token string">"6034be7b-a132-4ad9-b571-e3a4f16c572b"</span><span class="token punctuation">,</span>
   		<span class="token string">"firstName"</span><span class="token punctuation">:</span> <span class="token string">"joe"</span><span class="token punctuation">,</span>
   		<span class="token string">"lastName"</span><span class="token punctuation">:</span> <span class="token string">"biden"</span><span class="token punctuation">,</span>
   		<span class="token string">"email"</span><span class="token punctuation">:</span> <span class="token string">"joe@scoutout.net"</span><span class="token punctuation">,</span>
   		<span class="token string">"phone"</span><span class="token punctuation">:</span> <span class="token string">"0812345678"</span><span class="token punctuation">,</span>
   		<span class="token string">"lineManagerUuid"</span><span class="token punctuation">:</span> <span class="token string">"6034be7b-a132-4ad9-b571-e3a4f16c572b"</span><span class="token punctuation">,</span>
   		<span class="token string">"lineManagerName"</span><span class="token punctuation">:</span> <span class="token string">"Som"</span><span class="token punctuation">,</span>
   		<span class="token string">"siteUuid"</span><span class="token punctuation">:</span> <span class="token string">"6034be7b-a132-4ad9-b571-e3a4f16c572b"</span><span class="token punctuation">,</span>
   		<span class="token string">"siteName"</span><span class="token punctuation">:</span> <span class="token string">"SCB"</span><span class="token punctuation">,</span>
   		<span class="token string">"logPercent"</span><span class="token punctuation">:</span> <span class="token number">100</span><span class="token punctuation">,</span>
   		<span class="token string">"status"</span><span class="token punctuation">:</span> <span class="token string">"ACTIVE"</span><span class="token punctuation">,</span>
   		<span class="token string">"lastActiveDateTime"</span><span class="token punctuation">:</span> <span class="token string">"2023-10-02T13:39:36.936Z"</span><span class="token punctuation">,</span>
   		<span class="token string">"createdDateTime"</span><span class="token punctuation">:</span> <span class="token string">"2023-10-02T13:39:36.936Z"</span>
       <span class="token punctuation">}</span><span class="token punctuation">,</span>
       <span class="token punctuation">{</span>
   		<span class="token string">"uuid"</span><span class="token punctuation">:</span> <span class="token string">"6034be7b-a132-4ad9-b571-e3a4f16c572b"</span><span class="token punctuation">,</span>
   		<span class="token string">"firstName"</span><span class="token punctuation">:</span> <span class="token string">"poo"</span><span class="token punctuation">,</span>
   		<span class="token string">"lastName"</span><span class="token punctuation">:</span> <span class="token string">"tin"</span><span class="token punctuation">,</span>
   		<span class="token string">"email"</span><span class="token punctuation">:</span> <span class="token string">"joe@scoutout.net"</span><span class="token punctuation">,</span>
   		<span class="token string">"phone"</span><span class="token punctuation">:</span> <span class="token string">"0812345678"</span><span class="token punctuation">,</span>
   		<span class="token string">"lineManagerUuid"</span><span class="token punctuation">:</span> <span class="token string">"6034be7b-a132-4ad9-b571-e3a4f16c572b"</span><span class="token punctuation">,</span>
   		<span class="token string">"lineManagerName"</span><span class="token punctuation">:</span> <span class="token string">"Bee"</span><span class="token punctuation">,</span>
   		<span class="token string">"siteUuid"</span><span class="token punctuation">:</span> <span class="token string">"6034be7b-a132-4ad9-b571-e3a4f16c572b"</span><span class="token punctuation">,</span>
   		<span class="token string">"siteName"</span><span class="token punctuation">:</span> <span class="token string">"KTB"</span><span class="token punctuation">,</span>
   		<span class="token string">"logPercent"</span><span class="token punctuation">:</span> <span class="token number">70</span><span class="token punctuation">,</span>
   		<span class="token string">"status"</span><span class="token punctuation">:</span> <span class="token string">"ACTIVE"</span><span class="token punctuation">,</span>
   		<span class="token string">"lastActiveDateTime"</span><span class="token punctuation">:</span> <span class="token string">"2023-10-02T13:39:36.936Z"</span><span class="token punctuation">,</span>
   		<span class="token string">"createdDateTime"</span><span class="token punctuation">:</span> <span class="token string">"2023-10-02T13:39:36.936Z"</span>
       <span class="token punctuation">}</span><span class="token punctuation">,</span>
   <span class="token punctuation">]</span>
   <span class="token string">"totalElements"</span><span class="token punctuation">:</span> <span class="token number">48</span><span class="token punctuation">,</span>
   <span class="token string">"totalPages"</span><span class="token punctuation">:</span> <span class="token number">5</span><span class="token punctuation">,</span>
   <span class="token string">"size"</span><span class="token punctuation">:</span> <span class="token number">10</span><span class="token punctuation">,</span>
<span class="token punctuation">}</span>
</code></pre>
<h2 id="put----update-employee">PUT -  Update Employee</h2>
<pre class=" language-mermaid"><svg id="mermaid-svg-k3f3oLcy3Ok9LM2O" width="100%" xmlns="http://www.w3.org/2000/svg" height="401" style="max-width: 710px;" viewBox="-50 -10 710 401"><style>#mermaid-svg-k3f3oLcy3Ok9LM2O{font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:16px;fill:#000000;}#mermaid-svg-k3f3oLcy3Ok9LM2O .error-icon{fill:#552222;}#mermaid-svg-k3f3oLcy3Ok9LM2O .error-text{fill:#552222;stroke:#552222;}#mermaid-svg-k3f3oLcy3Ok9LM2O .edge-thickness-normal{stroke-width:2px;}#mermaid-svg-k3f3oLcy3Ok9LM2O .edge-thickness-thick{stroke-width:3.5px;}#mermaid-svg-k3f3oLcy3Ok9LM2O .edge-pattern-solid{stroke-dasharray:0;}#mermaid-svg-k3f3oLcy3Ok9LM2O .edge-pattern-dashed{stroke-dasharray:3;}#mermaid-svg-k3f3oLcy3Ok9LM2O .edge-pattern-dotted{stroke-dasharray:2;}#mermaid-svg-k3f3oLcy3Ok9LM2O .marker{fill:#666;stroke:#666;}#mermaid-svg-k3f3oLcy3Ok9LM2O .marker.cross{stroke:#666;}#mermaid-svg-k3f3oLcy3Ok9LM2O svg{font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:16px;}#mermaid-svg-k3f3oLcy3Ok9LM2O .actor{stroke:hsl(0,0%,83%);fill:#eee;}#mermaid-svg-k3f3oLcy3Ok9LM2O text.actor > tspan{fill:#333;stroke:none;}#mermaid-svg-k3f3oLcy3Ok9LM2O .actor-line{stroke:#666;}#mermaid-svg-k3f3oLcy3Ok9LM2O .messageLine0{stroke-width:1.5;stroke-dasharray:none;stroke:#333;}#mermaid-svg-k3f3oLcy3Ok9LM2O .messageLine1{stroke-width:1.5;stroke-dasharray:2,2;stroke:#333;}#mermaid-svg-k3f3oLcy3Ok9LM2O #arrowhead path{fill:#333;stroke:#333;}#mermaid-svg-k3f3oLcy3Ok9LM2O .sequenceNumber{fill:white;}#mermaid-svg-k3f3oLcy3Ok9LM2O #sequencenumber{fill:#333;}#mermaid-svg-k3f3oLcy3Ok9LM2O #crosshead path{fill:#333;stroke:#333;}#mermaid-svg-k3f3oLcy3Ok9LM2O .messageText{fill:#333;stroke:#333;}#mermaid-svg-k3f3oLcy3Ok9LM2O .labelBox{stroke:hsl(0,0%,83%);fill:#eee;}#mermaid-svg-k3f3oLcy3Ok9LM2O .labelText,#mermaid-svg-k3f3oLcy3Ok9LM2O .labelText > tspan{fill:#333;stroke:none;}#mermaid-svg-k3f3oLcy3Ok9LM2O .loopText,#mermaid-svg-k3f3oLcy3Ok9LM2O .loopText > tspan{fill:#333;stroke:none;}#mermaid-svg-k3f3oLcy3Ok9LM2O .loopLine{stroke-width:2px;stroke-dasharray:2,2;stroke:hsl(0,0%,83%);fill:hsl(0,0%,83%);}#mermaid-svg-k3f3oLcy3Ok9LM2O .note{stroke:hsl(60,100%,23.3333333333%);fill:#ffa;}#mermaid-svg-k3f3oLcy3Ok9LM2O .noteText,#mermaid-svg-k3f3oLcy3Ok9LM2O .noteText > tspan{fill:#333;stroke:none;}#mermaid-svg-k3f3oLcy3Ok9LM2O .activation0{fill:#f4f4f4;stroke:#666;}#mermaid-svg-k3f3oLcy3Ok9LM2O .activation1{fill:#f4f4f4;stroke:#666;}#mermaid-svg-k3f3oLcy3Ok9LM2O .activation2{fill:#f4f4f4;stroke:#666;}#mermaid-svg-k3f3oLcy3Ok9LM2O:root{--mermaid-font-family:"trebuchet ms",verdana,arial,sans-serif;}#mermaid-svg-k3f3oLcy3Ok9LM2O sequence{fill:apa;}</style><g></g><g><line id="actor977" x1="75" y1="5" x2="75" y2="390" class="actor-line" stroke-width="0.5px" stroke="#999"></line><rect x="0" y="0" fill="#eaeaea" stroke="#666" width="150" height="65" rx="3" ry="3" class="actor"></rect><text x="75" y="32.5" dominant-baseline="central" alignment-baseline="central" class="actor" style="text-anchor: middle; font-size: 14px; font-weight: 400; font-family: Open-Sans, &quot;sans-serif&quot;;"><tspan x="75" dy="0">Admin</tspan></text></g><g><line id="actor978" x1="335" y1="5" x2="335" y2="390" class="actor-line" stroke-width="0.5px" stroke="#999"></line><rect x="260" y="0" fill="#eaeaea" stroke="#666" width="150" height="65" rx="3" ry="3" class="actor"></rect><text x="335" y="32.5" dominant-baseline="central" alignment-baseline="central" class="actor" style="text-anchor: middle; font-size: 14px; font-weight: 400; font-family: Open-Sans, &quot;sans-serif&quot;;"><tspan x="335" dy="0">System</tspan></text></g><g><line id="actor979" x1="535" y1="5" x2="535" y2="390" class="actor-line" stroke-width="0.5px" stroke="#999"></line><rect x="460" y="0" fill="#eaeaea" stroke="#666" width="150" height="65" rx="3" ry="3" class="actor"></rect><text x="535" y="32.5" dominant-baseline="central" alignment-baseline="central" class="actor" style="text-anchor: middle; font-size: 14px; font-weight: 400; font-family: Open-Sans, &quot;sans-serif&quot;;"><tspan x="535" dy="0">Database</tspan></text></g><defs><marker id="arrowhead" refX="9" refY="5" markerUnits="userSpaceOnUse" markerWidth="12" markerHeight="12" orient="auto"><path d="M 0 0 L 10 5 L 0 10 z"></path></marker></defs><defs><marker id="crosshead" markerWidth="15" markerHeight="8" orient="auto" refX="16" refY="4"><path fill="black" stroke="#000000" stroke-width="1px" d="M 9,2 V 6 L16,4 Z" style="stroke-dasharray: 0, 0;"></path><path fill="none" stroke="#000000" stroke-width="1px" d="M 0,1 L 6,7 M 6,1 L 0,7" style="stroke-dasharray: 0, 0;"></path></marker></defs><defs><marker id="filled-head" refX="18" refY="7" markerWidth="20" markerHeight="28" orient="auto"><path d="M 18,7 L9,13 L14,7 L9,1 Z"></path></marker></defs><defs><marker id="sequencenumber" refX="15" refY="15" markerWidth="60" markerHeight="40" orient="auto"><circle cx="15" cy="15" r="6"></circle></marker></defs><text x="205" y="80" text-anchor="middle" dominant-baseline="middle" alignment-baseline="middle" class="messageText" dy="1em" style="font-family: &quot;trebuchet ms&quot;, verdana, arial, sans-serif; font-size: 16px; font-weight: 400;">put update employee data</text><line x1="75" y1="113" x2="335" y2="113" class="messageLine0" stroke-width="2" stroke="none" marker-end="url(#arrowhead)" style="fill: none;"></line><text x="435" y="128" text-anchor="middle" dominant-baseline="middle" alignment-baseline="middle" class="messageText" dy="1em" style="font-family: &quot;trebuchet ms&quot;, verdana, arial, sans-serif; font-size: 16px; font-weight: 400;">save to database</text><line x1="335" y1="161" x2="535" y2="161" class="messageLine0" stroke-width="2" stroke="none" marker-end="url(#arrowhead)" style="fill: none;"></line><text x="435" y="176" text-anchor="middle" dominant-baseline="middle" alignment-baseline="middle" class="messageText" dy="1em" style="font-family: &quot;trebuchet ms&quot;, verdana, arial, sans-serif; font-size: 16px; font-weight: 400;">get employee</text><line x1="335" y1="209" x2="535" y2="209" class="messageLine0" stroke-width="2" stroke="none" marker-end="url(#arrowhead)" style="fill: none;"></line><text x="435" y="224" text-anchor="middle" dominant-baseline="middle" alignment-baseline="middle" class="messageText" dy="1em" style="font-family: &quot;trebuchet ms&quot;, verdana, arial, sans-serif; font-size: 16px; font-weight: 400;">return employee</text><line x1="535" y1="257" x2="335" y2="257" class="messageLine1" stroke-width="2" stroke="none" marker-end="url(#arrowhead)" style="stroke-dasharray: 3, 3; fill: none;"></line><text x="205" y="272" text-anchor="middle" dominant-baseline="middle" alignment-baseline="middle" class="messageText" dy="1em" style="font-family: &quot;trebuchet ms&quot;, verdana, arial, sans-serif; font-size: 16px; font-weight: 400;">return employee</text><line x1="335" y1="305" x2="75" y2="305" class="messageLine1" stroke-width="2" stroke="none" marker-end="url(#arrowhead)" style="stroke-dasharray: 3, 3; fill: none;"></line><g><rect x="0" y="325" fill="#eaeaea" stroke="#666" width="150" height="65" rx="3" ry="3" class="actor"></rect><text x="75" y="357.5" dominant-baseline="central" alignment-baseline="central" class="actor" style="text-anchor: middle; font-size: 14px; font-weight: 400; font-family: Open-Sans, &quot;sans-serif&quot;;"><tspan x="75" dy="0">Admin</tspan></text></g><g><rect x="260" y="325" fill="#eaeaea" stroke="#666" width="150" height="65" rx="3" ry="3" class="actor"></rect><text x="335" y="357.5" dominant-baseline="central" alignment-baseline="central" class="actor" style="text-anchor: middle; font-size: 14px; font-weight: 400; font-family: Open-Sans, &quot;sans-serif&quot;;"><tspan x="335" dy="0">System</tspan></text></g><g><rect x="460" y="325" fill="#eaeaea" stroke="#666" width="150" height="65" rx="3" ry="3" class="actor"></rect><text x="535" y="357.5" dominant-baseline="central" alignment-baseline="central" class="actor" style="text-anchor: middle; font-size: 14px; font-weight: 400; font-family: Open-Sans, &quot;sans-serif&quot;;"><tspan x="535" dy="0">Database</tspan></text></g></svg></pre>
<pre><code>/api/admin/employee/{employeeUuid}
</code></pre>
<p><strong>Parameters</strong></p>

<table>
<thead>
<tr>
<th>Name</th>
<th>Type</th>
<th>Mandatory</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td>firstName</td>
<td>string</td>
<td>yes</td>
<td></td>
</tr>
<tr>
<td>lastName</td>
<td>string</td>
<td>yes</td>
<td></td>
</tr>
<tr>
<td>email</td>
<td>string</td>
<td>yes</td>
<td></td>
</tr>
<tr>
<td>phone</td>
<td>string</td>
<td>yes</td>
<td></td>
</tr>
<tr>
<td>lineManagerUuid</td>
<td>string</td>
<td>yes</td>
<td></td>
</tr>
<tr>
<td>siteUuid</td>
<td>string</td>
<td>yes</td>
<td></td>
</tr>
<tr>
<td>status</td>
<td>string</td>
<td>yes</td>
<td>ACTIVE, INACTIVE, RESIGN, CONTRACT_EXPIRED</td>
</tr>
</tbody>
</table><p><strong>Response - 200</strong></p>
<pre class=" language-json"><code class="prism  language-json"><span class="token punctuation">{</span>
   <span class="token string">"uuid"</span><span class="token punctuation">:</span> <span class="token string">"6034be7b-a132-4ad9-b571-e3a4f16c572b"</span><span class="token punctuation">,</span>
   <span class="token string">"firstName"</span><span class="token punctuation">:</span> <span class="token string">"joe"</span><span class="token punctuation">,</span>
   <span class="token string">"lastName"</span><span class="token punctuation">:</span> <span class="token string">"biden"</span><span class="token punctuation">,</span>
   <span class="token string">"email"</span><span class="token punctuation">:</span> <span class="token string">"joe@scoutout.net"</span><span class="token punctuation">,</span>
   <span class="token string">"phone"</span><span class="token punctuation">:</span> <span class="token string">"0812345678"</span><span class="token punctuation">,</span>
   <span class="token string">"lineManagerUuid"</span><span class="token punctuation">:</span> <span class="token string">"6034be7b-a132-4ad9-b571-e3a4f16c572b"</span><span class="token punctuation">,</span>
   <span class="token string">"lineManagerName"</span><span class="token punctuation">:</span> <span class="token string">"Som"</span><span class="token punctuation">,</span>
   <span class="token string">"siteUuid"</span><span class="token punctuation">:</span> <span class="token string">"6034be7b-a132-4ad9-b571-e3a4f16c572b"</span><span class="token punctuation">,</span>
   <span class="token string">"siteName"</span><span class="token punctuation">:</span> <span class="token string">"SCB"</span><span class="token punctuation">,</span>
   <span class="token string">"logPercent"</span><span class="token punctuation">:</span> <span class="token number">100</span><span class="token punctuation">,</span>
   <span class="token string">"status"</span><span class="token punctuation">:</span> <span class="token string">"ACTIVE"</span><span class="token punctuation">,</span>
   <span class="token string">"lastActiveDateTime"</span><span class="token punctuation">:</span> <span class="token string">"2023-10-02T13:39:36.936Z"</span><span class="token punctuation">,</span>
   <span class="token string">"createdDateTime"</span><span class="token punctuation">:</span> <span class="token string">"2023-10-02T13:39:36.936Z"</span>
<span class="token punctuation">}</span>
</code></pre>
<h2 id="put----update-employee-status">PUT -  Update Employee Status</h2>
<pre><code>/api/admin/employee/{employeeUuid}/status
</code></pre>
<p><strong>Parameters</strong></p>

<table>
<thead>
<tr>
<th>Name</th>
<th>Type</th>
<th>Mandatory</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td>status</td>
<td>string</td>
<td>yes</td>
<td>ACTIVE, INACTIVE, RESIGN, CONTRACT_EXPIRED</td>
</tr>
</tbody>
</table><p><strong>Response - 200</strong></p>
<pre class=" language-json"><code class="prism  language-json"><span class="token punctuation">{</span>
   <span class="token string">"uuid"</span><span class="token punctuation">:</span> <span class="token string">"6034be7b-a132-4ad9-b571-e3a4f16c572b"</span><span class="token punctuation">,</span>
   <span class="token string">"firstName"</span><span class="token punctuation">:</span> <span class="token string">"joe"</span><span class="token punctuation">,</span>
   <span class="token string">"lastName"</span><span class="token punctuation">:</span> <span class="token string">"biden"</span><span class="token punctuation">,</span>
   <span class="token string">"email"</span><span class="token punctuation">:</span> <span class="token string">"joe@scoutout.net"</span><span class="token punctuation">,</span>
   <span class="token string">"phone"</span><span class="token punctuation">:</span> <span class="token string">"0812345678"</span><span class="token punctuation">,</span>
   <span class="token string">"lineManagerUuid"</span><span class="token punctuation">:</span> <span class="token string">"6034be7b-a132-4ad9-b571-e3a4f16c572b"</span><span class="token punctuation">,</span>
   <span class="token string">"lineManagerName"</span><span class="token punctuation">:</span> <span class="token string">"Som"</span><span class="token punctuation">,</span>
   <span class="token string">"siteUuid"</span><span class="token punctuation">:</span> <span class="token string">"6034be7b-a132-4ad9-b571-e3a4f16c572b"</span><span class="token punctuation">,</span>
   <span class="token string">"siteName"</span><span class="token punctuation">:</span> <span class="token string">"SCB"</span><span class="token punctuation">,</span>
   <span class="token string">"logPercent"</span><span class="token punctuation">:</span> <span class="token number">100</span><span class="token punctuation">,</span>
   <span class="token string">"status"</span><span class="token punctuation">:</span> <span class="token string">"ACTIVE"</span><span class="token punctuation">,</span>
   <span class="token string">"lastActiveDateTime"</span><span class="token punctuation">:</span> <span class="token string">"2023-10-02T13:39:36.936Z"</span><span class="token punctuation">,</span>
   <span class="token string">"createdDateTime"</span><span class="token punctuation">:</span> <span class="token string">"2023-10-02T13:39:36.936Z"</span>
<span class="token punctuation">}</span>
</code></pre>
<h2 id="get----line-manager-dashboard">GET -  Line Manager Dashboard</h2>
<pre><code>/api/admin/dashboard/linemanager
</code></pre>
<p><strong>Parameters</strong></p>

<table>
<thead>
<tr>
<th>Name</th>
<th>Type</th>
<th>Mandatory</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td>lineManager</td>
<td>string</td>
<td>no</td>
<td></td>
</tr>
<tr>
<td>month</td>
<td>string</td>
<td>no</td>
<td></td>
</tr>
<tr>
<td>years</td>
<td>number</td>
<td>no</td>
<td></td>
</tr>
<tr>
<td>sort</td>
<td>string</td>
<td>no</td>
<td></td>
</tr>
<tr>
<td>sortDir</td>
<td>string</td>
<td>no</td>
<td>ASC, DESC</td>
</tr>
<tr>
<td>page</td>
<td>number</td>
<td>no</td>
<td></td>
</tr>
<tr>
<td>pageSize</td>
<td>number</td>
<td>no</td>
<td></td>
</tr>
</tbody>
</table><p><strong>Response  - 200</strong></p>
<pre class=" language-json"><code class="prism  language-json"><span class="token punctuation">{</span>
   <span class="token string">"content"</span><span class="token punctuation">:</span> <span class="token punctuation">[</span>
   	<span class="token punctuation">{</span>
   		<span class="token string">"uuid"</span><span class="token punctuation">:</span> <span class="token string">"6034be7b-a132-4ad9-b571-e3a4f16c572b"</span><span class="token punctuation">,</span>
   		<span class="token string">"lineManagerName"</span><span class="token punctuation">:</span> <span class="token string">"Som"</span><span class="token punctuation">,</span>
   		<span class="token string">"notCompleted"</span><span class="token punctuation">:</span> <span class="token number">100</span><span class="token punctuation">,</span>
   		<span class="token string">"complete"</span><span class="token punctuation">:</span> <span class="token number">900</span><span class="token punctuation">,</span>
   		<span class="token string">"employee"</span><span class="token punctuation">:</span> <span class="token number">1000</span><span class="token punctuation">,</span>
   		<span class="token string">"status"</span><span class="token punctuation">:</span> <span class="token string">"ACTIVE"</span><span class="token punctuation">,</span>
   		<span class="token string">"lastActiveDateTime"</span><span class="token punctuation">:</span> <span class="token string">"2023-10-02T13:39:36.936Z"</span><span class="token punctuation">,</span>
   		<span class="token string">"createdDateTime"</span><span class="token punctuation">:</span> <span class="token string">"2023-10-02T13:39:36.936Z"</span>
       <span class="token punctuation">}</span><span class="token punctuation">,</span>
       <span class="token punctuation">{</span>
   		<span class="token string">"uuid"</span><span class="token punctuation">:</span> <span class="token string">"6034be7b-a132-4ad9-b571-e3a4f16c572b"</span><span class="token punctuation">,</span>
   		<span class="token string">"lineManagerName"</span><span class="token punctuation">:</span> <span class="token string">"Bee"</span><span class="token punctuation">,</span>
   		<span class="token string">"notCompleted"</span><span class="token punctuation">:</span> <span class="token number">500</span><span class="token punctuation">,</span>
   		<span class="token string">"complete"</span><span class="token punctuation">:</span> <span class="token number">1500</span><span class="token punctuation">,</span>
   		<span class="token string">"employee"</span><span class="token punctuation">:</span> <span class="token number">2000</span><span class="token punctuation">,</span>
   		<span class="token string">"status"</span><span class="token punctuation">:</span> <span class="token string">"ACTIVE"</span><span class="token punctuation">,</span>
   		<span class="token string">"lastActiveDateTime"</span><span class="token punctuation">:</span> <span class="token string">"2023-10-02T13:39:36.936Z"</span><span class="token punctuation">,</span>
   		<span class="token string">"createdDateTime"</span><span class="token punctuation">:</span> <span class="token string">"2023-10-02T13:39:36.936Z"</span>
       <span class="token punctuation">}</span>
   <span class="token punctuation">]</span>
   <span class="token string">"totalElements"</span><span class="token punctuation">:</span> <span class="token number">48</span><span class="token punctuation">,</span>
   <span class="token string">"totalPages"</span><span class="token punctuation">:</span> <span class="token number">5</span><span class="token punctuation">,</span>
   <span class="token string">"size"</span><span class="token punctuation">:</span> <span class="token number">10</span><span class="token punctuation">,</span>
<span class="token punctuation">}</span>
</code></pre>
<h2 id="get----line-manager-dashboard-1">GET -  Line Manager Dashboard</h2>
<pre><code>/api/admin/dashboard/site
</code></pre>
<p><strong>Parameters</strong></p>

<table>
<thead>
<tr>
<th>Name</th>
<th>Type</th>
<th>Mandatory</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td>lineManager</td>
<td>string</td>
<td>no</td>
<td></td>
</tr>
<tr>
<td>month</td>
<td>string</td>
<td>no</td>
<td></td>
</tr>
<tr>
<td>years</td>
<td>number</td>
<td>no</td>
<td></td>
</tr>
<tr>
<td>sort</td>
<td>string</td>
<td>no</td>
<td></td>
</tr>
<tr>
<td>sortDir</td>
<td>string</td>
<td>no</td>
<td>ASC, DESC</td>
</tr>
<tr>
<td>page</td>
<td>number</td>
<td>no</td>
<td></td>
</tr>
<tr>
<td>pageSize</td>
<td>number</td>
<td>no</td>
<td></td>
</tr>
</tbody>
</table><p><strong>Response  - 200</strong></p>
<pre class=" language-json"><code class="prism  language-json"><span class="token punctuation">{</span>
   <span class="token string">"content"</span><span class="token punctuation">:</span> <span class="token punctuation">[</span>
   	<span class="token punctuation">{</span>
   		<span class="token string">"uuid"</span><span class="token punctuation">:</span> <span class="token string">"6034be7b-a132-4ad9-b571-e3a4f16c572b"</span><span class="token punctuation">,</span>
   		<span class="token string">"site"</span><span class="token punctuation">:</span> <span class="token string">"SCB"</span><span class="token punctuation">,</span>
   		<span class="token string">"lineManagerUuid"</span><span class="token punctuation">:</span> <span class="token string">"6034be7b-a132-4ad9-b571-e3a4f16c572b"</span><span class="token punctuation">,</span>
   		<span class="token string">"lineManagerName"</span><span class="token punctuation">:</span> <span class="token string">"Som"</span><span class="token punctuation">,</span>
   		<span class="token string">"notCompleted"</span><span class="token punctuation">:</span> <span class="token number">10</span><span class="token punctuation">,</span>
   		<span class="token string">"complete"</span><span class="token punctuation">:</span> <span class="token number">90</span><span class="token punctuation">,</span>
   		<span class="token string">"employee"</span><span class="token punctuation">:</span> <span class="token number">100</span><span class="token punctuation">,</span>
   		<span class="token string">"status"</span><span class="token punctuation">:</span> <span class="token string">"ACTIVE"</span><span class="token punctuation">,</span>
   		<span class="token string">"lastActiveDateTime"</span><span class="token punctuation">:</span> <span class="token string">"2023-10-02T13:39:36.936Z"</span><span class="token punctuation">,</span>
   		<span class="token string">"createdDateTime"</span><span class="token punctuation">:</span> <span class="token string">"2023-10-02T13:39:36.936Z"</span>
       <span class="token punctuation">}</span><span class="token punctuation">,</span>
       <span class="token punctuation">{</span>
   		<span class="token string">"uuid"</span><span class="token punctuation">:</span> <span class="token string">"6034be7b-a132-4ad9-b571-e3a4f16c572b"</span><span class="token punctuation">,</span>
   		<span class="token string">"site"</span><span class="token punctuation">:</span> <span class="token string">"KTB"</span><span class="token punctuation">,</span>
   		<span class="token string">"lineManagerUuid"</span><span class="token punctuation">:</span> <span class="token string">"6034be7b-a132-4ad9-b571-e3a4f16c572b"</span><span class="token punctuation">,</span>
   		<span class="token string">"lineManagerName"</span><span class="token punctuation">:</span> <span class="token string">"Som"</span><span class="token punctuation">,</span>
   		<span class="token string">"notCompleted"</span><span class="token punctuation">:</span> <span class="token number">10</span><span class="token punctuation">,</span>
   		<span class="token string">"complete"</span><span class="token punctuation">:</span> <span class="token number">90</span><span class="token punctuation">,</span>
   		<span class="token string">"employee"</span><span class="token punctuation">:</span> <span class="token number">100</span><span class="token punctuation">,</span>
   		<span class="token string">"status"</span><span class="token punctuation">:</span> <span class="token string">"ACTIVE"</span><span class="token punctuation">,</span>
   		<span class="token string">"lastActiveDateTime"</span><span class="token punctuation">:</span> <span class="token string">"2023-10-02T13:39:36.936Z"</span><span class="token punctuation">,</span>
   		<span class="token string">"createdDateTime"</span><span class="token punctuation">:</span> <span class="token string">"2023-10-02T13:39:36.936Z"</span>
       <span class="token punctuation">}</span>
   <span class="token punctuation">]</span>
   <span class="token string">"totalElements"</span><span class="token punctuation">:</span> <span class="token number">48</span><span class="token punctuation">,</span>
   <span class="token string">"totalPages"</span><span class="token punctuation">:</span> <span class="token number">5</span><span class="token punctuation">,</span>
   <span class="token string">"size"</span><span class="token punctuation">:</span> <span class="token number">10</span><span class="token punctuation">,</span>
<span class="token punctuation">}</span>
</code></pre>

