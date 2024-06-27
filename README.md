<html>
  <head>
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3"
      crossorigin="anonymous"
    
  </head>
  <body aria-hidden="false" style="padding: 0px">
    <div>
      <div class="">
        <div class="Toastify"></div>
        <div class="dark:bg-gray-900">
          <div class="py-0 md:mx-2" id="imgpreview">
            <div class="lg:min-h-screen bg-gray-50 dark:bg-gray-900">
              <div class="dark:bg-gray-900 min-h-screen md:px-4">
                <div
                  class="bg-gray-50 dark:bg-gray-900 min-h-screen p-4 lg:p-12"
                >
                  <div
                    class="max-w-screen-lg mx-auto bg-white dark:bg-gray-800 rounded-lg shadow-md p-6 lg:p-10"
                  >
                    <div
                      class="cont leading-relaxed text-dark dark:text-gray-100"
                    >
                      <h2>PHP Basics</h2>
                      <h3>Hello World</h3>
                      <p>echo function is used to display or print output</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token php language-php"><span class="token delimiter important">&lt;?php</span> <span class="token keyword">echo</span> <span class="token string double-quoted-string">"Hello World!"</span><span class="token punctuation">;</span> <span class="token delimiter important">?&gt;</span></span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h2>Comments</h2>
                      <p>
                        Commets are used to make the code more understandable
                        for programmer, they are not executed by compiler or
                        interpreter.
                      </p>
                      <h3>One Liner</h3>
                      <p>This is a singleline comment</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token comment">// Twinkle Twinkle Little Star</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>Another One Liner</h3>
                      <p>This is a single-line comment</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token comment"># Chocolate dedo mujhe yaar</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>Multiline</h3>
                      <p>This is a multiline comment</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token comment">/* Code With 
Harry */</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h2>Vardump</h2>
                      <p>
                        This function dumps information about one or more
                        variables.
                      </p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token php language-php"><span class="token delimiter important">&lt;?php</span> <span class="token function">var_dump</span><span class="token punctuation">(</span>var1<span class="token punctuation">,</span> var2<span class="token punctuation">,</span> <span class="token operator">...</span><span class="token punctuation">)</span><span class="token punctuation">;</span> <span class="token delimiter important">?&gt;</span></span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h2>Variables</h2>
                      <p>Variables are "containers" for storing information.</p>
                      <h3>Defining Variables</h3>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token php language-php"><span class="token delimiter important">&lt;?php</span>
<span class="token variable">$Title</span> <span class="token operator">=</span> <span class="token string double-quoted-string">"PHP Cheat Sheet By CodeWithHarry"</span><span class="token punctuation">;</span>
<span class="token delimiter important">?&gt;</span></span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h2>Datatypes</h2>
                      <p>Datatype is a type of data</p>
                      <h3>String</h3>
                      <p>
                        A string is a sequence of characters, like "Hello
                        world!".
                      </p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token php language-php"><span class="token delimiter important">&lt;?php</span> 
<span class="token variable">$x</span> <span class="token operator">=</span> <span class="token string double-quoted-string">"Harry"</span><span class="token punctuation">;</span> 
<span class="token keyword">echo</span> <span class="token variable">$x</span><span class="token punctuation">;</span> 
<span class="token delimiter important">?&gt;</span></span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>Integer</h3>
                      <p>An integer is a number without any decimal part.</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token php language-php"><span class="token delimiter important">&lt;?php</span>
