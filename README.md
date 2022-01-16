# CodeAcademy-FormAStory-HTMLForms
HTML Forms project
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css?family=Open+Sans" rel="stylesheet">
    <title>Form a Story</title>
  </head>
  <body>
    <section id="top">
      <img src="https://content.codecademy.com/courses/learn-html-forms/formAStoryLogo.svg" alt="Form A Story Logo">
    </section>

    <section id="main">
      <h1>Complete the Form -<br> Complete the Story!</h1>
      <hr>
      <!--Add your form below:-->
      <form action="story.html" method="GET">
        <label for="animal-1">Animal:</label>
        <input type="text" id="animal-1" name="animal-1" required>
        <br>
        <label forn="animal-2">Another Animal:</label>
        <input type="text" id="animal-2" name="animal-2" required>
        <br>
        <label forn="animal-3">More Animal:</label>
        <input type="text" id="animal-3" name="animal-3" required>
        <br>
        <label for="adj-1">Adjective (past tense):</label>
        <input type="text" id="adj-1" name="adj-1" required>
        <br>
        <label for="verb-1">Verb (ends in -ing):</label>
        <input type="text" id="verb-1" name="verb-1" required>
        <br>
        <label for="num-1">Number:</label>
        <input type='number' id="num-1" name="num-1" required>
        <br>
        <span>Yes or No:
          <input id="yes" type="radio" name="answer" value="yes" required>
          <label for="yes">Yes</label> 
          <input id="no" type="radio" name="answer" value="no" required>
          <label for="no">No</label> 
        </span>
        <br>
        <label for='speed'>Relative speed (ends in -er):</label>
        <select id='speed' name="speed">
          <option value="slowest">Slowest</option>
          <option value="slow">Slow</option>
          <option value="fast">Fast</option>
          <option value="fastest">Fastest</option>
        </select>
        <br>
        <label for="quote">Motivational Quote:</label>
        <input id="quote" name="quote" type="text" required list="quote-choices">
        <datalist id="quote-choices">
          <option value="It's not the fastest but the most consistent"></option>
          <option value="You can always learn something from others"></option>
          <option value="Follow your passion"></option>
        </datalist>
        <br>
        <label for="message">Meaningful Message:</label>
        <textarea id="message" name="message" required row='8' cols='40'></textarea>
        <br>
        <input type="submit" value="Form My Story!">
      </form>
    </section>
  </body>
</html>
