# Converting Opensourced OCR Models to TFLite

This repository is to create tflite models for the available ocr models. Till now I have converted two popular OCR models to TFLite and also added inference codes.

### TFLite Models Available

- [Captcha OCR](https://keras.io/examples/vision/captcha_ocr/)
- [Keras OCR](https://github.com/faustomorales/keras-ocr)

### TFLite Models On Progress (Stay Tuned)

- [EasyOCR](https://github.com/JaidedAI/EasyOCR)

### About the files
 ```
 ├── colabs
     ├── KERAS_OCR_TFLITE.ipynb     --> End to End Code for Converting Keras OCR models to TFLite and doing inference.
     ├── captcha_ocr_tflite.ipynb   ---> End to End to Convert Keras Captcha OCR(by [Aakash](https://twitter.com/A_K_Nain)) to TFLite and code to do inference.

 ├── models
     ├──  ocr_dr.tflite                --> Captcha OCR TFLite model.
     ├──  keras_ocr_dr.tflite          --> Keras OCR Dynamic Range Quantized TFLite Model
     ├──  keras_ocr_float16.tflite     --> Keras OCR Float16 Quantized TFLite Model
 ├── images
     Contains sample input images used for inference.
 ├── data
     Contains representative dataset used while converting to TFLite using Integer Quantization.
 ```

Will be uploading end to end OCR with TFLite Models (CRAFT as Text Detector and Keras OCR as Text Recognizer) soon.

You can find this [repo](https://github.com/tulasiram58827/craft_tflite) for converting CRAFT models to TFLite and using them for inference. For more details please find these blogs on Text Detectors.

- [Converting CRAFT to TFLite: A Guide to PyTorch-TFLite Conversion](https://tulasi.dev/craft-in-tflite)
- [A Battle of Text Detectors for Mobile Deployments: CRAFT vs. EAST](https://sayak.dev/optimizing-text-detectors/)


Feel free to suggest any other models through issues or contribute using Pull Requests.
