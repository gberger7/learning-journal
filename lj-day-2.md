I learned a ton of helpful information today! One of the big things I learned was using an if/else statement. For the "about me" assignment, since had to come up with 5 questions yes and no answers, the if/else statement really helped a lot with that.

example:

JS

var answer1 = prompt('Hello! Is my name Gabe?').toUpperCase();
if (answer1 === "YES" || answer1 === "Y") {
  alert('That is correct my name is Gabe!');
  console.log('The user answered ' + answer1 + ' to whether my name was Gabe.')
}
else {
  alert('Sorry that is incorrect');
  console.log('The user answered ' + answer1 + ' to whether my name was Gabe.')
}

Also another very helpful thing I learned, was that using a "<div" tag instead of just a <h1> or <p> tag, helped me be able to add a border ,specifically, for around my <h1> and <p> tag.

example:

HTML

<div class="info">
      <h2>Personal info</h2>
      <p>My name is Gabe Altenberger and I am 19 years old from Brier, Washington.</p>
    </div>

CSS

.info {
  border: 2px solid black;
  width: 400px;
}
