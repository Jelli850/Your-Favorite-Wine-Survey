# Your-Favorite-Wine-Survey
<DOCTYPE html>
  <html lang="en">
  <head>
    <link rel="stylesheet" href="styles.css">
    <meta charset="UTF-8">
    <title>What is your favorite wine?</title>
    </head>
    <body>
      <h1 id="title">What is your favorite wine</h1>
      <main>
      <p id="description">This is a form to collect information on wine. Do you like red? White? Rose?</p>
      <div id="form-styling">
    <form id="survey-form">
      <fieldset>
        <legend>Favorite Brand</legend>
        <label id="name-label" class="text-question">Name Your Favorite Wine
      <input id="name" type="text" placeholder="text" required/>
      </label>
      <label id="email-label" class="text-question">Name Favorite Brand
        <input id="email" type="email" placeholder="text" required/>
        <label id="number-label" class="text-question">Number of Favorite Wines
        <input id="number" type="number" min="0" max="5" placeholder="text">
        <select id="dropdown">
          <option>Chardonnay</option>
          <option>Pinot Gris</option>
              <option>Sauvignon Blanc</option>
          <option>Pinot Noir</option>
          <option>Merlot</option>
          <option>Syrah</option>
          </select>
          <br>
          <input id="radio" type="radio" value="white" name="wine">
          <label id="radio" class="radio-label">White
            <input id="radio" type="radio" value="red" name="wine">
            <label id="radio" class="radio-label">Red
              <input id="radio" type="radio" value="rose" name="wine">
              <label id="radio" class="radio-label">Rose
               <br>
 <input id="checkbox" type="checkbox" value="white">
            <label id="checkbox" class="checkbox-label">White
            <input id="checkbox" type="checkbox" value="red">
            <label id="checkbox" class="checkbox-label">Red
            <textarea>We would love to hear your comments about your favorite wines.
              </textarea>
            <button id="submit">Submit
              </button>
        </label>
        </fieldset>
      </form>
      </div>
    </main>
      </body>
      </html>