<span class="token variable">$x</span> <span class="token operator">=</span> <span class="token number">1234</span><span class="token punctuation">;</span>
<span class="token function">var_dump</span><span class="token punctuation">(</span><span class="token variable">$x</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token delimiter important">?&gt;</span></span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>Float</h3>
                      <p>
                        A float is a number with a decimal point or a number in
                        exponential form.
                      </p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token php language-php"><span class="token delimiter important">&lt;?php</span> 
<span class="token variable">$x</span> <span class="token operator">=</span> <span class="token number">1.2345</span><span class="token punctuation">;</span> 
<span class="token function">var_dump</span><span class="token punctuation">(</span><span class="token variable">$x</span><span class="token punctuation">)</span><span class="token punctuation">;</span> 
<span class="token delimiter important">?&gt;</span></span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>Array</h3>
                      <p>
                        An array stores multiple values in one single variable
                      </p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token php language-php"><span class="token delimiter important">&lt;?php</span>
<span class="token variable">$names</span> <span class="token operator">=</span> <span class="token keyword">array</span><span class="token punctuation">(</span><span class="token string double-quoted-string">"Harry"</span><span class="token punctuation">,</span><span class="token string double-quoted-string">"Rohan"</span><span class="token punctuation">,</span><span class="token string double-quoted-string">"Shubham"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token function">var_dump</span><span class="token punctuation">(</span><span class="token variable">$names</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token delimiter important">?&gt;</span></span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>Class</h3>
                      <p>A class is a template for objects</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token php language-php"><span class="token delimiter important">&lt;?php</span> 
<span class="token keyword">class</span> <span class="token class-name-definition class-name">Harry</span><span class="token punctuation">{</span> 
<span class="token comment">// code goes here... </span>
<span class="token punctuation">}</span> 
<span class="token delimiter important">?&gt;</span></span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>Object</h3>
                      <p>An object is an instance of the class.</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token php language-php"><span class="token delimiter important">&lt;?php</span> 
<span class="token keyword">class</span> <span class="token class-name-definition class-name">Bike</span> <span class="token punctuation">{</span> 
<span class="token keyword">public</span> <span class="token variable">$color</span><span class="token punctuation">;</span> 
<span class="token keyword">public</span> <span class="token variable">$model</span><span class="token punctuation">;</span> 
<span class="token keyword">public</span> <span class="token keyword">function</span> <span class="token function-definition function">__construct</span><span class="token punctuation">(</span><span class="token variable">$color</span><span class="token punctuation">,</span> <span class="token variable">$model</span><span class="token punctuation">)</span> <span class="token punctuation">{</span> 
<span class="token variable">$this</span><span class="token operator">-&gt;</span><span class="token property">color</span> <span class="token operator">=</span> <span class="token variable">$color</span><span class="token punctuation">;</span> 
<span class="token variable">$this</span><span class="token operator">-&gt;</span><span class="token property">model</span> <span class="token operator">=</span> <span class="token variable">$model</span><span class="token punctuation">;</span> 
<span class="token punctuation">}</span> 
<span class="token keyword">public</span> <span class="token keyword">function</span> <span class="token function-definition function">message</span><span class="token punctuation">(</span><span class="token punctuation">)</span> <span class="token punctuation">{</span> 
<span class="token keyword">return</span> <span class="token string double-quoted-string">"My bike is a "</span> <span class="token operator">.</span> <span class="token variable">$this</span><span class="token operator">-&gt;</span><span class="token property">color</span> <span class="token operator">.</span> <span class="token string double-quoted-string">" "</span> <span class="token operator">.</span> <span class="token variable">$this</span><span class="token operator">-&gt;</span><span class="token property">model</span> <span class="token operator">.</span> <span class="token string double-quoted-string">"!"</span><span class="token punctuation">;</span> 
<span class="token punctuation">}</span> 
<span class="token punctuation">}</span> 

<span class="token variable">$myBike</span> <span class="token operator">=</span> <span class="token keyword">new</span> <span class="token class-name">Bike</span><span class="token punctuation">(</span><span class="token string double-quoted-string">"red"</span><span class="token punctuation">,</span> <span class="token string double-quoted-string">"Honda"</span><span class="token punctuation">)</span><span class="token punctuation">;</span> 
<span class="token keyword">echo</span> <span class="token variable">$myBike</span> <span class="token operator">-&gt;</span> <span class="token function">message</span><span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">;</span> 
<span class="token delimiter important">?&gt;</span></span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h2>Escape Characters</h2>
                      <p>
                        Escape sequences are used for escaping a character
                        during string parsing. It is also used for giving
                        special meaning to represent line breaks, tabs, alerts
                        and more.
                      </p>
                      <h3>Line feed</h3>
                      <p>It adds a newline</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token php language-php"><span class="token delimiter important">&lt;?php</span>
<span class="token keyword">echo</span> <span class="token string double-quoted-string">"\n"</span><span class="token punctuation">;</span>
<span class="token delimiter important">?&gt;</span></span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>Carriage return</h3>
                      <p>
                        It inserts a carriage return in the text at this point.
                      </p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token php language-php"><span class="token delimiter important">&lt;?php</span>
<span class="token keyword">echo</span> <span class="token string double-quoted-string">"\r"</span><span class="token punctuation">;</span>
<span class="token delimiter important">?&gt;</span></span>
</code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>Horizontal tab</h3>
                      <p>It gives a horizontal tab space</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token php language-php"><span class="token delimiter important">&lt;?php</span>
<span class="token keyword">echo</span> <span class="token string double-quoted-string">"\t"</span><span class="token punctuation">;</span>
<span class="token delimiter important">?&gt;</span></span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>Vertical tab</h3>
                      <p>It gives a vertical tab space</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token php language-php"><span class="token delimiter important">&lt;?php</span>
<span class="token keyword">echo</span> <span class="token string double-quoted-string">"\v"</span><span class="token punctuation">;</span>
<span class="token delimiter important">?&gt;</span></span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>Escape</h3>
                      <p>It is used for escape characters</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token php language-php"><span class="token delimiter important">&lt;?php</span>
<span class="token keyword">echo</span> <span class="token string double-quoted-string">"\e"</span><span class="token punctuation">;</span>
<span class="token delimiter important">?&gt;</span></span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>Form feed</h3>
                      <p>
                        It is commonly used as page separators but now is also
                        used as section separators.
                      </p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token php language-php"><span class="token delimiter important">&lt;?php</span>
<span class="token keyword">echo</span> <span class="token string double-quoted-string">"\f"</span><span class="token punctuation">;</span>
<span class="token delimiter important">?&gt;</span></span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>Backslash</h3>
                      <p>It adds a backslash</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token php language-php"><span class="token delimiter important">&lt;?php</span>
<span class="token keyword">echo</span> <span class="token string double-quoted-string">"\\"</span><span class="token punctuation">;</span>
<span class="token delimiter important">?&gt;</span></span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>Dollar sign</h3>
                      <p>
                        Print the next character as a dollar, not as part of a
                        variable
                      </p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token php language-php"><span class="token delimiter important">&lt;?php</span>
<span class="token keyword">echo</span> <span class="token string double-quoted-string">"\$"</span><span class="token punctuation">;</span>
<span class="token delimiter important">?&gt;</span></span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>Single quote</h3>
                      <p>
                        Print the next character as a single quote, not a string
                        closer
                      </p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token php language-php"><span class="token delimiter important">&lt;?php</span>
<span class="token keyword">echo</span> <span class="token string double-quoted-string">"\'"</span><span class="token punctuation">;</span>
<span class="token delimiter important">?&gt;</span></span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>Double quote</h3>
                      <p>
                        Print the next character as a double quote, not a string
                        closer
                      </p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token php language-php"><span class="token delimiter important">&lt;?php</span>
<span class="token keyword">echo</span> <span class="token string double-quoted-string">"\""</span><span class="token punctuation">;</span>
<span class="token delimiter important">?&gt;</span></span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h2>Operators</h2>
                      <p>
                        Operators are symbols that tell the compiler or
                        interpreter to perform specific mathematical or logical
                        manipulations. These are of several types.
                      </p>
                      <h2>Arithmetic Operators</h2>
                      <h3>Addition</h3>
                      <p>Sum of $x and $y</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$x</span> <span class="token operator">+</span> <span class="token variable">$y</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>Subtraction</h3>
                      <p>Difference of $x and $y</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$x</span> <span class="token operator">-</span> <span class="token variable">$y</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>Multiplication</h3>
                      <p>Product of $x and $y</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$x</span> <span class="token operator">*</span> <span class="token variable">$y</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>Division</h3>
                      <p>Quotient of $x and $y</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$x</span> <span class="token operator">/</span> <span class="token variable">$y</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>Modulus</h3>
                      <p>The remainder of $x divided by $y</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$x</span> <span class="token operator">%</span> <span class="token variable">$y</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>Exponentiation</h3>
                      <p>Result of raising $x to the $y'th power</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$x</span> <span class="token operator">**</span> <span class="token variable">$y</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h2>PHP Assignment Operators</h2>
                      <p>
                        The PHP assignment operators are used with numeric
                        values to write a value to a variable.
                      </p>
                      <h3>x = y</h3>
                      <p>
                        The left operand gets set to the value of the expression
                        on the right
                      </p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php">x <span class="token operator">=</span> y</code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>x += y</h3>
                      <p>Addition</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php">x <span class="token operator">=</span> x <span class="token operator">+</span> y</code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>x -= y</h3>
                      <p>Subtraction</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php">x <span class="token operator">=</span> x <span class="token operator">-</span> y</code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>x *= y</h3>
                      <p>Multiplication</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php">x <span class="token operator">=</span> x <span class="token operator">*</span> y</code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>x /= y</h3>
                      <p>Division</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php">x <span class="token operator">=</span> x <span class="token operator">/</span> y</code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>x %= y</h3>
                      <p>Modulus</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php">x <span class="token operator">=</span> x <span class="token operator">%</span> y</code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h2>PHP Comparison Operators</h2>
                      <h3>Equal</h3>
                      <p>Returns true if $x is equal to $y</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$x</span> <span class="token operator">==</span> <span class="token variable">$y</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>Identical</h3>
                      <p>
                        Returns true if $x is equal to $y, and they are of the
                        same type
                      </p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$x</span> <span class="token operator">===</span> <span class="token variable">$y</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>Not equal</h3>
                      <p>Returns true if $x is not equal to $y</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$x</span> <span class="token operator">!=</span> <span class="token variable">$y</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>Not equal</h3>
                      <p>Returns true if $x is not equal to $y</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$x</span> <span class="token operator">&lt;</span><span class="token operator">&gt;</span> <span class="token variable">$y</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>Not identical</h3>
                      <p>
                        Returns true if $x is not equal to $y, or they are not
                        of the same type
                      </p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$x</span> <span class="token operator">!==</span> <span class="token variable">$y</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>Greater than</h3>
                      <p>Returns true if $x is greater than $y</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$x</span> <span class="token operator">&gt;</span> <span class="token variable">$y</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>Less than</h3>
                      <p>Returns true if $x is less than $y</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$x</span> <span class="token operator">&lt;</span> <span class="token variable">$y</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>Greater than or equal to</h3>
                      <p>Returns true if $x is greater than or equal to $y</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$x</span> <span class="token operator">&gt;=</span> <span class="token variable">$y</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>Less than or equal to</h3>
                      <p>Returns true if $x is less than or equal to $y</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$x</span> <span class="token operator">&lt;=</span> <span class="token variable">$y</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h2>PHP Increment / Decrement Operators</h2>
                      <h3>Pre-increment</h3>
                      <p>Increments $x by one, then returns $x</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token operator">=</span><span class="token operator">++</span><span class="token variable">$x</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>Post-increment</h3>
                      <p>Returns $x, then increments $x by one</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$x</span><span class="token operator">++</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>Pre-decrement</h3>
                      <p>Decrements $x by one, then returns $x</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token operator">--</span><span class="token variable">$x</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>Post-decrement</h3>
                      <p>Returns $x, then decrements $x by one</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$x</span><span class="token operator">--</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h2>PHP Logical Operators</h2>
                      <h3>And</h3>
                      <p>True if both $x and $y are true</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$x</span> <span class="token keyword">and</span> <span class="token variable">$y</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>Or</h3>
                      <p>True if either $x or $y is true</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$x</span> <span class="token keyword">or</span> <span class="token variable">$y</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>Xor</h3>
                      <p>True if either $x or $y is true, but not both</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$x</span> <span class="token keyword">xor</span> <span class="token variable">$y</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>And</h3>
                      <p>True if both $x and $y are true</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$x</span> <span class="token operator">&amp;&amp;</span> <span class="token variable">$y</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>Or</h3>
                      <p>True if either $x or $y is true</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$x</span> <span class="token operator">||</span> <span class="token variable">$y</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>Not</h3>
                      <p>True if $x is not true</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token operator">!</span><span class="token variable">$x</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <p></p>
                      <div class="cwhads my-4">
                        <ins
                          class="adsbygoogle"
                          style="display: block; height: 280px"
                          data-ad-client="ca-pub-9655830461045889"
                          data-ad-slot="8999979664"
                          data-ad-format="auto"
                          data-full-width-responsive="true"
                          data-adsbygoogle-status="done"
                        >
                          <div
                            id="aswift_1_host"
                            style="
                              border: none;
                              height: 280px;
                              width: 944px;
                              margin: 0px;
                              padding: 0px;
                              position: relative;
                              visibility: visible;
                              background-color: transparent;
                              display: inline-block;
                            "
                          ></div>
                        </ins>
                      </div>
                      <p></p>
                      <h2>PHP String Operators</h2>
                      <h3>Concatenation</h3>
                      <p>Concatenation of $txt1 and $txt2</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$txt1</span> <span class="token operator">.</span> <span class="token variable">$txt2</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>Concatenation assignment</h3>
                      <p>Appends $txt2 to $txt1</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$txt1</span> <span class="token operator">.=</span> <span class="token variable">$txt2</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h2>PHP Array Operators</h2>
                      <h3>Union</h3>
                      <p>Union of $x and $y</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$x</span> <span class="token operator">+</span> <span class="token variable">$y</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>Equality</h3>
                      <p>
                        Returns true if $x and $y have the same key/value pairs
                      </p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$x</span> <span class="token operator">==</span> <span class="token variable">$y</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>Identity</h3>
                      <p>
                        Returns true if $x and $y have the same key/value pairs
                        in the same order and of the same types
                      </p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$x</span> <span class="token operator">===</span> <span class="token variable">$y</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>Inequality</h3>
                      <p>Returns true if $x is not equal to $y</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$x</span> <span class="token operator">!=</span> <span class="token variable">$y</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>Inequality</h3>
                      <p>Returns true if $x is not equal to $y</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$x</span> <span class="token operator">&lt;</span><span class="token operator">&gt;</span> <span class="token variable">$y</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>Non-identity</h3>
                      <p>Returns true if $x is not identical to $y</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$x</span> <span class="token operator">!==</span> <span class="token variable">$y</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h2>PHP Conditional Assignment Operators</h2>
                      <h3>Ternary</h3>
                      <p>
                        Returns the value of $x. The value of $x is expr2 if
                        expr1 = TRUE. The value of $x is expr3 if expr1 = FALSE
                      </p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$x</span> <span class="token operator">=</span> expr1 <span class="token operator">?</span> expr2 <span class="token punctuation">:</span> expr3</code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h2>Conditional Statements</h2>
                      <p>
                        Conditional statements are used to perform operations
                        based on some condition.
                      </p>
                      <h3>If Statement</h3>
                      <p>
                        if statement checks the condition and if it is True,
                        then the block of if statement executes; otherwise,
                        control skips that block of code.
                      </p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token keyword">if</span> <span class="token punctuation">(</span>condition<span class="token punctuation">)</span> <span class="token punctuation">{</span> 
<span class="token comment">// code to execute if condition is met </span>
<span class="token punctuation">}</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>If..Else</h3>
                      <p>
                        if the condition of if block evaluates to True, then if
                        block executes otherwise else block executes
                      </p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token keyword">if</span> <span class="token punctuation">(</span>condition<span class="token punctuation">)</span> <span class="token punctuation">{</span> 
<span class="token comment">// code to execute if condition is met </span>
<span class="token punctuation">}</span> <span class="token keyword">else</span> <span class="token punctuation">{</span> 
<span class="token comment">// code to execute if condition is not met </span>
<span class="token punctuation">}</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>If..Elseif..Else</h3>
                      <p>
                        It executes different codes for more than two conditions
                      </p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token keyword">if</span> <span class="token punctuation">(</span>condition<span class="token punctuation">)</span> <span class="token punctuation">{</span> 
