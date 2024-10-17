# Aspose.OCR Resource Repository

Aspose.OCR is an advanced optical character recognition library that offers a wide variety of features and supports a large number of recognition languages.

The distributive provides only basic recognition capabilities. Additional features are added via downloadable resources available in this repository. This approach allows you to selectively choose which additional features you need for your project, keeping the core codebase lean and modular.

## Managing OCR resources

Aspose.OCR library _automatically_ downloads the required resources as needed, saving you time and effort in managing dependencies. However, you have the option to manually manage the resources for your project if needed:

### Manually downloading

This method is preferred if you do not want your application to access the Internet at runtime.

1. Download the resource files that are used in your project from the repository. Check out the resource descriptions below to decide what you need.
2. Place the downloaded .OCR files into a local directory.
3. Set an absolute or relative path to that directory in your project's source code.
4. Optionally disable automatic downloads in your project's source code.

**NOTE:** Do not forget to include a directory with downloaded resources in your distributive.

### Using the local repository

This method is preferred if you want to keep the distribution size to a minimum while maintaining full control over the online resource accessed by the application.

1. Clone the **entire** contents of the repository to:

    - A directory on web site (either intranet or public);
    - Publicly accessible S3 bucket or other online storage with web access;
    - Your corporate GitHub repository.

2. Set the **root** URL where the resources are available in your project's source code. For example:  
   `https://github.com/aspose-ocr/resources/tree/main`  
   `http://localhost/aspose-ocr-resources`

3. Optionally allow outbound HTTP access to that URL for your application in the firewall.

The required resources will be downloaded as needed from the URL you have configured.

## Resources

### Document structure detection (aspose-ocr-document-structure-detection-v1)

This resource allows you to choose between the core document region detection algorithms and use recognition methods that rely on these algorithms:

- Detect large blocks of text, such as paragraphs and columns;
- Detect smaller text areas in an image, such as individual words, phrases, or lines;
- Detect large blocks of text and then scan for individual words, phrases, or lines.

#### Compatibility

- Aspose.OCR for .NET 24.3.0 or later
- Aspose.OCR for Python via .NET 24.3.0
- Aspose.OCR for Java 24.2.0 or later
- Aspose.OCR for Python via Java 24.2.0 or later
- Aspose.OCR for C++ 24.4.0 or later

### Advanced OCR models (aspose-ocr-advanced-recognition-v1)

This resource allows you to use the following specialized document areas detection algorithms and use recognition methods that rely on those algorithms:

- Detect tabular structures and extract text from cells;
- Automatically track and straighten curved lines of text.

#### Compatibility

- Aspose.OCR for .NET 24.3.0 or later
- Aspose.OCR for Python via .NET 24.3.0
- Aspose.OCR for Java 24.2.0 or later
- Aspose.OCR for Python via Java 24.2.0 or later
- Aspose.OCR for C++ 24.4.0 or later

### Smart image processing (aspose-ocr-advanced-preprocessing-v1)

This resource allows you to use advanced automated image preprocessing filters that enhance an image before it is sent to the OCR:

- Automatically remove dirt, spots, scratches, glare, unwanted gradients, and other noise from photos and scans;
- Straighten page curvature and fix camera lens distortion for page photos.

#### Compatibility

- Aspose.OCR for .NET 24.3.0 or later
- Aspose.OCR for Python via .NET 24.3.0
- Aspose.OCR for Java 24.2.0 or later
- Aspose.OCR for Python via Java 24.2.0 or later
- Aspose.OCR for C++ 24.4.0 or later

### Cyrillic text recognition (aspose-ocr-cyrillic-v1)

This recognition model allows to to extract Cyrillic characters from images.

#### Compatibility

- Aspose.OCR for .NET 24.3.0 or later
- Aspose.OCR for Python via .NET 24.3.0
- Aspose.OCR for Java 24.2.0 or later
- Aspose.OCR for Python via Java 24.2.0 or later
- Aspose.OCR for C++ 24.4.0 or later

### Chinese text recognition (aspose-ocr-chinese-v2)

This recognition model allows to to extract Chinese characters from images.

#### Compatibility

- Aspose.OCR for .NET 24.3.0 or later
- Aspose.OCR for Python via .NET 24.3.0
- Aspose.OCR for Java 24.2.0 or later
- Aspose.OCR for Python via Java 24.2.0 or later
- Aspose.OCR for C++ 24.4.0 or later

### Hindi text recognition (aspose-ocr-hindi-v1)

This recognition model allows to to extract Hindi (Devanagari) characters from images.

#### Compatibility

- Aspose.OCR for .NET 24.3.0 or later
- Aspose.OCR for Python via .NET 24.3.0
- Aspose.OCR for Java 24.2.0 or later
- Aspose.OCR for Python via Java 24.2.0 or later
- Aspose.OCR for C++ 24.4.0 or later

### Arabic, Persian and Urdu text recognition (aspose-ocr-arabic-v1)

This recognition model allows to to extract the following texts:

- Arabic
- Persian (Farsi)
- Uyghur
- Urdu

The model also supports texts in mixed alphabets (the mix of national characters and English).

#### Compatibility

- Aspose.OCR for .NET 24.4.2 or later
- Aspose.OCR for Java 24.4.1 or later

### Handwritten text recognition (aspose-ocr-handwriting-v1)

This recognition model allows to to extract handwritten text from images.

#### Compatibility

- Aspose.OCR for .NET 24.3.0 or later
- Aspose.OCR for Python via .NET 24.3.0
- Aspose.OCR for Java 24.2.0 or later
- Aspose.OCR for Python via Java 24.2.0 or later

### Sparse text recognition (aspose-ocr-text-in-wild-v1)

This recognition model allows to extract content from street photos and other images with sparse text and noisy/colored backgrounds.

#### Compatibility

- Aspose.OCR for .NET 24.3.0 or later
- Aspose.OCR for Python via .NET 24.3.0
- Aspose.OCR for Java 24.2.0 or later
- Aspose.OCR for Python via Java 24.2.0 or later
