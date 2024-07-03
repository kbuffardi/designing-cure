[comment]: # (Compile this presentation with the command below)
[comment]: # (mdslides index.md && mv index/index.html .)
[comment]: # (THEME = night)
[comment]: # (CODE_THEME = base16/zenburn)
[comment]: # (The list of themes is at https://revealjs.com/themes/)
[comment]: # (The list of code themes is at https://highlightjs.org/)
[comment]: # (Pass optional settings to reveal.js:)
[comment]: # (controls: true)
[comment]: # (keyboard: true)
[comment]: # (progress: true)
[comment]: # (width: "1024")
[comment]: # (markdown: { smartypants: true })
[comment]: # (hash: false)
[comment]: # (respondToHashChanges: false)
[comment]: # (Other settings are documented at https://revealjs.com/config/)

### Designing a CURE for CS1

----------

Kevin Buffardi, JoAna Brooks, David Alexander
[California State University, Chico](https://csuchico.edu/)

<img src="qr-code.png" alt="QR code" width="30%">
</img>

<sub>[LearnByFailure.com](https://learnbyfailure.com/research/)</sub>

[comment]: # (!!!)
        
### What is a CURE?

* <u>**C**</u>ourse-based <u>**U**</u>ndergraduate <u>**R**</u>esearch <u>**E**</u>xperience
    * Using **scientific practices**, 
    * Addressing **novel** scientific questions, 
    * Impact **beyond the classroom**, 
    * **Collaboration**, and
    * **Iteration**

[comment]: # (||| data-auto-animate)

### What is a CURE?

* Originates in life sciences
    * At time of our study, few [Computer Science classes](https://serc.carleton.edu/curenet/collection.html?q1=sercvocabs__513%3A8)
        * Serving environmental science, genomics, etc.
        * In Upper-division courses

[comment]: # (!!!)
        
### Why CURE?

* Undergraduate research is a high-impact practice
    * Extracurricular research is unscalable and inequitable
    * Integrating into a course involves **everyone**
* Reveal synergy between research and entrepreneurial mindset

[comment]: # (!!!)

### CURE in CS1

* Primary challenge: Involve **CS1** students in CURE
    * Participate in **research**
    * On a **Human-Computer Interaction** (HCI) project **within the major**
    
[comment]: # (!!!)

### Color Vision Project

* Digital visualizations often encode data via color
* Poor color combinations can be difficult to differentiate
    * Color blindness further complicates perception

[comment]: # (||| data-auto-animate)

### Color Vision Project

#### Example [via /r/dataisbeautiful](https://www.reddit.com/r/dataisbeautiful/comments/16jmv4o/car_sizes_from_1970s_to_present_oc/)

<img src="car-colors.png" alt="Chart with 9 car manufacturers each color-coded" width="60%">
</img>

[comment]: # (||| data-auto-animate)

### Color Vision Project

#### Deuteranomaly simulation [via Pilestone simulator](https://pilestone.com/pages/color-blindness-simulator-1)

<img src="car-deuteranomaly.png" alt="Previous chart with simulated perception, showing colors that are difficult to distinguish" width="60%">
</img>

[comment]: # (||| data-auto-animate)

### Color Vision Project

#### Protanomaly simulation [via Pilestone simulator](https://pilestone.com/pages/color-blindness-simulator-1)

<img src="car-protanomaly.png" alt="Another simulated perception, showing more colors that are difficult to distinguish" width="60%">
</img>

[comment]: # (||| data-auto-animate)

### Color Vision Project

#### Group Roles

* <u>**Analyzer**</u> <small>provided a palette of colors, evaluate to what degree its color combinations are problematic for people with a particular form of color blindness;</small>
* <u>**Optimizer**</u> <small>provided a palette of colors, adjust the colors when necessary to optimize the percentage of people who will be able to easily detect the color differences;</small>
* <u>**Generator**</u> <small>provided a number of distinct colors needed (2 or more), create a palette of colors that avoid or minimize problematic color combinations; and</small>
* <u>**Designer**</u> <small>provided a base color, create a list of five more colors that do not have problematic color combinations.</small>

[comment]: # (!!! data-auto-animate)

### Color Vision Project

#### Iterations

* **Minimum Viable Product** (MVP): <p>Most value to the customer for the least effort</p>
* **Project deliverables**: <p>Three cumulative iterations of MVPs</p>
* **Adaptation**: <p>Reflect how next MVP could improve</p>

[comment]: # (|||)

#### Iteration 1 Requirements

<table>
  <tr>
    <th style="nowrap"><small><b>MVP #1</b></small></th>
    <th><small>Useful Progress</small></th>
    <th><small>Variables</small></th>
    <th><small>Standard IO</small></th>
    <th><small>Decisions</small></th>
    <th><small>Iteration</small></th>
  </tr>
  <tr>
    <td> &nbsp; </td>
    <td><small>Initial MVP</small></td>
    <td><small>Multiple + array/vector</small></td>
    <td><small>Console input & output</small></td>
    <td><small>3+ different controls</small></td>
    <td><small>1+ loop</small></td>
  </tr>
</table>

[comment]: # (|||)

#### Iteration 2 Requirements

<table>
  <tr>
    <th><small><b>MVP #2</b></small></th>
    <th><small>Useful Progress</small></th>
    <th><small>Parameters</small></th>
    <th><small>File IO</small></th>
    <th><small>Style</small></th>
  </tr>
  <tr>
    <td><small>MVP #1 <i>and</i></small></td>
    <td><small>Adapted MVP</small></td>
    <td><small>Pass-by-reference &amp; Pass-by-value</small></td>
    <td><small>fstream input/output</small></td>
    <td><small>Adopt style guide</small></td>
  </tr>
</table>

[comment]: # (|||)

#### Iteration 3 Requirements

<table>
  <tr>
    <th><small><b>MVP #3</b></small></th>
    <th><small>Useful Progress</small></th>
    <th><small>Classes</small></th>
  </tr>
  <tr>
    <td><small>MVP #2 <i>and</i></small></td>
    <td><small>Final MVP</small></td>
    <td><small>1+ Class</small></td>
  </tr>
</table>

[comment]: # (!!!)

### Entrepreneurial Mindset

* [CURE-E](https://www.csuchico.edu/curee/) project
* Integrate [Entrepreneurial Mindset](https://nfte.com/):
    * Managing risk
    * Taking initiative
    * Persisting
    * Learning from failure
    * Collaboration
    * Seeking opportunities to improve people’s lives

[comment]: # (||| data-auto-animate)

### Entrepreneurial Mindset

* [Agile](https://agilemanifesto.org/) and [Lean](http://www.poppendieck.com/) software development:
    * Managing risk: **Identifying [MVP](https://www.syncdev.com/minimum-viable-product)**
    * Taking initiative: **Novel solution to role**
    * Persisting: **Competency-based grading for cumulative requirements**
    * Learning from failure: **Adaptation in each iteration**
    * Collaboration: **Share insights within groups**
    * Seeking opportunities to improve people’s lives: **Innovate accessibility**

[comment]: # (!!!)

### Formative Lessons Learned

1. Research requires familiarity with some **domain knowledge** and scaffolding enough expertise does not scale well when the domain is too broad
2. CUREs that do not have funding to provide **incentives for stakeholder participation** will suffer attrition in seeking valuable feedback
3. Students are not experienced researchers and require more structured guidance on how to **critically evaluate a product/result**

[comment]: # (!!!)

### Outcomes

| Theme || *a* | Max | Mean | s.d. |
| ----- || ----- | ----- | ----- | ----- |
| Self- efficacy || *0.789* | 5 | 3.615 | 0.559 |
| Identity || *0.884* | 5 | 3.809 | 0.728 |
| Community || *0.856* | 6 | 4.258 | 0.941 |
| Values || *0.891* | 6 | 4.742 | 0.992 |
| How often || 0.678 | 4 | 3.619 | 0.424 |
| How apparent || *0.940* | 6 | 4.739 | 0.733 |
| Entrep. Mindset || *0.766* | 6 | 4.971 | 0.816 |

[comment]: # (||| data-auto-animate)

### Outcomes

<img src="CourseActivities.png" alt="Histogram of frequency of CURE activities" width="80%">
</img>

[comment]: # (!!!)

### Post-Hoc Reflections

* ChatGPT was made public in the midst of implementation
* Initially:
  * Suggest using `{red, green, blue}` as a palette
  * Acknowledged problems, but no solutions offered
* After a semester:
  * Uses common student solutions to evaluate palettes
  * Contrast used as a primary indicator of color combination accessibility

[comment]: # (!!!)

#### Designing a CURE for CS1

----------

<small>Presented at [ITiCSE'24](https://iticse.acm.org/2024/) in Milan, Italy. The [paper is available via ACM](#).</small>
<small>To cite this paper, use the following reference in your bibliography:</small>
> <small style="text-align: left; width: 100%;">Kevin Buffardi, JoAna Brooks, and David Alexander. 2024. Designing a CURE for CS1. In Proceedings of the 2024 ACM Conference on Innovation and Technology in Computer Science Education (ITiCSE '24). Association for Computing Machinery, Milan, Italy.</small>

<small>Or import the following *BibTeX* reference:</small> 
> <small style="text-align: left; width: 100%;"> @article{buffardi2024cure, author = {Buffardi, Kevin and Brooks, JoAna and Alexander, David}, title = {Designing a CURE for CS1}, year = {2024}, issue_date = {July 2024}, publisher = {Association for Computing Machinery}, address = {Milan, Italy}} 
</small>

[comment]: # (!!!)

#### Designing a CURE for CS1 

----------

<small>This presentation is accessible at [learnbyfailure.com/designing-cure](https://learnbyfailure.com/designing-cure) and its source is available on [GitHub](https://github.com/kbuffardi/designing-cure/).</small>

<img src="qr-code.png" alt="QR code" width="30%">
</img>

<small>[Back to LearnByFailure](https://learnbyfailure.com/research/)
</small>