<span class="token comment">// code to execute if condition is met </span>
<span class="token punctuation">}</span> <span class="token keyword">elseif</span> <span class="token punctuation">(</span>condition<span class="token punctuation">)</span> <span class="token punctuation">{</span> 
<span class="token comment">// code to execute if this condition is met </span>
<span class="token punctuation">}</span> <span class="token keyword">else</span> <span class="token punctuation">{</span> 
<span class="token comment">// code to execute if none of the conditions are met </span>
<span class="token punctuation">}</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>Switch Statement</h3>
                      <p>
                        It allows a variable to be tested for equality against a
                        list of values (cases).
                      </p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token keyword">switch</span> <span class="token punctuation">(</span>n<span class="token punctuation">)</span> <span class="token punctuation">{</span> 
<span class="token keyword">case</span> x<span class="token punctuation">:</span> 
code to execute <span class="token keyword">if</span> n<span class="token operator">=</span>x<span class="token punctuation">;</span> 
<span class="token keyword">break</span><span class="token punctuation">;</span> 
<span class="token keyword">case</span> y<span class="token punctuation">:</span> 
code to execute <span class="token keyword">if</span> n<span class="token operator">=</span>y<span class="token punctuation">;</span> 
<span class="token keyword">break</span><span class="token punctuation">;</span> 
<span class="token keyword">case</span> z<span class="token punctuation">:</span> 
code to execute <span class="token keyword">if</span> n<span class="token operator">=</span>z<span class="token punctuation">;</span> 
<span class="token keyword">break</span><span class="token punctuation">;</span> 
<span class="token comment">// add more cases as needed </span>
<span class="token keyword">default</span><span class="token punctuation">:</span> 
code to execute <span class="token keyword">if</span> n is neither of the above<span class="token punctuation">;</span> 
<span class="token punctuation">}</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h2>Loops</h2>
                      <p>
                        Iterative statements or Loops facilitate programmers to
                        execute any block of code lines repeatedly.
                      </p>
                      <h3>For Loop</h3>
                      <p>
                        It is used to iterate the statements several times. It
                        is frequently used to traverse the data structures like
                        the array and linked list.
                      </p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token keyword">for</span> <span class="token punctuation">(</span>starting counter value<span class="token punctuation">;</span> ending counter value<span class="token punctuation">;</span> increment by which 
