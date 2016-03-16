# Tyler Fink
## Software/Web Developer

> [tfink419@gmail.com](tfink419@gmail.com)  
> (561) 319-6751

- - -

### Objective
Utilize my math and Computer Science knowledge to tackle challenges and find solutions to problems while furthering my own knowledge and ability.

- - -

### Education
#### University of Florida, Gainesville, FL
Attended: *August 2010* – *April 2015*
*	Semester Classes
	*	Computer Architecture/Assembly Programming (MIPS)
	*	Data Structures (C++)
	*	Python
	*	Android
	*	SQL/NoSQL
	*	Object Oriented Programming, Design Patterns
	*	HTML5/CSS/PHP


#### Suncoast High School, Riviera Beach, FL
Dates attended: *2006* – *2010*
Graduation Date: May 2010
*	Taken Calculus 1-3, Matrix Theory, and Differential Equations
*	4 years of Computer Science classes
	*	2 years Java, 2 years C/C++
* 3 years on Programming Team: 1st place 2 years, 2nd place 1 year

### Work Experience

#### EdutainmentLIVE! (ITPro.tv)
> **Programmer**
> *May 2015* - *Now*

##### Responsibilities
* Largely working at own discretion to write new features for api and website or other services.
* Interact with coworkers in other departments to determine priorities/details of new features.

##### Projects
* **Sails Main API** _(node-based api similar to Rails)_
  * Mainly mongo-based database
  * Built custom redis 'adapter' for quickly retrieving information for specific courses/episode/user combinations.
  * Expanded api into many new avenues and built upon main api
 
* **Angular Frontend**
  * Main website features are in Angular
  * Created:
    * Multiple download manager in Javascript (Mediocre cross-platform compatibility)
    * Subtitles below video with searching/tracking
      * Parses srt/vtt file
      * Can click parts to goto time in video
    * Open private test session on external website via API interaction
      * User presses <kbd>Start Test</kbd> and a new page opens up

* **"Producer" Website**
  * Backdoor site for employees only
  * Added many custom API fetch/update/create pages
  * Built site metrics page to graph/table various metrics on our site using Chart.js

* **Ruby Pdf Creator**
  * Simple 'certificate' creator
  * First time using Ruby
  * Built in short timeframe, worked alone
  * **Process:**
    1. Receives http post request from main api with information about certificate
    2. Responds immediately with a generated filename and 1 hour expiration time
    3. Queues task
    4. Receives get requests for filename periodically from api, responds with expiration/not-finished or a generated AWS url with expiration.
* **Productron**
  * Standalone Desktop App running on Github's Electron
  * Used by switchers to handle starting/stopping of recording/streaming
    * Interacts with main api and individual Epiphan Pearl devices
  * Takes information from each session/recording and stores it along with the file name/location
    * Automatically rename and move new recordings from an incoming folder to name/location
  * Search past sessions/recordings
  * View and split outline of hosts when recordings break off into multiple episodes (for searching)
  
### Tonerite Inc.
> **Web Developer**  
> *September 2013* – *May 2014*  

#### Responsibilities
* Rebuilt website using a newer CMS and transferred data from the old website to the new one.
* Fixed bugs and graphical glitches from the old website while the new website was under construction.
