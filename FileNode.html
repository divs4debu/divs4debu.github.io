<!-- HTML generated using hilite.me --><div style="background: #272822; overflow:auto;width:auto;border:solid gray;border-width:.1em .1em .1em .8em;padding:.2em .6em;"><table><tr><td><pre style="margin: 0; line-height: 125%"><span style="color: #75715e">  1
  2
  3
  4
  5
  6
  7
  8
  9
 10
 11
 12
 13
 14
 15
 16
 17
 18
 19
 20
 21
 22
 23
 24
 25
 26
 27
 28
 29
 30
 31
 32
 33
 34
 35
 36
 37
 38
 39
 40
 41
 42
 43
 44
 45
 46
 47
 48
 49
 50
 51
 52
 53
 54
 55
 56
 57
 58
 59
 60
 61
 62
 63
 64
 65
 66
 67
 68
 69
 70
 71
 72
 73
 74
 75
 76
 77
 78
 79
 80
 81
 82
 83
 84
 85
 86
 87
 88
 89
 90
 91
 92
 93
 94
 95
 96
 97
 98
 99
100
101
102
103
104
105
106
107
108
109
110
111
112
113
114
115
116
117
118
119
120
121
122
123
124
125
126
127
128
129
130
131
132
133
134
135
136
137
138
139
140
141
142
143
144
145
146
147
148
149
150
151
152
153
154
155
156
157
158
159
160
161
162
163
164
165
166
167
168
169
170
171
172
173
174
175
176
177
178
179
180
181
182
183
184
185
186
187
188
189
190
191
192
193
194
195
196
197</span></pre></td><td><pre style="margin: 0; line-height: 125%"><span style="color: #75715e">#include &lt;iostream&gt;</span>
<span style="color: #75715e">#include &lt;cstdlib&gt;</span>
<span style="color: #75715e">#include &lt;fstream&gt;</span>
<span style="color: #66d9ef">using</span> <span style="color: #66d9ef">namespace</span> <span style="color: #f8f8f2">std;</span>
<span style="color: #66d9ef">typedef</span> <span style="color: #66d9ef">struct</span> <span style="color: #f8f8f2">node</span> <span style="color: #f8f8f2">node;</span>
<span style="color: #66d9ef">struct</span> <span style="color: #f8f8f2">node</span> <span style="color: #f8f8f2">{</span>
    <span style="color: #66d9ef">char</span>  <span style="color: #f8f8f2">name;</span>
    <span style="color: #f8f8f2">node</span> <span style="color: #f92672">*</span><span style="color: #f8f8f2">up;</span>
    <span style="color: #f8f8f2">node</span> <span style="color: #f92672">*</span><span style="color: #f8f8f2">down;</span>
    <span style="color: #f8f8f2">node</span> <span style="color: #f92672">*</span><span style="color: #f8f8f2">left;</span>
    <span style="color: #f8f8f2">node</span> <span style="color: #f92672">*</span><span style="color: #f8f8f2">right;</span>
<span style="color: #f8f8f2">}</span><span style="color: #f92672">*</span><span style="color: #f8f8f2">head,</span><span style="color: #f92672">*</span><span style="color: #f8f8f2">cur,</span><span style="color: #f92672">*</span><span style="color: #f8f8f2">next,</span><span style="color: #f92672">*</span><span style="color: #f8f8f2">ne;</span>
<span style="color: #66d9ef">int</span> <span style="color: #f8f8f2">col,row;</span>
<span style="color: #f8f8f2">string</span> <span style="color: #f8f8f2">line;</span>
<span style="color: #66d9ef">void</span> <span style="color: #a6e22e">setColumn</span><span style="color: #f8f8f2">(</span><span style="color: #66d9ef">int</span> <span style="color: #f8f8f2">i)</span> <span style="color: #f8f8f2">{</span>
    <span style="color: #f8f8f2">col</span><span style="color: #f92672">=</span><span style="color: #f8f8f2">i;</span>
<span style="color: #f8f8f2">}</span>
<span style="color: #66d9ef">int</span> <span style="color: #a6e22e">getColumn</span><span style="color: #f8f8f2">()</span> <span style="color: #f8f8f2">{</span>
    <span style="color: #66d9ef">return</span> <span style="color: #f8f8f2">col;</span>
<span style="color: #f8f8f2">}</span>
<span style="color: #66d9ef">void</span> <span style="color: #a6e22e">setRow</span><span style="color: #f8f8f2">(</span><span style="color: #66d9ef">int</span> <span style="color: #f8f8f2">r)</span> <span style="color: #f8f8f2">{</span>
    <span style="color: #f8f8f2">row</span><span style="color: #f92672">=</span><span style="color: #f8f8f2">r;</span>
<span style="color: #f8f8f2">}</span>

