Download Link: https://assignmentchef.com/product/solved-cse3055-homework-1
<br>
<span class="kksr-muted">Rate this product</span>




<ol>

 <li>1)  Consider the following information about a university database:

  <ul>

   <li>Professors have an SSN, a name (composed of firstName and lastName), a birthdate, an age (derivedfrom birthdate), a rank, and a research specialty. A professor can have more than one specialty.</li>

   <li>Projects have a project number, a sponsor name (e.g., NSF), a starting date, an ending date, and a budget.</li>

   <li>Graduate students have an SSN, a name, an age, and a degree program (e.g., M.S. or Ph.D.).</li>

   <li>Each project is managed by one professor (known as the project’s principal investigator).</li>

   <li>Each project is worked on by one or more professors (known as the project’s co-investigators).</li>

   <li>Professors can manage and/or work on multiple projects.</li>

   <li>Each project is worked on by one or more graduate students (known as the project’s research assistants).</li>

   <li>When graduate students work on a project, a professor must supervise their work on the project. Graduate students can work on multiple projects, in which case they will have a (potentially different) supervisor for each one.</li>

   <li>Departments have a department number, a department name, and a main office.</li>

   <li>Departments have a professor (known as the chairman) who runs the department.</li>

   <li>Professors work in one or more departments and for each department that they work in, a time percentage is associated with their job.</li>

   <li>Graduate students have one major department in which they are working on their degree.</li>

   <li>Each graduate student has another, more senior graduate student (known as a student advisor) whoadvises him or her on what courses to take.Design and draw an ER diagram that captures the information about the university. Be sure to indicate any key and participation constraints.Please indicate any assumptions that you have made.</li>

  </ul></li>

 <li>2)  Design a database to keep track of information for an art museum. Assume that the following requirements were collected:

  <ul>

   <li>The museum has a collection of ART_OBJECTs. Each ART_OBJECT has a unique ArtObjectID, an Artist (if known), a Year (when it was created, if known), a Title, and a Description. The art objects are categorized in several ways, as discussed below.</li>

   <li>ART_OBJECTs are categorized based on their type. There are two main types: PAINTING, and SCULPTURE, plus another type called OTHER to accommodate objects that do not fall into one of the two main types.</li>

  </ul></li>

</ol>




<ul>

 <li>A PAINTING has a PaintType (oil, watercolor, etc.), material on which it is DrawnOn (paper, canvas, wood, etc.), and Style (modern, abstract, etc.).</li>

 <li>A SCULPTURE has a Material from which it was created (wood, stone, etc.), Height, Weight, and Style. A SCULPTURE might be made up of many Materials.</li>

 <li>An art object in the OTHER category has a Type (print, photo, etc.) and Style.</li>

 <li>ART_OBJECTs are also categorized as either PERMANENT_COLLECTION (objects that are owned by themuseum) or BORROWED_COLLECTION.</li>

 <li>Information captured about objects in the PERMANENT_COLLECTION includes DateAcquired, Status (on display, on loan, or stored), and Cost.</li>

 <li>Information captured about BORROWED_COLLECTION objects includes the collection from which it was borrowed, DateBorrowed, and DateReturned.</li>

 <li>Information describing the country or culture of Origin (Italian, Egyptian, American, Indian, and so forth) and Epoch (Renaissance, Modern, Ancient, and so forth) is captured for each ART_OBJECT.</li>

 <li>The museum keeps track of ARTIST information, if known: Name, DateBorn (if known), DateDied (if not living), CountryOfOrigin, Epoch, MainStyle, and Description. The Name is assumed to be unique.</li>

 <li>Different EXHIBITIONs occur, each having a Name (unique), Place, StartDate, and EndDate. EXHIBITIONs are related to all the art objects that were on display during the exhibition. Place is composed of Country, State, and City.</li>

 <li>Information is kept on other COLLECTIONs (related to BORROWED_COLLECTION) with which the museum interacts, including Name (unique), Type (museum, personal, etc.), Description, Address, Phone, and current ContactPerson.Draw an Enhanced Entity Relationship (EER) schema diagram for this application. Discuss any assumptions you make, and that justify your EER design choices.</li>

</ul>

3) Map the following enhanced entity-relationship diagram into a relational database schema. Please state any assumptions that you have made. Do not forget to use arrows for foreign key – primary key references.




4) Map the following entity-relationship diagram into a relational database schema. Please state any assumptions that you have made. Do not forget to use arrows for foreign key – primary key references.