to increase<span class="token punctuation">)</span> <span class="token punctuation">{</span> 
<span class="token comment">// code to execute goes here </span>
<span class="token punctuation">}</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>Foreach Loop</h3>
                      <p>
                        The foreach loop loops through a block of code for each
                        element in an array.
                      </p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token keyword">foreach</span> <span class="token punctuation">(</span><span class="token variable">$InsertYourArrayName</span> <span class="token keyword">as</span> <span class="token variable">$value</span><span class="token punctuation">)</span> <span class="token punctuation">{</span> 
<span class="token comment">// code to execute goes here </span>
<span class="token punctuation">}</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>While Loop</h3>
                      <p>
                        It iterate the block of code as long as a specified
                        condition is True or vice versa
                      </p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token keyword">while</span> <span class="token punctuation">(</span>condition that must apply<span class="token punctuation">)</span> <span class="token punctuation">{</span> 
<span class="token comment">// code to execute goes here </span>
<span class="token punctuation">}</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>Do-While Loop</h3>
                      <p>
                        This loop is very similar to the while loop with one
                        difference, i.e., the body of the do-while loop is
                        executed at least once even if the condition is False.
                        It is an exit-controlled loop.
                      </p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token keyword">do</span> <span class="token punctuation">{</span> 
<span class="token comment">// code to execute goes here; </span>
<span class="token punctuation">}</span> <span class="token keyword">while</span> <span class="token punctuation">(</span>condition that must apply<span class="token punctuation">)</span><span class="token punctuation">;</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h2>Predefined Variables</h2>
                      <p>
                        PHP provides a large number of predefined variables to
                        all scripts. The variables represent everything from
                        external variables to built-in environment variables,
                        last error messages etc. All this information is defined
                        in some predefined variables.
                      </p>
                      <h3>$GLOBALS</h3>
                      <p>
                        $GLOBALS is a PHP super global variable which is used to
                        access global variables from anywhere in the PHP script.
                      </p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token php language-php"><span class="token delimiter important">&lt;?php</span> 
<span class="token variable">$a</span> <span class="token operator">=</span> <span class="token number">10</span><span class="token punctuation">;</span> 
<span class="token variable">$b</span> <span class="token operator">=</span> <span class="token number">15</span><span class="token punctuation">;</span> 

<span class="token keyword">function</span> <span class="token function-definition function">addition</span><span class="token punctuation">(</span><span class="token punctuation">)</span> <span class="token punctuation">{</span> 
<span class="token variable">$GLOBALS</span><span class="token punctuation">[</span><span class="token string single-quoted-string">'c'</span><span class="token punctuation">]</span> <span class="token operator">=</span> <span class="token variable">$GLOBALS</span><span class="token punctuation">[</span><span class="token string single-quoted-string">'a'</span><span class="token punctuation">]</span> <span class="token operator">+</span> <span class="token variable">$GLOBALS</span><span class="token punctuation">[</span><span class="token string single-quoted-string">'b'</span><span class="token punctuation">]</span><span class="token punctuation">;</span> 
<span class="token punctuation">}</span> 
<span class="token function">addition</span><span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">;</span> 
<span class="token keyword">echo</span> <span class="token variable">$c</span><span class="token punctuation">;</span> 
<span class="token delimiter important">?&gt;</span></span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>$_SERVER</h3>
                      <p>
                        Returns the filename of the currently executing script.
                        $_SERVER is a PHP super global variable which holds
                        information about headers, paths, and script locations.
                      </p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$_SERVER</span><span class="token punctuation">[</span><span class="token string single-quoted-string">'PHP_SELF'</span><span class="token punctuation">]</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <p>
                        Returns the version of the Common Gateway Interface
                        (CGI) the server is using
                      </p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$_SERVER</span><span class="token punctuation">[</span><span class="token string single-quoted-string">'GATEWAY_INTERFACE'</span><span class="token punctuation">]</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <p>Returns the IP address of the host server</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$_SERVER</span><span class="token punctuation">[</span><span class="token string single-quoted-string">'SERVER_ADDR'</span><span class="token punctuation">]</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <p>
                        Returns the name of the host server (such as
                        www.codewithharry.com)
                      </p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$_SERVER</span><span class="token punctuation">[</span><span class="token string single-quoted-string">'SERVER_NAME'</span><span class="token punctuation">]</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <p>
                        Returns the server identification string (such as
                        Apache/2.2.24)
                      </p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$_SERVER</span><span class="token punctuation">[</span><span class="token string single-quoted-string">'SERVER_SOFTWARE'</span><span class="token punctuation">]</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <p>
                        Returns the name and revision of the information
                        protocol (such as HTTP/1.1)
                      </p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$_SERVER</span><span class="token punctuation">[</span><span class="token string single-quoted-string">'SERVER_PROTOCOL'</span><span class="token punctuation">]</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <p>
                        Returns the request method used to access the page (such
                        as POST)
                      </p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$_SERVER</span><span class="token punctuation">[</span><span class="token string single-quoted-string">'REQUEST_METHOD'</span><span class="token punctuation">]</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <p>
                        Returns the timestamp of the start of the request (such
                        as 1377687496)
                      </p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$_SERVER</span><span class="token punctuation">[</span><span class="token string single-quoted-string">'REQUEST_TIME'</span><span class="token punctuation">]</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <p>
                        Returns the query string if the page is accessed via a
                        query string
                      </p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$_SERVER</span><span class="token punctuation">[</span><span class="token string single-quoted-string">'QUERY_STRING'</span><span class="token punctuation">]</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <p>Returns the Accept header from the current request</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$_SERVER</span><span class="token punctuation">[</span><span class="token string single-quoted-string">'HTTP_ACCEPT'</span><span class="token punctuation">]</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <p>
                        Returns the Accept_Charset header from the current
                        request (such as utf-8,ISO-8859-1)
                      </p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$_SERVER</span><span class="token punctuation">[</span><span class="token string single-quoted-string">'HTTP_ACCEPT_CHARSET'</span><span class="token punctuation">]</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <p>Returns the Host header from the current request</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$_SERVER</span><span class="token punctuation">[</span><span class="token string single-quoted-string">'HTTP_HOST'</span><span class="token punctuation">]</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <p>
                        Returns the complete URL of the current page (not
                        reliable because not all user-agents support it)
                      </p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$_SERVER</span><span class="token punctuation">[</span><span class="token string single-quoted-string">'HTTP_REFERER'</span><span class="token punctuation">]</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <p>
                        Is the script queried through a secure HTTP protocol?
                      </p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$_SERVER</span><span class="token punctuation">[</span><span class="token string single-quoted-string">'HTTPS'</span><span class="token punctuation">]</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <p>
                        Returns the IP address from where the user is viewing
                        the current page
                      </p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$_SERVER</span><span class="token punctuation">[</span><span class="token string single-quoted-string">'REMOTE_ADDR'</span><span class="token punctuation">]</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <p>
                        Returns the Hostname from where the user is viewing the
                        current page
                      </p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$_SERVER</span><span class="token punctuation">[</span><span class="token string single-quoted-string">'REMOTE_HOST'</span><span class="token punctuation">]</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <p>
                        Returns the port being used on the user's machine to
                        communicate with the web server
                      </p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$_SERVER</span><span class="token punctuation">[</span><span class="token string single-quoted-string">'REMOTE_PORT'</span><span class="token punctuation">]</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <p>
                        Returns the absolute pathname of the currently executing
                        script
                      </p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$_SERVER</span><span class="token punctuation">[</span><span class="token string single-quoted-string">'SCRIPT_FILENAME'</span><span class="token punctuation">]</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <p>
                        Returns the value given to the SERVER_ADMIN directive in
                        the web server configuration file (if your script runs
                        on a virtual host, it will be the value defined for that
                        virtual host) (such as someone@codewithharry.com)
                      </p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$_SERVER</span><span class="token punctuation">[</span><span class="token string single-quoted-string">'SERVER_ADMIN'</span><span class="token punctuation">]</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <p>
                        Returns the port on the server machine being used by the
                        webserver for communication (such as 80)
                      </p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$_SERVER</span><span class="token punctuation">[</span><span class="token string single-quoted-string">'SERVER_PORT'</span><span class="token punctuation">]</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <p>
                        Returns the server version and virtual hostname which
                        are added to server-generated pages
                      </p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$_SERVER</span><span class="token punctuation">[</span><span class="token string single-quoted-string">'SERVER_SIGNATURE'</span><span class="token punctuation">]</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <p>
                        Returns the file system based path to the current script
                      </p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$_SERVER</span><span class="token punctuation">[</span><span class="token string single-quoted-string">'PATH_TRANSLATED'</span><span class="token punctuation">]</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <p>Returns the path of the current script</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$_SERVER</span><span class="token punctuation">[</span><span class="token string single-quoted-string">'SCRIPT_NAME'</span><span class="token punctuation">]</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <p>Returns the URI of the current page</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token variable">$_SERVER</span><span class="token punctuation">[</span><span class="token string single-quoted-string">'SCRIPT_URI'</span><span class="token punctuation">]</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>$_GET</h3>
                      <p>
                        PHP $_GET is a PHP super global variable which is used
                        to collect form data after submitting an HTML form with
                        method="get".
                      </p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token php language-php"><span class="token delimiter important">&lt;?php</span> 
