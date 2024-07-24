# DigiNotes: Comprehensive Lecture Note Digitization Tool
Whether it’s the professors’ lecture notes on the chalkboard, or your friend’s handwritten notes on paper, the common method for copying down other people’s notes is taking a quick picture on your phone. One expects the content to be replete with some text, numerous equations, and a few diagrams. Our project explores the idea of converting handwritten words, equations, and diagrams into an easily digestible, digital format. Our project aims to recognize and process these inputs, by constructing a rich digital representation of the image for later use. GitHub Repository can be found \href{https://github.com/a-cowlagi/DigiNotes}{here}.

## Introduction
A hastily taken snapshot of a whiteboard is undoubtedly an image with plenty of noise and image nuisances (occlusions, lighting, brightness, etc.). Consequently, implementing a truly robust digitization pipeline requires a comprehensive preprocessing stage. Our preprocessing stage is able to return high-quality representations of the source image by performing 1) aspect ratio preserving perspective correction, 2) image enhancement and binarization, 3) line segmentation, 4) bounding box detection.\\ 

Following the preprocessing stage, we move onto recognizing the various kinds of text possibly present in the image -- plain text and mathematical formulae. We are able to parse text using a transformer-based architecture on the line-segmented images, while employing a third-party service to produce \LaTeX source code representations of any mathematical formulae present. \\

We then extract any diagrams present in the image using another bounding box based approach. Then, we using a variational autoencoder in tandem with a nearest neighbors model to serve similar diagrams and related documents -- for any diagram in the source space, we find its nearest neighbor in the latent space of the autoencoder and serve the documents corresponding to these nearest neighbors in the digital representation.\\  \\

Finally, we synthesize the outputs of the various stages of processing into a single information-rich, digital document that the user may readily return to at any point in the future. 

<a href="img/board_view.webp" target="_blank">
    <img src="img/board_view.webp" align="right" alt="Size Limit logo by Anton Lovchikov" width="40%">
</a>

<a href="img/conversions_digitool.webp" target="_blank">
    <img src="img/conversions_digitool.webp" align="right" alt="Size Limit logo by Anton Lovchikov" width="40%">
</a>


