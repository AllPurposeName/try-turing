---
layout: lesson
---

# Back-End Try Coding: Pre-work

<a href="../">Back to Curriculum Index</a>

## Introduction

We are excited you will be joining us for an upcoming Try Coding workshop. If you've found yourself on this page and are not yet signed up for one, you can sign up [here](https://www.eventbrite.com/o/turing-school-of-software-amp-design-9895674202)!

Completing this pre-work will set you up for success in our virtual classroom - making sure that everyone feels comfortable with the tools we will use and a bit of foundational knowledge.

<span role="img" aria-label="clock">⏰</span> <strong>Time:</strong> Most participants share that this work took them between 25-35 minutes to complete.

<span role="img" aria-label="woman at computer">👩🏽‍💻</span> <strong>Materials:</strong> It is ideal that you work through this on a laptop or desktop computer. Everything can be done inside a browser with an internet connection.

<span role="img" aria-label="rocket">🚀</span> <strong>Goal:</strong> Work through the materials so you are prepared to engage at your workshop. Then, complete the submission form at the bottom of this page in order to get the zoom link for your scheduled workshop!
<br>
<br>

<!-- SET UP -->
<div class="expander expander-be">
  <header>
    <h2>Set Up</h2>
    <div>
      <div class="setup be-tag tag to-do-tag">To Do</div>
      <button class="expander-btn">
        <img
          src="../../assets/icons/arrow.svg"
          alt="expander arrow icon" />
      </button>
    </div>
  </header>
  <div class="hide">
    <p><a href="https://repl.it/~" target="blank">repl.it</a> provides an online platform that allows us to write code and see the results almost immediately - all inside of one browser tab! There are many other similar (and awesome) tools available; we feel this is the best choice for the Try Coding workshops.</p>
    <p><span role="img" aria-label="movie">🎬</span> Please watch this short video for an introduction on how to navigate repl.it:</p>

    <iframe width="100%" height="550px" frameborder="0" scrolling="no" src="https://screencast-o-matic.com/embed?sc=cYeDbCxkcH&v=6&ff=1&title=0&controls=1" allowfullscreen="true"></iframe>

    <p><span role="img" aria-label="check mark">✅</span> Since we'll be using repl.it during the workshop, please create a free account with them at this time. Then, create a repl as shown in the video. You don't need to type any code in it just yet.</p>
    <button class="btn-dark mark-complete-btn">Mark Complete</button>
  </div>
</div>

<!-- Part 1: Data Types, puts/print -->
<div class="expander expander-be">
  <header>
    <h2>Learn: Part 1</h2>
    <div>
      <div class="part-one be-tag tag to-do-tag">To Do</div>
      <button class="expander-btn">
        <img
          src="../../assets/icons/arrow.svg"
          alt="expander arrow icon" />
      </button>
    </div>
  </header>
  <div class="hide">
    <p>Ruby is a Back-End programming language. It was written with a focus on simplicity and productivity, so is a great language for beginners!</p>
    <p>Programming languages need a way to classify the various types of data they work with. Ruby works with the 3 data types defined below:</p>

    <section class="data-type-cards">
      <div>
        <h3>String</h3>
        <p>A String is a series of characters (alpha, numeric, or symbol) between quotation marks.</p>
        <pre>"Hello, World!"
"12345"</pre>
      </div>

      <div>
        <h3>Integer</h3>
        <p>An Integer is a number without decimals. Basic math operations can be performed on them.</p>
        <pre>137
3 + 7</pre>
      </div>

      <div>
        <h3>Boolean</h3>
        <p>A Boolean refers to a value that is either true or false. You can think of it as an on/off switch.</p>
        <pre>true
false</pre>
      </div>
    </section>
    <br>

    <p>Ruby provides a command that allows us to print out the data we are working with the the console. It's a tool for learning and troubleshooting, but isn't usually included in the final code of an app. Below is a screenshot of code after being run, in a repl.it. <a href="https://repl.it/@turingschool/puts-example#main.rb" target="blank">Click here to see the code and run it yourself</a>, if you'd like!</p>

    <img
      src="./assets/p1-replit.png"
      alt="Screenshot of code in previous example, inside the replit platform" />

    <p><em><span role="img" aria-label="finger pointing to text">👉🏽</span> This may not feel very exciting now, but it will be a useful tool as we move forward!</em></p>
    <br>

    <h3>You Try</h3>
    <p>In your repl.it, "puts" several values out to the console. Run the file and observe the output.</p>
    <p>Now, instead of using the <code class="try-it-code">puts</code> command, use <code class="try-it-code">print</code>. Observe the difference in the output.</p>
    <p><em><span role="img" aria-label="raised hand">🖐🏼</span> If you need help or want to feel confident in your work, <a href="https://repl.it/@turingschool/you-try-1-solution" target="blank">here is a working solution</a>.</em></p>
    <div class="help-container">
      <button class="help-click">FAQ: Is puts or print preferred?</button>
      <div class="help-toggle">
        <p>Since puts and print are both for learning and troubleshooting, you should use the one <strong>you</strong> prefer! You may choose one over the other in different situations. There is no "best practice", but it's good to know that both exist.</p>
      </div>
    </div>

    <button class="btn-dark mark-complete-btn">Mark Complete</button>
  </div>