<span class="token keyword">echo</span> <span class="token string double-quoted-string">"Hello"</span> <span class="token operator">.</span> <span class="token variable">$_GET</span><span class="token punctuation">[</span><span class="token string single-quoted-string">'Example'</span><span class="token punctuation">]</span> <span class="token operator">.</span> <span class="token string double-quoted-string">" at "</span> <span class="token operator">.</span> <span class="token variable">$_GET</span><span class="token punctuation">[</span><span class="token string single-quoted-string">'web'</span><span class="token punctuation">]</span><span class="token punctuation">;</span> 
<span class="token delimiter important">?&gt;</span></span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>$_POST</h3>
                      <p>
                        PHP $_POST is a PHP super global variable which is used
                        to collect form data after submitting an HTML form with
                        method="post". $_POST is also widely used to pass
                        variables.
                      </p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>html</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>body</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>form</span> <span class="token attr-name">method</span><span class="token attr-value"><span class="token punctuation attr-equals">=</span><span class="token punctuation">"</span>post<span class="token punctuation">"</span></span> <span class="token attr-name">action</span><span class="token attr-value"><span class="token punctuation attr-equals">=</span><span class="token punctuation">"</span><span class="token php language-php"><span class="token delimiter important">&lt;?php</span> <span class="token keyword">echo</span> <span class="token variable">$_SERVER</span><span class="token punctuation">[</span><span class="token string single-quoted-string">'PHP_SELF'</span><span class="token punctuation">]</span><span class="token punctuation">;</span><span class="token delimiter important">?&gt;</span></span><span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
