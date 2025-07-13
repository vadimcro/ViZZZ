# ViZZ
Visual explanation of how tokens are being represented and addressed as embeddings inside the latent space.

<img width="1794" height="872" alt="image" src="https://github.com/user-attachments/assets/520d6555-8deb-4c85-8f39-441275d77ee7" />

Human visual perception of concepts cannot span across more than XYZ Dimentions. 
As a result - A visualization of complex spaces with N Dimentions (for example 700 dimentions) is rather difficult for us to grasp.
So what happends if we would like to show an example of how tokens are being represented as embeddings inisde a latent space?
Or even better: how vectors operate with different embeddings in order to represent a tokenized prompt?!

I have built this little demonstration tool for one of my lectures in order to visualize the main idea behing the inner workings
of diffusion operating within a Latent space: The user types in a word or a prompt, and the clusters that represent meanings of 
these embeddings within a 3D cube (latent space) light up. Type in one word - and get a highlighted cluster. Type in a sentence 
- and see how a vector connects the relevant clusters as it moves through the 3D cube.
  
Mathematically speaking - this is not correct! But for a sake of simplified explanation this is just enough to visualize
the inner working of a latents space, embeddings and motion vectors on a very basic and illustrative level.

Enjoy!