<span style="color: #66d9ef">int</span> <span style="color: #a6e22e">getRow</span><span style="color: #f8f8f2">()</span> <span style="color: #f8f8f2">{</span>
    <span style="color: #66d9ef">return</span> <span style="color: #f8f8f2">row;</span>
<span style="color: #f8f8f2">}</span>
<span style="color: #75715e">/*	string str;</span>
<span style="color: #75715e">	while(line[i]!=&#39; &#39;){</span>
<span style="color: #75715e">		str = str+line[i];</span>
<span style="color: #75715e">	}</span>
<span style="color: #75715e">}*/</span>
<span style="color: #66d9ef">bool</span> <span style="color: #a6e22e">checkAlNum</span><span style="color: #f8f8f2">(</span><span style="color: #66d9ef">char</span> <span style="color: #f8f8f2">x)</span> <span style="color: #f8f8f2">{</span>
    <span style="color: #66d9ef">if</span><span style="color: #f8f8f2">((x</span><span style="color: #f92672">&gt;=</span><span style="color: #e6db74">&#39;A&#39;</span><span style="color: #f92672">&amp;&amp;</span><span style="color: #f8f8f2">x</span><span style="color: #f92672">&lt;=</span><span style="color: #e6db74">&#39;Z&#39;</span><span style="color: #f8f8f2">)</span><span style="color: #f92672">||</span><span style="color: #f8f8f2">(x</span><span style="color: #f92672">&gt;=</span><span style="color: #e6db74">&#39;a&#39;</span><span style="color: #f92672">&amp;&amp;</span><span style="color: #f8f8f2">x</span><span style="color: #f92672">&lt;=</span><span style="color: #e6db74">&#39;z&#39;</span><span style="color: #f8f8f2">)</span><span style="color: #f92672">||</span><span style="color: #f8f8f2">(x</span><span style="color: #f92672">&gt;=</span><span style="color: #e6db74">&#39;0&#39;</span><span style="color: #f92672">&amp;&amp;</span><span style="color: #f8f8f2">x</span><span style="color: #f92672">&lt;=</span><span style="color: #e6db74">&#39;9&#39;</span><span style="color: #f8f8f2">))</span>
        <span style="color: #66d9ef">return</span> <span style="color: #f8f8f2">true;</span>
    <span style="color: #66d9ef">else</span>
        <span style="color: #66d9ef">return</span> <span style="color: #f8f8f2">false;</span>
<span style="color: #f8f8f2">}</span>

<span style="color: #f8f8f2">node</span><span style="color: #f92672">*</span> <span style="color: #a6e22e">search</span><span style="color: #f8f8f2">(</span><span style="color: #66d9ef">char</span> <span style="color: #f8f8f2">x)</span> <span style="color: #f8f8f2">{</span>
    <span style="color: #f8f8f2">cur</span><span style="color: #f92672">=</span><span style="color: #f8f8f2">head;</span>
    <span style="color: #66d9ef">int</span> <span style="color: #f8f8f2">flag</span><span style="color: #f92672">=</span><span style="color: #f8f8f2">true;</span>
    <span style="color: #66d9ef">while</span><span style="color: #f8f8f2">(flag)</span> <span style="color: #f8f8f2">{</span>
        <span style="color: #66d9ef">for</span> <span style="color: #f8f8f2">(</span><span style="color: #66d9ef">int</span> <span style="color: #f8f8f2">i</span> <span style="color: #f92672">=</span> <span style="color: #ae81ff">0</span><span style="color: #f8f8f2">;</span> <span style="color: #f8f8f2">i</span> <span style="color: #f92672">&lt;</span> <span style="color: #f8f8f2">getRow()</span> <span style="color: #f8f8f2">;</span> <span style="color: #f8f8f2">i</span><span style="color: #f92672">++</span><span style="color: #f8f8f2">)</span> <span style="color: #f8f8f2">{</span>
            <span style="color: #66d9ef">for</span><span style="color: #f8f8f2">(</span><span style="color: #66d9ef">int</span> <span style="color: #f8f8f2">j</span><span style="color: #f92672">=</span><span style="color: #ae81ff">0</span><span style="color: #f8f8f2">;</span> <span style="color: #f8f8f2">j</span><span style="color: #f92672">&lt;</span><span style="color: #f8f8f2">getColumn()</span><span style="color: #f92672">-</span><span style="color: #ae81ff">1</span><span style="color: #f8f8f2">;</span> <span style="color: #f8f8f2">j</span><span style="color: #f92672">++</span><span style="color: #f8f8f2">)</span> <span style="color: #f8f8f2">{</span>
                <span style="color: #66d9ef">if</span><span style="color: #f8f8f2">(i</span><span style="color: #f92672">%</span><span style="color: #ae81ff">2</span><span style="color: #f92672">==</span><span style="color: #ae81ff">0</span><span style="color: #f8f8f2">)</span> <span style="color: #f8f8f2">{</span>
                    <span style="color: #66d9ef">if</span><span style="color: #f8f8f2">(cur</span><span style="color: #f92672">-&gt;</span><span style="color: #f8f8f2">name</span><span style="color: #f92672">==</span><span style="color: #f8f8f2">x)</span>
                        <span style="color: #66d9ef">return</span> <span style="color: #f8f8f2">cur;</span>
                    <span style="color: #66d9ef">else</span>
                        <span style="color: #f8f8f2">cur</span><span style="color: #f92672">=</span><span style="color: #f8f8f2">cur</span><span style="color: #f92672">-&gt;</span><span style="color: #f8f8f2">right;</span>
                <span style="color: #f8f8f2">}</span> <span style="color: #66d9ef">else</span> <span style="color: #f8f8f2">{</span>
                    <span style="color: #66d9ef">if</span><span style="color: #f8f8f2">(cur</span><span style="color: #f92672">-&gt;</span><span style="color: #f8f8f2">name</span><span style="color: #f92672">==</span><span style="color: #f8f8f2">x)</span>
                        <span style="color: #66d9ef">return</span> <span style="color: #f8f8f2">cur;</span>
                    <span style="color: #66d9ef">else</span>
                        <span style="color: #f8f8f2">cur</span><span style="color: #f92672">=</span><span style="color: #f8f8f2">cur</span><span style="color: #f92672">-&gt;</span><span style="color: #f8f8f2">left;</span>
                <span style="color: #f8f8f2">}</span>
            <span style="color: #f8f8f2">}</span>
            <span style="color: #66d9ef">if</span><span style="color: #f8f8f2">(cur</span><span style="color: #f92672">-&gt;</span><span style="color: #f8f8f2">name</span><span style="color: #f92672">==</span><span style="color: #f8f8f2">x)</span>
                <span style="color: #66d9ef">return</span> <span style="color: #f8f8f2">cur;</span>
            <span style="color: #f8f8f2">cur</span><span style="color: #f92672">=</span><span style="color: #f8f8f2">cur</span><span style="color: #f92672">-&gt;</span><span style="color: #f8f8f2">down;</span>

        <span style="color: #f8f8f2">}</span>
        <span style="color: #f8f8f2">flag</span><span style="color: #f92672">=</span><span style="color: #f8f8f2">false;</span>
    <span style="color: #f8f8f2">}</span>
    <span style="color: #66d9ef">if</span><span style="color: #f8f8f2">(flag</span><span style="color: #f92672">==</span><span style="color: #f8f8f2">false)</span>
        <span style="color: #75715e">//cout&lt;&lt;&quot;node not found&quot;&lt;&lt;endl;</span>
    <span style="color: #66d9ef">return</span> <span style="color: #f8f8f2">NULL;</span>
<span style="color: #f8f8f2">}</span>

<span style="color: #66d9ef">int</span> <span style="color: #a6e22e">main</span><span style="color: #f8f8f2">()</span> <span style="color: #f8f8f2">{</span>
    <span style="color: #f8f8f2">ifstream</span> <span style="color: #f8f8f2">infile;</span>
    <span style="color: #f8f8f2">infile.open(</span><span style="color: #e6db74">&quot;mest.txt&quot;</span><span style="color: #f8f8f2">);</span>
    <span style="color: #66d9ef">if</span><span style="color: #f8f8f2">(infile</span><span style="color: #f92672">==</span><span style="color: #f8f8f2">NULL){</span>
    	<span style="color: #f8f8f2">cout</span><span style="color: #f92672">&lt;&lt;</span><span style="color: #e6db74">&quot;FILE NOT FOUND&quot;</span><span style="color: #f92672">&lt;&lt;</span><span style="color: #f8f8f2">endl;</span>
    	<span style="color: #66d9ef">return</span> <span style="color: #ae81ff">0</span><span style="color: #f8f8f2">;</span>
    <span style="color: #f8f8f2">}</span>
    <span style="color: #f8f8f2">string</span> <span style="color: #f8f8f2">strMov;</span>
    <span style="color: #f8f8f2">head</span><span style="color: #f92672">=</span><span style="color: #f8f8f2">(node</span><span style="color: #f92672">*</span><span style="color: #f8f8f2">)malloc</span> <span style="color: #f8f8f2">(</span><span style="color: #66d9ef">sizeof</span><span style="color: #f8f8f2">(node));</span>
    <span style="color: #f8f8f2">cur</span><span style="color: #f92672">=</span><span style="color: #f8f8f2">head;</span>
    <span style="color: #66d9ef">bool</span> <span style="color: #f8f8f2">matrix</span><span style="color: #f92672">=</span><span style="color: #f8f8f2">true,s_node</span><span style="color: #f92672">=</span><span style="color: #f8f8f2">true;</span>
    <span style="color: #66d9ef">int</span> <span style="color: #f8f8f2">i,r</span><span style="color: #f92672">=</span><span style="color: #ae81ff">0</span><span style="color: #f8f8f2">,j,k;</span>
    
    <span style="color: #66d9ef">while</span><span style="color: #f8f8f2">(getline(infile,line))</span> <span style="color: #f8f8f2">{</span>
        <span style="color: #66d9ef">int</span> <span style="color: #f8f8f2">c</span><span style="color: #f92672">=</span><span style="color: #ae81ff">0</span><span style="color: #f8f8f2">;</span>
        <span style="color: #66d9ef">if</span><span style="color: #f8f8f2">(line.find(</span><span style="color: #e6db74">&quot;input&quot;</span><span style="color: #f8f8f2">)</span><span style="color: #f92672">!=-</span><span style="color: #ae81ff">1</span><span style="color: #f8f8f2">)</span> <span style="color: #f8f8f2">{</span>
            <span style="color: #f8f8f2">matrix</span><span style="color: #f92672">=</span><span style="color: #f8f8f2">false;</span>
        <span style="color: #f8f8f2">}</span>

        <span style="color: #66d9ef">if</span><span style="color: #f8f8f2">(</span><span style="color: #f92672">!</span><span style="color: #f8f8f2">line.empty()</span><span style="color: #f92672">&amp;&amp;</span><span style="color: #f8f8f2">matrix)</span> <span style="color: #f8f8f2">{</span>

            <span style="color: #66d9ef">for</span><span style="color: #f8f8f2">(i</span><span style="color: #f92672">=</span><span style="color: #ae81ff">0</span><span style="color: #f8f8f2">;</span> <span style="color: #f8f8f2">i</span><span style="color: #f92672">&lt;</span><span style="color: #f8f8f2">line.length();</span> <span style="color: #f8f8f2">i</span><span style="color: #f92672">+=</span><span style="color: #ae81ff">2</span><span style="color: #f8f8f2">)</span> <span style="color: #f8f8f2">{</span>

                <span style="color: #f8f8f2">c</span><span style="color: #f92672">++</span><span style="color: #f8f8f2">;</span>
                <span style="color: #f8f8f2">ne</span><span style="color: #f92672">=</span><span style="color: #f8f8f2">(node</span><span style="color: #f92672">*</span><span style="color: #f8f8f2">)malloc</span> <span style="color: #f8f8f2">(</span><span style="color: #66d9ef">sizeof</span><span style="color: #f8f8f2">(node));</span>

                <span style="color: #f8f8f2">cur</span><span style="color: #f92672">-&gt;</span><span style="color: #f8f8f2">right</span><span style="color: #f92672">=</span><span style="color: #f8f8f2">ne;</span>
                <span style="color: #f8f8f2">ne</span><span style="color: #f92672">-&gt;</span><span style="color: #f8f8f2">left</span><span style="color: #f92672">=</span><span style="color: #f8f8f2">cur;</span>
                <span style="color: #66d9ef">if</span><span style="color: #f8f8f2">(checkAlNum(line[i]))</span>
                    <span style="color: #f8f8f2">cur</span><span style="color: #f92672">-&gt;</span><span style="color: #f8f8f2">name</span><span style="color: #f92672">=</span><span style="color: #f8f8f2">line[i];</span>

                <span style="color: #f8f8f2">cur</span><span style="color: #f92672">=</span><span style="color: #f8f8f2">cur</span><span style="color: #f92672">-&gt;</span><span style="color: #f8f8f2">right;</span>
            <span style="color: #f8f8f2">}</span>
            <span style="color: #f8f8f2">setColumn(c);</span>
            <span style="color: #66d9ef">while</span><span style="color: #f8f8f2">(c</span><span style="color: #f92672">--</span><span style="color: #f8f8f2">)</span>
                <span style="color: #f8f8f2">cur</span><span style="color: #f92672">=</span><span style="color: #f8f8f2">cur</span><span style="color: #f92672">-&gt;</span><span style="color: #f8f8f2">left;</span>

            <span style="color: #f8f8f2">ne</span><span style="color: #f92672">=</span><span style="color: #f8f8f2">(node</span><span style="color: #f92672">*</span><span style="color: #f8f8f2">)malloc</span> <span style="color: #f8f8f2">(</span><span style="color: #66d9ef">sizeof</span><span style="color: #f8f8f2">(node));</span>
            <span style="color: #f8f8f2">ne</span><span style="color: #f92672">-&gt;</span><span style="color: #f8f8f2">up</span><span style="color: #f92672">=</span><span style="color: #f8f8f2">cur;</span>
            <span style="color: #f8f8f2">cur</span><span style="color: #f92672">-&gt;</span><span style="color: #f8f8f2">down</span><span style="color: #f92672">=</span><span style="color: #f8f8f2">ne;</span>
            <span style="color: #f8f8f2">cur</span><span style="color: #f92672">=</span><span style="color: #f8f8f2">cur</span><span style="color: #f92672">-&gt;</span><span style="color: #f8f8f2">down;</span>
            <span style="color: #f8f8f2">r</span><span style="color: #f92672">++</span><span style="color: #f8f8f2">;</span>
        <span style="color: #f8f8f2">}</span> <span style="color: #66d9ef">else</span> <span style="color: #66d9ef">if</span><span style="color: #f8f8f2">(</span><span style="color: #f92672">!</span><span style="color: #f8f8f2">matrix)</span> <span style="color: #f8f8f2">{</span>
            <span style="color: #66d9ef">if</span><span style="color: #f8f8f2">(line.find(</span><span style="color: #e6db74">&quot;input&quot;</span><span style="color: #f8f8f2">)</span><span style="color: #f92672">==-</span><span style="color: #ae81ff">1</span><span style="color: #f8f8f2">)</span> <span style="color: #f8f8f2">{</span>
                
                <span style="color: #f8f8f2">strMov</span><span style="color: #f92672">=</span><span style="color: #f8f8f2">strMov</span><span style="color: #f92672">+</span><span style="color: #f8f8f2">line</span><span style="color: #f92672">+</span><span style="color: #e6db74">&quot;</span><span style="color: #ae81ff">\n</span><span style="color: #e6db74">&quot;</span><span style="color: #f8f8f2">;</span>
            <span style="color: #f8f8f2">}</span>

        <span style="color: #f8f8f2">}</span>

    <span style="color: #f8f8f2">}</span>
    <span style="color: #f8f8f2">setRow(r);</span>
    <span style="color: #f8f8f2">cur</span><span style="color: #f92672">=</span><span style="color: #f8f8f2">head;</span>
    <span style="color: #66d9ef">for</span><span style="color: #f8f8f2">(i</span><span style="color: #f92672">=</span><span style="color: #ae81ff">0</span><span style="color: #f8f8f2">;</span> <span style="color: #f8f8f2">i</span><span style="color: #f92672">&lt;</span><span style="color: #f8f8f2">getRow()</span><span style="color: #f92672">-</span><span style="color: #ae81ff">1</span><span style="color: #f8f8f2">;</span> <span style="color: #f8f8f2">i</span><span style="color: #f92672">++</span><span style="color: #f8f8f2">)</span> <span style="color: #f8f8f2">{</span>
        <span style="color: #f8f8f2">next</span><span style="color: #f92672">=</span><span style="color: #f8f8f2">cur</span><span style="color: #f92672">-&gt;</span><span style="color: #f8f8f2">down;</span>
        <span style="color: #66d9ef">for</span><span style="color: #f8f8f2">(j</span><span style="color: #f92672">=</span><span style="color: #ae81ff">0</span><span style="color: #f8f8f2">;</span> <span style="color: #f8f8f2">j</span><span style="color: #f92672">&lt;</span><span style="color: #f8f8f2">getColumn()</span><span style="color: #f92672">-</span><span style="color: #ae81ff">1</span><span style="color: #f8f8f2">;</span> <span style="color: #f8f8f2">j</span><span style="color: #f92672">++</span><span style="color: #f8f8f2">)</span> <span style="color: #f8f8f2">{</span>
            <span style="color: #f8f8f2">cur</span><span style="color: #f92672">=</span><span style="color: #f8f8f2">cur</span><span style="color: #f92672">-&gt;</span><span style="color: #f8f8f2">right;</span>
            <span style="color: #f8f8f2">next</span><span style="color: #f92672">=</span><span style="color: #f8f8f2">next</span><span style="color: #f92672">-&gt;</span><span style="color: #f8f8f2">right;</span>
            <span style="color: #f8f8f2">cur</span><span style="color: #f92672">-&gt;</span><span style="color: #f8f8f2">down</span><span style="color: #f92672">=</span><span style="color: #f8f8f2">next;</span>
            <span style="color: #f8f8f2">next</span><span style="color: #f92672">-&gt;</span><span style="color: #f8f8f2">up</span><span style="color: #f92672">=</span><span style="color: #f8f8f2">cur;</span>
        <span style="color: #f8f8f2">}</span>
        <span style="color: #66d9ef">for</span><span style="color: #f8f8f2">(k</span><span style="color: #f92672">=</span><span style="color: #ae81ff">0</span><span style="color: #f8f8f2">;</span> <span style="color: #f8f8f2">k</span><span style="color: #f92672">&lt;</span><span style="color: #f8f8f2">j;</span> <span style="color: #f8f8f2">k</span><span style="color: #f92672">++</span><span style="color: #f8f8f2">)</span> <span style="color: #f8f8f2">{</span>
            <span style="color: #f8f8f2">cur</span><span style="color: #f92672">=</span><span style="color: #f8f8f2">cur</span><span style="color: #f92672">-&gt;</span><span style="color: #f8f8f2">left;</span>
        <span style="color: #f8f8f2">}</span>
        <span style="color: #f8f8f2">cur</span><span style="color: #f92672">=</span><span style="color: #f8f8f2">cur</span><span style="color: #f92672">-&gt;</span><span style="color: #f8f8f2">down;</span>
    <span style="color: #f8f8f2">}</span>

    <span style="color: #f8f8f2">ofstream</span> <span style="color: #f8f8f2">out_file;</span>
    <span style="color: #f8f8f2">out_file.open(</span><span style="color: #e6db74">&quot;output.txt&quot;</span><span style="color: #f8f8f2">);</span>
    <span style="color: #f8f8f2">string</span> <span style="color: #f8f8f2">out;</span>


    <span style="color: #66d9ef">for</span><span style="color: #f8f8f2">(i</span><span style="color: #f92672">=</span><span style="color: #ae81ff">0</span><span style="color: #f8f8f2">;</span> <span style="color: #f8f8f2">i</span><span style="color: #f92672">&lt;</span><span style="color: #f8f8f2">strMov.length();</span> <span style="color: #f8f8f2">i</span><span style="color: #f92672">++</span><span style="color: #f8f8f2">)</span> <span style="color: #f8f8f2">{</span>
        <span style="color: #66d9ef">for</span><span style="color: #f8f8f2">(j</span><span style="color: #f92672">=</span><span style="color: #f8f8f2">i;</span> <span style="color: #f8f8f2">strMov[j]</span><span style="color: #f92672">!=</span><span style="color: #e6db74">&#39;\n&#39;</span><span style="color: #f8f8f2">;</span> <span style="color: #f8f8f2">j</span><span style="color: #f92672">++</span><span style="color: #f8f8f2">)</span> <span style="color: #f8f8f2">{</span>

            <span style="color: #66d9ef">if</span><span style="color: #f8f8f2">(s_node)</span> <span style="color: #f8f8f2">{</span>
                <span style="color: #f8f8f2">cur</span><span style="color: #f92672">=</span><span style="color: #f8f8f2">search(strMov[j]);</span>
                <span style="color: #66d9ef">if</span><span style="color: #f8f8f2">(cur</span><span style="color: #f92672">==</span><span style="color: #f8f8f2">NULL)</span> <span style="color: #f8f8f2">{</span>
                    <span style="color: #f8f8f2">out</span><span style="color: #f92672">=</span><span style="color: #f8f8f2">out</span><span style="color: #f92672">+</span><span style="color: #e6db74">&quot;node not found&quot;</span><span style="color: #f8f8f2">;</span>
                    <span style="color: #66d9ef">for</span><span style="color: #f8f8f2">(j;</span> <span style="color: #f8f8f2">strMov[j]</span><span style="color: #f92672">!=</span><span style="color: #e6db74">&#39;\n&#39;</span><span style="color: #f8f8f2">;</span> <span style="color: #f8f8f2">j</span><span style="color: #f92672">++</span><span style="color: #f8f8f2">);</span>
                    <span style="color: #66d9ef">break</span><span style="color: #f8f8f2">;</span>
                <span style="color: #f8f8f2">}</span>
                <span style="color: #f8f8f2">s_node</span><span style="color: #f92672">=</span><span style="color: #f8f8f2">false;</span>

            <span style="color: #f8f8f2">}</span> <span style="color: #66d9ef">else</span> <span style="color: #f8f8f2">{</span>

                <span style="color: #66d9ef">if</span><span style="color: #f8f8f2">(strMov[j]</span><span style="color: #f92672">!=</span><span style="color: #e6db74">&#39; &#39;</span><span style="color: #f8f8f2">)</span> <span style="color: #f8f8f2">{</span>


                    <span style="color: #f8f8f2">out</span><span style="color: #f92672">=</span><span style="color: #f8f8f2">out</span><span style="color: #f92672">+</span><span style="color: #e6db74">&quot;</span><span style="color: #ae81ff">\&#39;</span><span style="color: #e6db74">&quot;</span><span style="color: #f92672">+</span><span style="color: #f8f8f2">strMov[j]</span><span style="color: #f92672">+</span><span style="color: #e6db74">&quot;</span><span style="color: #ae81ff">\&#39;</span><span style="color: #e6db74">&quot;&quot;-&gt;&quot;</span><span style="color: #f8f8f2">;</span>

                    <span style="color: #66d9ef">if</span><span style="color: #f8f8f2">(strMov[j]</span><span style="color: #f92672">==</span><span style="color: #e6db74">&#39;u&#39;</span><span style="color: #f92672">||</span><span style="color: #f8f8f2">strMov[j]</span><span style="color: #f92672">==</span><span style="color: #e6db74">&#39;U&#39;</span><span style="color: #f8f8f2">)</span> <span style="color: #f8f8f2">{</span>
                        <span style="color: #f8f8f2">cur</span><span style="color: #f92672">=</span><span style="color: #f8f8f2">cur</span><span style="color: #f92672">-&gt;</span><span style="color: #f8f8f2">up;</span>
                    <span style="color: #f8f8f2">}</span> <span style="color: #66d9ef">else</span> <span style="color: #66d9ef">if</span><span style="color: #f8f8f2">(strMov[j]</span><span style="color: #f92672">==</span><span style="color: #e6db74">&#39;d&#39;</span><span style="color: #f92672">||</span><span style="color: #f8f8f2">strMov[j]</span><span style="color: #f92672">==</span><span style="color: #e6db74">&#39;D&#39;</span><span style="color: #f8f8f2">)</span> <span style="color: #f8f8f2">{</span>
                        <span style="color: #f8f8f2">cur</span><span style="color: #f92672">=</span><span style="color: #f8f8f2">cur</span><span style="color: #f92672">-&gt;</span><span style="color: #f8f8f2">down;</span>
                    <span style="color: #f8f8f2">}</span> <span style="color: #66d9ef">else</span> <span style="color: #66d9ef">if</span><span style="color: #f8f8f2">(strMov[j]</span><span style="color: #f92672">==</span><span style="color: #e6db74">&#39;r&#39;</span><span style="color: #f92672">||</span><span style="color: #f8f8f2">strMov[j]</span><span style="color: #f92672">==</span><span style="color: #e6db74">&#39;R&#39;</span><span style="color: #f8f8f2">)</span> <span style="color: #f8f8f2">{</span>
                        <span style="color: #f8f8f2">cur</span><span style="color: #f92672">=</span><span style="color: #f8f8f2">cur</span><span style="color: #f92672">-&gt;</span><span style="color: #f8f8f2">right;</span>
                    <span style="color: #f8f8f2">}</span> <span style="color: #66d9ef">else</span> <span style="color: #66d9ef">if</span><span style="color: #f8f8f2">(strMov[j]</span><span style="color: #f92672">==</span><span style="color: #e6db74">&#39;l&#39;</span><span style="color: #f92672">||</span><span style="color: #f8f8f2">strMov[j]</span><span style="color: #f92672">==</span><span style="color: #e6db74">&#39;L&#39;</span><span style="color: #f8f8f2">)</span> <span style="color: #f8f8f2">{</span>
                        <span style="color: #f8f8f2">cur</span><span style="color: #f92672">=</span><span style="color: #f8f8f2">cur</span><span style="color: #f92672">-&gt;</span><span style="color: #f8f8f2">left;</span>
                    <span style="color: #f8f8f2">}</span> <span style="color: #66d9ef">else</span> <span style="color: #f8f8f2">{</span>

                        <span style="color: #f8f8f2">out</span><span style="color: #f92672">+=</span><span style="color: #e6db74">&quot;this is invalid move</span><span style="color: #ae81ff">\n</span><span style="color: #e6db74">&quot;</span><span style="color: #f8f8f2">;</span>
                        <span style="color: #66d9ef">for</span><span style="color: #f8f8f2">(j;</span> <span style="color: #f8f8f2">strMov[j]</span><span style="color: #f92672">!=</span><span style="color: #e6db74">&#39;\n&#39;</span><span style="color: #f8f8f2">;</span> <span style="color: #f8f8f2">j</span><span style="color: #f92672">++</span><span style="color: #f8f8f2">);</span>
                        <span style="color: #66d9ef">break</span><span style="color: #f8f8f2">;</span>

                    <span style="color: #f8f8f2">}</span>
                <span style="color: #f8f8f2">}</span>



                <span style="color: #66d9ef">if</span><span style="color: #f8f8f2">(cur</span><span style="color: #f92672">==</span><span style="color: #f8f8f2">NULL</span><span style="color: #f92672">||</span><span style="color: #f8f8f2">cur</span><span style="color: #f92672">-&gt;</span><span style="color: #f8f8f2">name</span><span style="color: #f92672">==</span><span style="color: #f8f8f2">NULL)</span> <span style="color: #f8f8f2">{</span>
                    <span style="color: #f8f8f2">out</span><span style="color: #f92672">+=</span><span style="color: #e6db74">&quot;NULL&quot;</span><span style="color: #f8f8f2">;</span>
                    <span style="color: #66d9ef">for</span><span style="color: #f8f8f2">(j;</span> <span style="color: #f8f8f2">strMov[j]</span><span style="color: #f92672">!=</span><span style="color: #e6db74">&#39;\n&#39;</span><span style="color: #f8f8f2">;</span> <span style="color: #f8f8f2">j</span><span style="color: #f92672">++</span><span style="color: #f8f8f2">);</span>
                    <span style="color: #66d9ef">break</span><span style="color: #f8f8f2">;</span>
                <span style="color: #f8f8f2">}</span> <span style="color: #66d9ef">else</span>
                    <span style="color: #f8f8f2">out</span><span style="color: #f92672">=</span><span style="color: #f8f8f2">out</span><span style="color: #f92672">+</span><span style="color: #f8f8f2">cur</span><span style="color: #f92672">-&gt;</span><span style="color: #f8f8f2">name</span><span style="color: #f92672">+</span><span style="color: #e6db74">&quot;-&gt;&quot;</span><span style="color: #f8f8f2">;</span>
            <span style="color: #f8f8f2">}</span>

        <span style="color: #f8f8f2">}</span>
        <span style="color: #f8f8f2">i</span><span style="color: #f92672">=</span><span style="color: #f8f8f2">j;</span>
        <span style="color: #f8f8f2">s_node</span><span style="color: #f92672">=</span><span style="color: #f8f8f2">true;</span>
        <span style="color: #f8f8f2">out</span><span style="color: #f92672">+=</span><span style="color: #e6db74">&quot;</span><span style="color: #ae81ff">\n</span><span style="color: #e6db74">&quot;</span><span style="color: #f8f8f2">;</span>
    <span style="color: #f8f8f2">}</span>
   <span style="color: #75715e">// cout&lt;&lt;out;</span>
    <span style="color: #f8f8f2">out_file</span><span style="color: #f92672">&lt;&lt;</span><span style="color: #f8f8f2">out;</span>
    <span style="color: #f8f8f2">out_file.close();</span>
    <span style="color: #f8f8f2">infile.close();</span>
<span style="color: #f8f8f2">}</span>
</pre></td></tr></table></div>