Name: <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>input</span> <span class="token attr-name">type</span><span class="token attr-value"><span class="token punctuation attr-equals">=</span><span class="token punctuation">"</span>text<span class="token punctuation">"</span></span> <span class="token attr-name">name</span><span class="token attr-value"><span class="token punctuation attr-equals">=</span><span class="token punctuation">"</span>fname<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>input</span> <span class="token attr-name">type</span><span class="token attr-value"><span class="token punctuation attr-equals">=</span><span class="token punctuation">"</span>submit<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>form</span><span class="token punctuation">&gt;</span></span>
<span class="token php language-php"><span class="token delimiter important">&lt;?php</span>
<span class="token keyword">if</span> <span class="token punctuation">(</span><span class="token variable">$_SERVER</span><span class="token punctuation">[</span><span class="token string double-quoted-string">"REQUEST_METHOD"</span><span class="token punctuation">]</span> <span class="token operator">==</span> <span class="token string double-quoted-string">"POST"</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
<span class="token variable">$name</span> <span class="token operator">=</span> <span class="token variable">$_POST</span><span class="token punctuation">[</span><span class="token string single-quoted-string">'fname'</span><span class="token punctuation">]</span><span class="token punctuation">;</span>
<span class="token keyword">if</span> <span class="token punctuation">(</span><span class="token keyword">empty</span><span class="token punctuation">(</span><span class="token variable">$name</span><span class="token punctuation">)</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
<span class="token keyword">echo</span> <span class="token string double-quoted-string">"Please Enter your name"</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span> <span class="token keyword">else</span> <span class="token punctuation">{</span>
<span class="token keyword">echo</span> <span class="token variable">$name</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>
<span class="token punctuation">}</span>
<span class="token delimiter important">?&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>body</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>html</span><span class="token punctuation">&gt;</span></span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>$_REQUEST</h3>
                      <p>
                        PHP $_REQUEST is a PHP super global variable which is
                        used to collect data after submitting an HTML form.
                      </p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>html</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>body</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>form</span> <span class="token attr-name">method</span><span class="token attr-value"><span class="token punctuation attr-equals">=</span><span class="token punctuation">"</span>post<span class="token punctuation">"</span></span> <span class="token attr-name">action</span><span class="token attr-value"><span class="token punctuation attr-equals">=</span><span class="token punctuation">"</span><span class="token php language-php"><span class="token delimiter important">&lt;?php</span> <span class="token keyword">echo</span> <span class="token variable">$_SERVER</span><span class="token punctuation">[</span><span class="token string single-quoted-string">'PHP_SELF'</span><span class="token punctuation">]</span><span class="token punctuation">;</span><span class="token delimiter important">?&gt;</span></span><span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
Name: <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>input</span> <span class="token attr-name">type</span><span class="token attr-value"><span class="token punctuation attr-equals">=</span><span class="token punctuation">"</span>text<span class="token punctuation">"</span></span> <span class="token attr-name">name</span><span class="token attr-value"><span class="token punctuation attr-equals">=</span><span class="token punctuation">"</span>fname<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>input</span> <span class="token attr-name">type</span><span class="token attr-value"><span class="token punctuation attr-equals">=</span><span class="token punctuation">"</span>submit<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>form</span><span class="token punctuation">&gt;</span></span>
<span class="token php language-php"><span class="token delimiter important">&lt;?php</span>
<span class="token keyword">if</span> <span class="token punctuation">(</span><span class="token variable">$_SERVER</span><span class="token punctuation">[</span><span class="token string double-quoted-string">"REQUEST_METHOD"</span><span class="token punctuation">]</span> <span class="token operator">==</span> <span class="token string double-quoted-string">"POST"</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
<span class="token variable">$name</span> <span class="token operator">=</span> <span class="token variable">$_REQUEST</span><span class="token punctuation">[</span><span class="token string single-quoted-string">'fname'</span><span class="token punctuation">]</span><span class="token punctuation">;</span>
<span class="token keyword">if</span> <span class="token punctuation">(</span><span class="token keyword">empty</span><span class="token punctuation">(</span><span class="token variable">$name</span><span class="token punctuation">)</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
<span class="token keyword">echo</span> <span class="token string double-quoted-string">"Name is empty"</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span> <span class="token keyword">else</span> <span class="token punctuation">{</span>
<span class="token keyword">echo</span> <span class="token variable">$name</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>
<span class="token punctuation">}</span>
<span class="token delimiter important">?&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>body</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>html</span><span class="token punctuation">&gt;</span></span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <p></p>
                      <div class="cwhads my-4">
                        <ins
                          class="adsbygoogle"
                          style="display: block; height: 280px"
                          data-ad-client="ca-pub-9655830461045889"
                          data-ad-slot="8999979664"
                          data-ad-format="auto"
                          data-full-width-responsive="true"
                          data-adsbygoogle-status="done"
                        >
                          <div
                            id="aswift_2_host"
                            style="
                              border: none;
                              height: 280px;
                              width: 944px;
                              margin: 0px;
                              padding: 0px;
                              position: relative;
                              visibility: visible;
                              background-color: transparent;
                              display: inline-block;
                            "
                          ></div>
                        </ins>
                      </div>
                      <p></p>
                      <h2>Variable-handling Functions</h2>
                      <p>
                        The PHP variable handling functions are part of the PHP
                        core. No installation is required to use these
                        functions.
                      </p>
                      <h3>boolval</h3>
                      <p>
                        Boolval is used to get the boolean value of a variable
                      </p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token php language-php"><span class="token delimiter important">&lt;?php</span> 
<span class="token keyword">echo</span> <span class="token string single-quoted-string">'0: '</span><span class="token operator">.</span><span class="token punctuation">(</span><span class="token function">boolval</span><span class="token punctuation">(</span><span class="token number">0</span><span class="token punctuation">)</span> <span class="token operator">?</span> <span class="token string single-quoted-string">'true'</span> <span class="token punctuation">:</span> <span class="token string single-quoted-string">'false'</span><span class="token punctuation">)</span><span class="token operator">.</span><span class="token string double-quoted-string">"\n"</span><span class="token punctuation">;</span> 
<span class="token keyword">echo</span> <span class="token string single-quoted-string">'42: '</span><span class="token operator">.</span><span class="token punctuation">(</span><span class="token function">boolval</span><span class="token punctuation">(</span><span class="token number">42</span><span class="token punctuation">)</span> <span class="token operator">?</span> <span class="token string single-quoted-string">'true'</span> <span class="token punctuation">:</span> <span class="token string single-quoted-string">'false'</span><span class="token punctuation">)</span><span class="token operator">.</span><span class="token string double-quoted-string">"\n"</span><span class="token punctuation">;</span> 
<span class="token keyword">echo</span> <span class="token string single-quoted-string">'0.0: '</span><span class="token operator">.</span><span class="token punctuation">(</span><span class="token function">boolval</span><span class="token punctuation">(</span><span class="token number">0.0</span><span class="token punctuation">)</span> <span class="token operator">?</span> <span class="token string single-quoted-string">'true'</span> <span class="token punctuation">:</span> <span class="token string single-quoted-string">'false'</span><span class="token punctuation">)</span><span class="token operator">.</span><span class="token string double-quoted-string">"\n"</span><span class="token punctuation">;</span> 
<span class="token keyword">echo</span> <span class="token string single-quoted-string">'4.2: '</span><span class="token operator">.</span><span class="token punctuation">(</span><span class="token function">boolval</span><span class="token punctuation">(</span><span class="token number">4.2</span><span class="token punctuation">)</span> <span class="token operator">?</span> <span class="token string single-quoted-string">'true'</span> <span class="token punctuation">:</span> <span class="token string single-quoted-string">'false'</span><span class="token punctuation">)</span><span class="token operator">.</span><span class="token string double-quoted-string">"\n"</span><span class="token punctuation">;</span> 
<span class="token keyword">echo</span> <span class="token string single-quoted-string">'"": '</span><span class="token operator">.</span><span class="token punctuation">(</span><span class="token function">boolval</span><span class="token punctuation">(</span><span class="token string double-quoted-string">""</span><span class="token punctuation">)</span> <span class="token operator">?</span> <span class="token string single-quoted-string">'true'</span> <span class="token punctuation">:</span> <span class="token string single-quoted-string">'false'</span><span class="token punctuation">)</span><span class="token operator">.</span><span class="token string double-quoted-string">"\n"</span><span class="token punctuation">;</span> 
<span class="token keyword">echo</span> <span class="token string single-quoted-string">'"string": '</span><span class="token operator">.</span><span class="token punctuation">(</span><span class="token function">boolval</span><span class="token punctuation">(</span><span class="token string double-quoted-string">"string"</span><span class="token punctuation">)</span> <span class="token operator">?</span> <span class="token string single-quoted-string">'true'</span> <span class="token punctuation">:</span> <span class="token string single-quoted-string">'false'</span><span class="token punctuation">)</span><span class="token operator">.</span><span class="token string double-quoted-string">"\n"</span><span class="token punctuation">;</span> 
<span class="token keyword">echo</span> <span class="token string single-quoted-string">'"0": '</span><span class="token operator">.</span><span class="token punctuation">(</span><span class="token function">boolval</span><span class="token punctuation">(</span><span class="token string double-quoted-string">"0"</span><span class="token punctuation">)</span> <span class="token operator">?</span> <span class="token string single-quoted-string">'true'</span> <span class="token punctuation">:</span> <span class="token string single-quoted-string">'false'</span><span class="token punctuation">)</span><span class="token operator">.</span><span class="token string double-quoted-string">"\n"</span><span class="token punctuation">;</span> 
<span class="token keyword">echo</span> <span class="token string single-quoted-string">'"1": '</span><span class="token operator">.</span><span class="token punctuation">(</span><span class="token function">boolval</span><span class="token punctuation">(</span><span class="token string double-quoted-string">"1"</span><span class="token punctuation">)</span> <span class="token operator">?</span> <span class="token string single-quoted-string">'true'</span> <span class="token punctuation">:</span> <span class="token string single-quoted-string">'false'</span><span class="token punctuation">)</span><span class="token operator">.</span><span class="token string double-quoted-string">"\n"</span><span class="token punctuation">;</span> 
<span class="token keyword">echo</span> <span class="token string single-quoted-string">'[1, 2]: '</span><span class="token operator">.</span><span class="token punctuation">(</span><span class="token function">boolval</span><span class="token punctuation">(</span><span class="token punctuation">[</span><span class="token number">1</span><span class="token punctuation">,</span> <span class="token number">2</span><span class="token punctuation">]</span><span class="token punctuation">)</span> <span class="token operator">?</span> <span class="token string single-quoted-string">'true'</span> <span class="token punctuation">:</span> <span class="token string single-quoted-string">'false'</span><span class="token punctuation">)</span><span class="token operator">.</span><span class="token string double-quoted-string">"\n"</span><span class="token punctuation">;</span> 
<span class="token keyword">echo</span> <span class="token string single-quoted-string">'[]: '</span><span class="token operator">.</span><span class="token punctuation">(</span><span class="token function">boolval</span><span class="token punctuation">(</span><span class="token punctuation">[</span><span class="token punctuation">]</span><span class="token punctuation">)</span> <span class="token operator">?</span> <span class="token string single-quoted-string">'true'</span> <span class="token punctuation">:</span> <span class="token string single-quoted-string">'false'</span><span class="token punctuation">)</span><span class="token operator">.</span><span class="token string double-quoted-string">"\n"</span><span class="token punctuation">;</span> 
<span class="token keyword">echo</span> <span class="token string single-quoted-string">'stdClass: '</span><span class="token operator">.</span><span class="token punctuation">(</span><span class="token function">boolval</span><span class="token punctuation">(</span><span class="token keyword">new</span> <span class="token class-name">stdClass</span><span class="token punctuation">)</span> <span class="token operator">?</span> <span class="token string single-quoted-string">'true'</span> <span class="token punctuation">:</span> <span class="token string single-quoted-string">'false'</span><span class="token punctuation">)</span><span class="token operator">.</span><span class="token string double-quoted-string">"\n"</span><span class="token punctuation">;</span> 
<span class="token delimiter important">?&gt;</span></span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>isset</h3>
                      <p>
                        It is used to check whether a variable is empty. It also
                        checks whether the variable is set/declared:
                      </p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token php language-php"><span class="token delimiter important">&lt;?php</span> 
<span class="token variable">$x</span> <span class="token operator">=</span> <span class="token number">0</span><span class="token punctuation">;</span> 
<span class="token comment">// True because $x is set </span>
<span class="token keyword">if</span> <span class="token punctuation">(</span><span class="token keyword">isset</span><span class="token punctuation">(</span><span class="token variable">$x</span><span class="token punctuation">)</span><span class="token punctuation">)</span> <span class="token punctuation">{</span> 
<span class="token keyword">echo</span> <span class="token string double-quoted-string">"Variable 'x' is set"</span><span class="token punctuation">;</span> 
<span class="token punctuation">}</span> 
</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>unset</h3>
                      <p>It unsets variables.</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token php language-php"><span class="token delimiter important">&lt;?php</span> 
<span class="token variable">$a</span> <span class="token operator">=</span> <span class="token string double-quoted-string">"Namaste world!"</span><span class="token punctuation">;</span> 
<span class="token keyword">echo</span> <span class="token string double-quoted-string">"The value of 'a' before unset: "</span> <span class="token operator">.</span> <span class="token variable">$a</span> <span class="token punctuation">;</span> 
<span class="token keyword">unset</span><span class="token punctuation">(</span><span class="token variable">$a</span><span class="token punctuation">)</span><span class="token punctuation">;</span> 
<span class="token keyword">echo</span> <span class="token string double-quoted-string">"The value of 'a' after unset: "</span> <span class="token operator">.</span> <span class="token variable">$a</span><span class="token punctuation">;</span> 
<span class="token delimiter important">?&gt;</span></span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>debug_zval_dump</h3>
                      <p>
                        debug_zval_dump is used to dump a string representation
                        of an internal zval structure to output
                      </p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token php language-php"><span class="token delimiter important">&lt;?php</span> 
<span class="token variable">$var1</span> <span class="token operator">=</span> <span class="token string single-quoted-string">'Hello'</span><span class="token punctuation">;</span> 
<span class="token variable">$var1</span> <span class="token operator">.=</span> <span class="token string single-quoted-string">' World'</span><span class="token punctuation">;</span> 
<span class="token variable">$var2</span> <span class="token operator">=</span> <span class="token variable">$var1</span><span class="token punctuation">;</span> 

<span class="token function">debug_zval_dump</span><span class="token punctuation">(</span><span class="token variable">$var1</span><span class="token punctuation">)</span><span class="token punctuation">;</span> 
<span class="token delimiter important">?&gt;</span></span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>empty</h3>
                      <p>
                        Empty is used to check whether a variable is empty or
                        not.
                      </p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token php language-php"><span class="token delimiter important">&lt;?php</span> 
<span class="token variable">$var</span> <span class="token operator">=</span> <span class="token number">0</span><span class="token punctuation">;</span> 

<span class="token comment">// Evaluates to true because $var is empty </span>
<span class="token keyword">if</span> <span class="token punctuation">(</span><span class="token keyword">empty</span><span class="token punctuation">(</span><span class="token variable">$var</span><span class="token punctuation">)</span><span class="token punctuation">)</span> <span class="token punctuation">{</span> 
<span class="token keyword">echo</span> <span class="token string single-quoted-string">'$var is either 0, empty, or not set at all'</span><span class="token punctuation">;</span> 
<span class="token punctuation">}</span> 

<span class="token comment">// Evaluates as true because $var is set </span>
<span class="token keyword">if</span> <span class="token punctuation">(</span><span class="token keyword">isset</span><span class="token punctuation">(</span><span class="token variable">$var</span><span class="token punctuation">)</span><span class="token punctuation">)</span> <span class="token punctuation">{</span> 
<span class="token keyword">echo</span> <span class="token string single-quoted-string">'$var is set even though it is empty'</span><span class="token punctuation">;</span> 
<span class="token punctuation">}</span> 
<span class="token delimiter important">?&gt;</span></span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>floatval</h3>
                      <p>It returns the float value of different variables:</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token php language-php"><span class="token delimiter important">&lt;?php</span> 
<span class="token variable">$var</span> <span class="token operator">=</span> <span class="token string single-quoted-string">'122.34343The'</span><span class="token punctuation">;</span> 
<span class="token variable">$float_value_of_var</span> <span class="token operator">=</span> <span class="token function">floatval</span><span class="token punctuation">(</span><span class="token variable">$var</span><span class="token punctuation">)</span><span class="token punctuation">;</span> 
<span class="token keyword">echo</span> <span class="token variable">$float_value_of_var</span><span class="token punctuation">;</span> <span class="token comment">// 122.34343 </span>
<span class="token delimiter important">?&gt;</span></span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>get_defined_vars</h3>
                      <p>It returns all defined variables, as an array:</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token php language-php"><span class="token delimiter important">&lt;?php</span> 
<span class="token variable">$b</span> <span class="token operator">=</span> <span class="token keyword">array</span><span class="token punctuation">(</span><span class="token number">1</span><span class="token punctuation">,</span> <span class="token number">1</span><span class="token punctuation">,</span> <span class="token number">2</span><span class="token punctuation">,</span> <span class="token number">3</span><span class="token punctuation">,</span> <span class="token number">5</span><span class="token punctuation">,</span> <span class="token number">8</span><span class="token punctuation">)</span><span class="token punctuation">;</span> 

<span class="token variable">$arr</span> <span class="token operator">=</span> <span class="token function">get_defined_vars</span><span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">;</span> 

<span class="token comment">// print $b </span>
<span class="token function">print_r</span><span class="token punctuation">(</span><span class="token variable">$arr</span><span class="token punctuation">[</span><span class="token string double-quoted-string">"b"</span><span class="token punctuation">]</span><span class="token punctuation">)</span><span class="token punctuation">;</span> 

<span class="token comment">/* print path to the PHP interpreter (if used as a CGI) 
* e.g. /usr/local/bin/php */</span> 
<span class="token keyword">echo</span> <span class="token variable">$arr</span><span class="token punctuation">[</span><span class="token string double-quoted-string">"_"</span><span class="token punctuation">]</span><span class="token punctuation">;</span> 

<span class="token comment">// print the command-line parameters if any </span>
<span class="token function">print_r</span><span class="token punctuation">(</span><span class="token variable">$arr</span><span class="token punctuation">[</span><span class="token string double-quoted-string">"argv"</span><span class="token punctuation">]</span><span class="token punctuation">)</span><span class="token punctuation">;</span> 

<span class="token comment">// print all the server vars </span>
<span class="token function">print_r</span><span class="token punctuation">(</span><span class="token variable">$arr</span><span class="token punctuation">[</span><span class="token string double-quoted-string">"_SERVER"</span><span class="token punctuation">]</span><span class="token punctuation">)</span><span class="token punctuation">;</span> 

<span class="token comment">// print all the available keys for the arrays of variables </span>
<span class="token function">print_r</span><span class="token punctuation">(</span><span class="token function">array_keys</span><span class="token punctuation">(</span><span class="token function">get_defined_vars</span><span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">)</span><span class="token punctuation">)</span><span class="token punctuation">;</span> 
<span class="token delimiter important">?&gt;</span></span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>get_resource_type</h3>
                      <p>It returns the resource type:</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token php language-php"><span class="token delimiter important">&lt;?php</span> 
<span class="token comment">// prints: stream </span>
<span class="token variable">$fp</span> <span class="token operator">=</span> <span class="token function">fopen</span><span class="token punctuation">(</span><span class="token string double-quoted-string">"foo"</span><span class="token punctuation">,</span> <span class="token string double-quoted-string">"w"</span><span class="token punctuation">)</span><span class="token punctuation">;</span> 
<span class="token keyword">echo</span> <span class="token function">get_resource_type</span><span class="token punctuation">(</span><span class="token variable">$fp</span><span class="token punctuation">)</span> <span class="token operator">.</span> <span class="token string double-quoted-string">"\n"</span><span class="token punctuation">;</span> 

<span class="token comment">// prints: curl </span>
<span class="token variable">$c</span> <span class="token operator">=</span> <span class="token function">curl_init</span> <span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">;</span> 
<span class="token keyword">echo</span> <span class="token function">get_resource_type</span><span class="token punctuation">(</span><span class="token variable">$c</span><span class="token punctuation">)</span> <span class="token operator">.</span> <span class="token string double-quoted-string">"\n"</span><span class="token punctuation">;</span> <span class="token comment">// works prior to PHP 8.0.0 as since 8.0 curl_init returns a CurlHandle object </span>
<span class="token delimiter important">?&gt;</span></span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>gettype</h3>
                      <p>It returns the type of different variables:</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token php language-php"><span class="token delimiter important">&lt;?php</span> 
<span class="token variable">$a</span> <span class="token operator">=</span> <span class="token number">3</span><span class="token punctuation">;</span> 
<span class="token keyword">echo</span> <span class="token function">gettype</span><span class="token punctuation">(</span><span class="token variable">$a</span><span class="token punctuation">)</span> <span class="token punctuation">;</span> 
<span class="token delimiter important">?&gt;</span></span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>intval</h3>
                      <p>
                        It returns the integer value of different variables:
                      </p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token php language-php"><span class="token delimiter important">&lt;?php</span> 
<span class="token keyword">echo</span> <span class="token function">intval</span><span class="token punctuation">(</span><span class="token number">42</span><span class="token punctuation">)</span><span class="token punctuation">;</span> <span class="token delimiter important">?&gt;</span></span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>is_array</h3>
                      <p>To check whether a variable is an array or not:</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token php language-php"><span class="token delimiter important">&lt;?php</span> 
<span class="token variable">$a</span> <span class="token operator">=</span> <span class="token string double-quoted-string">"Hello"</span><span class="token punctuation">;</span> 
<span class="token keyword">echo</span> <span class="token string double-quoted-string">"a is "</span> <span class="token operator">.</span> <span class="token function">is_array</span><span class="token punctuation">(</span><span class="token variable">$a</span><span class="token punctuation">)</span> <span class="token punctuation">;</span><span class="token delimiter important">?&gt;</span></span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h2>Array</h2>
                      <p>
                        An array stores multiple values in one single variable.
                      </p>
                      <h3>Declaring an Array</h3>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token php language-php"><span class="token delimiter important">&lt;?php</span>
<span class="token variable">$cms</span> <span class="token operator">=</span> <span class="token keyword">array</span><span class="token punctuation">(</span><span class="token string double-quoted-string">"Harry"</span><span class="token punctuation">,</span> <span class="token string double-quoted-string">"Lovish"</span><span class="token punctuation">,</span> <span class="token string double-quoted-string">"Rohan"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token keyword">echo</span> <span class="token string double-quoted-string">"Who needs chocolate? Is it"</span> <span class="token operator">.</span> <span class="token variable">$cms</span><span class="token punctuation">[</span><span class="token number">0</span><span class="token punctuation">]</span> <span class="token operator">.</span> <span class="token string double-quoted-string">", "</span> <span class="token operator">.</span>
<span class="token variable">$cms</span><span class="token punctuation">[</span><span class="token number">1</span><span class="token punctuation">]</span> <span class="token operator">.</span> <span class="token string double-quoted-string">" or "</span> <span class="token operator">.</span> <span class="token variable">$cms</span><span class="token punctuation">[</span><span class="token number">2</span><span class="token punctuation">]</span> <span class="token operator">.</span> <span class="token string double-quoted-string">"?"</span><span class="token punctuation">;</span>
<span class="token delimiter important">?&gt;</span></span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h2>Functions</h2>
                      <p>
                        A function is a block of statements that can be used
                        repeatedly in a program
                      </p>
                      <h3>Defining Functions</h3>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token keyword">function</span> <span class="token function-definition function">NameOfTheFunction</span><span class="token punctuation">(</span><span class="token punctuation">)</span> <span class="token punctuation">{</span> 
<span class="token comment">//place PHP code here </span>
<span class="token punctuation">}</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h2>MySQLi Functions</h2>
                      <p>
                        These functions allow you to access MySQL database
                        server.
                      </p>
                      <h3>mysqli_connect() Function</h3>
                      <p>It opens a non-persistent MySQL connection</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token function">mysqli_connect</span><span class="token punctuation">(</span><span class="token punctuation">)</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>mysqli_affected_rows() Function</h3>
                      <p>It returns the number of affected rows</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token function">mysqli_affected_rows</span><span class="token punctuation">(</span><span class="token punctuation">)</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>mysqli_connect_error() Function</h3>
                      <p>
                        It shows the Error description for the connection error
                      </p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token function">mysqli_connect_error</span><span class="token punctuation">(</span><span class="token punctuation">)</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>mysqli_fetch_all() Function</h3>
                      <p>It fetches all result rows as an array</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token function">mysqli_fetch_all</span><span class="token punctuation">(</span><span class="token punctuation">)</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>mysqli_fetch_array() Function</h3>
                      <p>
                        It fetches a result row as an associative, a numeric
                        array, or both
                      </p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token function">mysqli_fetch_array</span><span class="token punctuation">(</span><span class="token punctuation">)</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>mysqli_fetch_assoc() Function</h3>
                      <p>It fetches a result row as an associative array</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token function">mysqli_fetch_assoc</span><span class="token punctuation">(</span><span class="token punctuation">)</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>mysqli_fetch_row() Function</h3>
                      <p>
                        It fetches one row from a result set and returns it as
                        an enumerated array
                      </p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token function">mysqli_fetch_row</span><span class="token punctuation">(</span><span class="token punctuation">)</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>mysqli_kill() Function</h3>
                      <p>It kills a MySQL thread</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token function">mysqli_kill</span><span class="token punctuation">(</span><span class="token punctuation">)</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                      <h3>mysqli_close() Function</h3>
                      <p>It closes a database connection</p>
                      <div class="code-toolbar">
                        <pre
                          class="language-php"
                          tabindex="0"
                        ><code class="language-php"><span class="token function">mysqli_close</span><span class="token punctuation">(</span><span class="token punctuation">)</span></code></pre>
                        <div class="toolbar"></div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </body>
</html>
