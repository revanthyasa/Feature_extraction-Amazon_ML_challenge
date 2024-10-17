**Amazon ML challenge**

This project focuses on extracting features from images, specifically designed as a business use case for most e-commerce websites. Leveraging the visual information in product images, we can extract crucial features such as volume, dimensions, weight, and other product-specific details. This feature extraction process is vital for enhancing product listings, automating product data entry, and improving the accuracy of information displayed on e-commerce platforms.

To achieve this, we implemented several image processing techniques, beginning with **greyscaling** to reduce computational complexity by converting the image to shades of gray. This step simplifies subsequent processing by focusing on key aspects without color distractions. We then applied **color contrasting** to enhance the distinction between important elements, making features like text more visible and easier to identify. **Color reduction** was also used to minimize unnecessary variations in the image, further emphasizing critical information.

Following these preprocessing steps, we utilized the **EasyOCR** module, which enabled the extraction of text from the processed images. EasyOCR is an Optical Character Recognition (OCR) library that uses deep learning models to accurately identify and convert characters in the image into machine-readable text.

Once the text was extracted, we used **regular expressions** to identify and extract specific features, such as product volume, dimensions, and weight, from the text obtained. Regular expressions are particularly effective for parsing text data because they allow us to search for predefined patterns that represent the desired attributes. This way, we could isolate and retrieve relevant information from the image, automating the feature extraction process efficiently.

By employing these image processing and text extraction techniques, this project aims to streamline the data extraction process for e-commerce platforms, ultimately enhancing user experience and operational efficiency.