</div>

<!-- Part 2: Variables, Interpolation -->
<div class="expander expander-be">
  <header>
    <h2>Learn: Part 2</h2>
    <div>
      <div class="part-two be-tag tag to-do-tag">To Do</div>
      <button class="expander-btn">
        <img
          src="../../assets/icons/arrow.svg"
          alt="expander arrow icon" />
      </button>
    </div>
  </header>
  <div class="hide">
    <p>We can use variables to store and reference information within a Ruby program. We can think about it as a storage bin in the garage - the contents inside of the bin are what we care about storing, and the label on the outside is how we can quickly identify it.</p>
    <p>The syntax for declaring variables and assigning a value to them is as follows:</p>
    <pre class="expander-code">first_name = "Maya"
age = 34
is_signed_in = true</pre>
    <p>After declaring a variable, we can reference the variable name as many time as we want/need to:</p>
    <pre class="expander-code">first_name = "Maya"
puts first_name
puts first_name
puts first_name</pre>
    <p><em>Note that the variable <code class="try-it-code">first_name</code> uses an underscore character to separate the two words. This is called <a href="https://en.wikipedia.org/wiki/Snake_case" target="blank">snake case <span role="img" aria-label="snake">🐍</span></a> and is a Ruby convention.</em></p>
    <br>
    <p>Many times, information within a program will change, so we will need to re-assign the value of a variable. The screenshot below was taken after <a href="https://repl.it/@turingschool/reassign-variable#main.rb" target="blank">this repl.it file was run</a>.</p>

    <img
      src="./assets/p2-replit.png"
      alt="Screenshot of code in previous example, inside the replit platform" />
    <br>
    <br>
    <br>

    <h3>String Interpolation</h3>
    <p>String Interpolation allows us to create more dynamic and customized information for our users. Instead of telling you exactly what it does and how it works, we're only providing the syntax. You may be able to predict what the code will do just by reading through it. In the next activity, you will use that syntax and be able to see the result for yourself!</p>
    <pre class="expander-code">first_name = "Maya"
age = 34

puts "Hello! My name is #{first_name} and I am #{age} years old."</pre>


    <h3>You Try</h3>
    <p>In the same repl file you were working in earlier, declare two variables.</p>
    <p>Then, <code class="try-it-code">puts</code> or <code class="try-it-code">print</code> a sentence that uses those two variables with String Interpolation!</p>
    <p><em><span role="img" aria-label="raised hand">🖐🏾</span> If you need help or want to feel confident in your work, <a href="https://repl.it/@turingschool/you-try-2-solution" target="blank">here is a working solution</a>.</em></p>
    <div class="help-container">
      <button class="help-click">Help! It's not working.</button>
      <div class="help-toggle">
        <p>If the desired result is not printing to the console, or, if you are seeing an error message, here are some go-to strategies to problem solve:</p>
        <p>If repl is working very slowly, try to refresh the page. It works best in the Chrome browser.</p>
        <p>Make sure you are using double quotes.</p>
        <p>Check the spelling and capitalization of your variables. The variable names must be exact matches!</p>
      </div>
    </div>

    <button class="btn-dark mark-complete-btn">Mark Complete</button>
  </div>
</div>

<!-- Submission Form -->
<div class="expander expander-be">
  <header>
    <h2>Submission</h2>
    <div>
      <div class="submission be-tag tag to-do-tag">To Do</div>
      <button class="expander-btn">
        <img
          src="../../assets/icons/arrow.svg"
          alt="expander arrow icon" />
      </button>
    </div>
  </header>
  <div class="hide">
    <p>You did it <span role="img" aria-label="celebration cone">🎉</span> We hope you had some fun learning about the building blocks of Ruby - this is a great foundation!</p>
    <p>Please complete the form below so we have a sense of where you are with the material so far and can customize the workshop to your needs.</p>
    <iframe src="https://docs.google.com/forms/d/e/1FAIpQLScyKttYAR6OiHcCsarBXbFRgZUqMI4ffZal0atN8ArByH68yw/viewform?embedded=true" width="100%" height="1076" frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe>
    <button class="btn-dark mark-complete-btn">Mark Complete</button>
  </div>
</div>
