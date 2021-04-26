# Seam Carving

A real-time implementation of [Seam Carving for Content-Aware Image Resizing [Avidan and Shamir 2007]](https://faculty.idc.ac.il/arik/SCWeb/imret/imret.pdf), adapted for the web. Check out the live demo here: https://brianstrauch.com/seam-carving/

## Instructions
1. To run, place an image in the `samples/` folder. (Ex: `samples/background.jpg`)
2. For best results, use an image with width ~1000px.
3. Use the Jupyter Notebook to create a delete-order matrix, stored in `samples/background-data-2x.json`.
4. Finally, include the title of the image (Ex: "background") in the first line of `carve.js`.
5. If running locally, run `python3 -m http.server` in the root directory and view the website at http://localhost:8000.
