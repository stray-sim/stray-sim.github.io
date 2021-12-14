## STRAY Simulation platform for radiology systems


The simulator can deal with a wide variety of scanning geometries but does not include the source model (heel effect, polychromatic nature, focal spot) or detector model (noise model, intensity response), both of which could easily be included in the future as new modules of STRAY in the support layer.


### Features


- Offers a high degree of flexibility, allowing any value in system parameters: source-to-object distance, detector-to-object distance, detector misalignment, projection size, volume size.
- Fast multicore and GPU implementation allowing automatic HW resource management. Allows handling 2K resolution volumes on a 32 GB RAM PC. Implementation has been accelerated and optimized, reaching a utilization rate of 95% of the computer's hardware resources (both CPU and GPU). 
- Implementation of dynamic partitioning of the input data. This feature allows the application to run on a multitude of devices and systems.
- Portable implementation as it is possible to run it on both Windows and Linux based systems. 
- Includes the following default configurations: circular CT, helical CT, extended field of view and two tomosynthesis configurations.


### Contributors

Computer Science and Engineering Dept., Universidad Carlos III de Madrid, Madrid, Spain \
Dept. Bioingeniería e Ingeniería Aeroespacial, Universidad Carlos III de Madrid, Madrid, Spain \
Instituto de Investigación Sanitaria Gregorio Marañón, Madrid, Spain \
Centro de Investigación Biomédica en red de Salud Mental (CIBERSAM), Madrid, Spain

### Support or Contact

<div id="contact">
        <h2>Get in Touch</h2>
        <div id="contact-form">
                <form action="https://formspree.io/f/mzbobavj" method="POST">
  <label>
    Your email: <input type="email" name="_replyto">
  </label>
  <label>
    Your message: <textarea name="message"></textarea>
  </label>
  <button type="submit">Send</button>
</form>
        </div>
    </div>
    
 
### Citation

FUX-Sim: Implementation of a fast universal simulation/reconstruction framework for X-ray systems
Monica Abella, Estefania Serrano, Javier Garcia-Blas, Ines García, Claudia de Molina, Jesus Carretero, Manuel Desco
Published: July 10, 2017
https://doi.org/10.1371/journal.pone.0180363
