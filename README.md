# HumanDetection
Адаптирован код с https://gist.github.com/madhawav/1546a4b99c8313f06c0b2d7d7b4a09e2
1) Для запуска необходимы OpenCV версии выше 3.0, tensorflow >= 1.5, numpy
2) Необходимо загрузить и распаковать http://download.tensorflow.org/models/object_detection/faster_rcnn_inception_v2_coco_2018_01_28.tar.gz
3) В MODEL_PATH в main.py указать путь до файла frozen_inference_graph.pb из архива
4) В IMAGE_PATH указать путь до изображения
5) Запустить main.py
