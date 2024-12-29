<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <title>CatPhotoApp</title>
    </head>
    <body>
        <main>

         <section>
            <h1>CatPhotoApp</h1>
            <h2>Cat Photos</h2>
            <!-- TODO: Add link to cat photos -->
            <p>See more <a href= "https://unsplash.com/s/photos/jaguar" target="_blank">cat photos</a> in our gallery.</p>
    
            <a href="https://unsplash.com/s/photos/jaguar">
             <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTHVm_3OwLUnE93_Fw-jveqN5smqZsPgtocXQ&s" alt=" black jaguar in desert">
            </a>
         </section>

         <section>
          <h2>Cat Lists</h2>
          <h3>Things cats love:</h3>
          <ul>
            <li>cat nip</li>
            <li>laser pointer</li>
            <li>lasagna</li>
          </ul>
          <figure>  
              <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
              <figcaption>cats <em>love</em> lasagna</figcaption>
          </figure>
          <h3>Top 3 things cats hate:</h3>
          <ol>
            <li>flea Treatment</li>
            <li>thunder</li>
            <li>other cats</li>
          </ol>

           <figure>

              <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Five cats looking around a field.">
              <figcaption>Cats <strong>hate</strong> other cats.</figcaption>

            </figure>
         </section>

         <section>
            <h2>Cat Form</h2>
            <form action="https://freecatphotoapp.com/submit-cat-photo">
                <fieldset>

                    <legend>Is your cat an indoor or outdoor cat?</legend>
                  <label><input checked type="radio" id="indoor" name="indoor-outdoor" value="indoor"> Indoor</label>
                  <label><input type="radio" id="outdoor" name="indoor-outdoor" value="outdoor"> Outdoor</label>

                </fieldset>


                <fieldset>

                    <legend> What's your cat's personality?</legend>
                   <input checked type="checkbox" id="loving" name="personality" value="loving"> 
                   <label for="loving">Loving</label>
                   <input type="checkbox" id="lazy" name="personality" value="lazy">
                   <label for="lazy">Lazy</label>
                   <input type="checkbox" id="energetic" name="personality" value="energetic">
                   <label for="energetic">Energetic</label>
                       
                </fieldset>
                <input required required type="text" placeholder="cat photo URL" name="catphotourl">
                <button type="submit"> Submit</button>
            </form>
         </section>
        </main>
        <footer>
            <p>No Copyright - <a href="https://www.freecodecamp.org" >Freecodecamp.org</a></p>
        </footer>
      </body>
    </html>
