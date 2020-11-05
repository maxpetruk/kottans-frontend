# Front-End Course from gorgeous [Kottans](https://kottans.org/)

## The repository is dedicated to taking part in [Kottans frontend course](https://github.com/kottans/frontend)

### What I have done so far :rocket:

 1. **General**
    - [x] [Git Basics](#0-git-basics)
    - [x] [Linux CLI and Networking](#1-linux-cli-and-networking)
    - [x] [VCS (hello gitty), GitHub and Collaboration](#2-vcs-hello-gitty-github-and-collaboration)
  
 2. **Front-End Basics**

    - [x] [Intro to HTML & CSS](#3-intro-to-html-and-css)
    - [ ] [Responsive Web Design](#5-responsive-web-design)
    - [ ] [HTML & CSS Practice](#6-html-css-practice)
    - [ ] [JavaScript Basics](#7-javascript-basics)
    - [ ] [Document Object Model - practice](#8-document-object-model-practice)
  
 3. **Advanced Topics**

    - [ ] [Building a Tiny JS World (pre-OOP) - practice](#9-building-a-tiny-js-world-pre-oop-practice)
    - [ ] [Object oriented JS - practice](#10-object-oriented-js-practice)
    - [ ] [OOP exercise - practice](#11-oop-exercise-practice)
    - [ ] [Offline Web Applications](#12-offline-web-applications)
    - [ ] [Memory pair game — real project!](#13-memory-pair-game-real-project)
    - [ ] [Website Performance Optimization](#14-website-performance-optimization)
    - [ ] [Friends App - real project!](#15-friends-app-real-project)


    ## General

### 0. Git Basics
***
[Version Control with Git](https://www.udacity.com/course/version-control-with-git--ud123)
    
  <details><summary>Screenshot</summary>
  <p>

  ![Screenshot-image-link](./task_git_basics/version_control_with_git.png)

  </p>
  </details>
    
  [Learn Git Branching](https://learngitbranching.js.org/)

  <details><summary>Screenshots</summary>
  <p>

  ![Screenshot-image-link](./task_git_basics/learngitbranching_main.png)
  ![Screenshot-image-link](./task_git_basics/learngitbranching_remote.png)

  </p>
  </details>

  I already took the courses in the past. Still, it was worth refreshing my knowledge of Git and Github.
### 1. Linux CLI and Networking

***

   #### 1.1 Course [Linux Survival (4 modules)](https://linuxsurvival.com/linux-tutorial-introduction/)


  <details><summary>Screenshots</summary>
  <p>

  ![Screenshot-image-link](./task_linux_cli/2020-10-18_19-35.png)
  ![Screenshot-image-link](./task_linux_cli/2020-10-18_23-43.png)
  ![Screenshot-image-link](./task_linux_cli/2020-10-19_23-10.png)
  ![Screenshot-image-link](./task_linux_cli/2020-10-20_00-10.png)

  </p>
  </details>


- **What was new:**

  - the "**more**" command which is used to view the contents of a file in your terminal.
  - the "**pwd**" command. I realized that once I used the command a few times but with the course of time it just slipped my mind.
  - *mv cats/tigers cats/siberians* - renaming the folder by specifying the pathname relative to the parent folder
  - *mv ../cats/tigers ../cats/siberians* - renaming the folder when you are in a neighboring folder 
  - *ls -l* - the command shows **more** info about files in a folder
  - ***chmod g+w chimps*** - the command changes the security permissions on files. In this case, it gives "write" permission to the group for file "chimps"
  - **wildcards (such as **ing*) are used to match a certain number of characters**
  - chmod g+w * - gives "write" permission to the group on all files in the current folder
  - **groups** - shows group memberships in the current folder
  - *cp ~/jokes /tmp* - copies a file called "jokes" from my home folder to the "/tmp" folder. The command is shorter than *cp /home/keeper/jokes /tmp*
  - **man** command
  - **finger** command - shows a user info. To use the command you need to install *finger* (sudo apt-get install finger)
  - **find ** command (e.g. find . -name "joke*") = to find files
  - **cat** command (e.g. cat joke-1 joke-2). The jokes are corny though :)
  - cat jabber wocky > poem - it puts the contents of the two files into a file called poem
  - lpr -P zephyr corny - where zephyr is the printer, corny is the file to print, lpr -P is the command to print
  - lprm -P zephyr 737 - removes a print job 737
  - cp -r ~jester/jokes ~  = cp -r lets you copy folders
  - df = shows how much disk space you have left on your system
  - df ~ = shows the statistics for the disk where your home folder resides
  - rm -r stocks = removes everything in "stocks" folder
  - ps aux = shows a detailed list of all processes
  - "|" - (to pipe) it sends the output of a command as the input to another command
  - cat joke-1 joke-2 | grep rabbit
  - ps aux | grep rogue = the command sequence that lists only those processes which contain the word "rogue"
  - kill PID = kills a process where PID is the id of the process
  - kill -9 PID = kills a process at once
- **What surprised me:**

  - I learned about squirrel monkeys. They look extremely cute :)

- **What I intend to use in the future**
  - I would say I am going to use most of the commands but for the commands related to printing



#### 1.2 Article [HTTP: The Protocol Every Web Developer Must Know - Part 1](https://code.tutsplus.com/tutorials/http-the-protocol-every-web-developer-must-know-part-1--net-31177)

- **What was new:**

  - every request is completely independent, it's stateless

  - additional request verbs which are less common (e.g. HEAD, TRACE, OPTIONS)
  - such utilities as **curl**, **tcpbump** and **tsshark** are used for monitoring HTTP traffic.

- **What surprised me:**

  - Finally I learned what URL stands for :), which is "Uniform Resource Locators"

- **What I intend to use in the future:**

  - To my mind, as a developer, I have to know how to work with what Developer Tools show, I mean the output of the headers and status codes.

- **General Overview:**

  There was so much new stuff in the article to get my head around so I feel a bit overwhelmed now. It's important to know the theory but I have a feeling like I need to see how the knowledge of the protocol and its codes is applied on a practical level. 



#### 1.3 Article [HTTP: The Protocol Every Web Developer Must Know - Part 2](https://code.tutsplus.com/tutorials/http-the-protocol-every-web-developer-must-know-part-2--net-31155)

- **What was new:**

  - such things as *persistent connections*, *parallel connections,* 

  - HTTP supports Basic Authentication and Digest Authentication which is more secure.
  - Due its simplicity Basic Authentication is more common than Digest A. 
  - I'd say - quite many things were new to me

- **What I intend to use in the future:**

  - I figure a lot of it. 

- **General Overview:**

  I feel like I need to put it into practice to dive deeply and therefore to get the hang around the topic.


### 2. VCS (hello gitty), GitHub and Collaboration

#### 2.1 Course [GitHub & Collaboration](https://classroom.udacity.com/courses/ud456)

  <details><summary>Screenshots</summary>
  <p>

  ![Screenshot-image-link](./task_git_collaboration/github-and-collaboration.png)

  </p>
  </details>

- **What was new:**

  - I knew about "**git log**" command, but now I have learned about its flags (-p, --stat); 
  - **git shortlog -s -n** = list authors of a git repository including commit count

- **What surprised me:**

  - I find the advice how to write commit messages and when it's better to commit surprisingly reasonable

- **What I intend to use in the future:**

  - pretty much everything mentioned in the course

  

#### 2.2 Course [learngitbranching.js.org](https://learngitbranching.js.org/)

I have already finished the task in [Git and GitHub](https://github.com/nadsatt/kottans-frontend/blob/main/README.md#1-git-and-github) section.

  <details><summary>Screenshots</summary>
  <p>

  ![Screenshot-image-link](./task_git_collaboration/learngitbranching_main.png)
  ![Screenshot-image-link](./task_git_collaboration/learngitbranching_remote.png)

  </p>
  </details>

### 3. Intro to HTML and CSS

  <details><summary>Animated Screenshot</summary>
  <p>

  ![Screenshot-image-link](./task_html_css_intro/HTML_and_CSS.gif)

  </p>
  </details>

- **What was new:**

  - `<video>`  and`<audio>` tags and their attribute **control**
  - `scope` attribute, which can take one of two values: `row` (for rows) and `col` (for columns)
  - `<td colspan>`  attribute
  - HTML `<td rowspan>` attribute
  - the `<tbody>` tag is used to group the body content in an HTML table
  - The `<thead>` tag is used to group header content in an HTML table.
  - The `<tfoot>` tag is used to group footer content in an HTML table.
  - The `<datalist>` tag specifies a list of pre-defined options for an `<input>` element.
  - `<input required>` The **required** attribute is a boolean attribute. When present, it specifies that an input field must be filled out before submitting the form.
  - The **max** and **min** attributes specify the maximum and the minimum values for an `<input>` element.
  - The **`minlength`** **`maxlength`** attribute define the minimum the maximum number of characters (as UTF-16 code units) the user can enter into `<input>` or `<textarea>`
  - The **`pattern`** attribute specifies a [regular expression](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions) the form control's value should match.
  - The `<figure>` tag specifies self-contained content, like illustrations, diagrams, photos, code listings, etc.
  - The `<figcaption>` [tag](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/figcaption) defines a caption for a  `<aside>`  element.
  - The **HTML `<aside>` element** represents a portion of a document whose content is only indirectly related to the document's main content. Asides are frequently presented as sidebars or call-out boxes.
  
- **What surprised me:**

  - I was surprised to learn that I could use regular expressions in HTML code

- **What I intend to use in the future:**

  - pretty much everything mentioned in the courses
  
- **General Overview:**

  I refreshed my knowledge of tables. Generally, the courses are designed for total newbies, and therefore, it was easy for me to pass the course. 

#### 3.3 [Learn CSS(Eng)](https://www.codecademy.com/learn/learn-css)

- **What was new:**

  - `<video>`  

  - *HSL* - hue-saturation-lightness color scheme

  - `hsla` property - changes the *opacity*, or the amount of transparency, of some colors so that some or all of the bottom elements are visible through a covering element.

  - `word-spacing` - increase the spacing between words in a body of text

  - `letter-spacing`- adjusts the spacing between letters  (*tracking*).

  - `@font-face` - is a to import fonts directly into stylesheets

  - `grid-template`can replace `grid-template-rows` and `grid-template-columns`

  - `grid-template-columns: repeat(3, 100px)`is equal to `grid-template-columns: 100px 100px 100px;`

  - The **`minmax()`** [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) [function](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Functionals) defines a size range greater than or equal to min and less than or equal to max. It is used with [CSS Grids](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout).

  - The **`gap`** [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) property sets the gaps ([gutters](https://developer.mozilla.org/en-US/docs/Glossary/gutters)) between rows and columns. It is a [shorthand](https://developer.mozilla.org/en-US/docs/Web/CSS/Shorthand_properties) for [`row-gap`](https://developer.mozilla.org/en-US/docs/Web/CSS/row-gap) and [`column-gap`](https://developer.mozilla.org/en-US/docs/Web/CSS/column-gap).

  - `grid-row` is used as shorthand for `grid-row-start` and `grid-row-end`

  - `grid-column: 4 / span 2;` using `span` keyword

  - `grid-area: 9row / 1column / 13row / 7column` 

  - `grid-auto-rows` and `grid-auto-columns` properties

  - `grid-auto-flow: dense` property

  - `transition-property: background-color;` and `transition-duration: 2s;`

  - `transition-delay: 250ms;`

  - `transition-timing-function: ease-out;`

  - transition-property: color; 

    transition-duration: 1.5s; 

    transition-timing-function: linear; 

    transition-delay: 0.5s;      corresponds to `transition: color 1.5s linear 0.5s;`

  - combinations of transitions by adding commas;

  - using `all` to affect all properties;

- **What surprised me:**

  - nothing much. 

- **What I intend to use in the future:**

  - pretty much everything mentioned in the course

- **General Overview:**

  I refreshed my knowledge of `grid` and transitions. The course represents basic CSS skills so it was easy to pass it.