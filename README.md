# PhotoRead-Scene-Text-Detection
A scene text detection and recognition model that performs OCR in two stages: text detection using a MobileNetV2 model (trained via transfer learning on a COCO dataset subset) and text recognition using a CNN followed by Bi-Directional LSTMs trained on the MjSynth dataset.
