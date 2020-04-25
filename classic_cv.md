# Классика Computer Vision

### Содержание
* [Введение в CV](#overview)
* [Работа с цветами](#colors)
* [Features](#features)
* [Object detection](#detection)
* [Denoising](#denoising)
* [Object Tracking](#tracking)
* [Optical flow](#optical_flow)
* [Лекции](#lectures)
* [Usefull Tools](#tools)

---

### 1. Введение в CV <a class="anchor" id="overview"></a>

Базовые понятия, идеи и задачи, которые решает компьютерное зрение, отражены в следующихх постах.

* [Постановка задачи компьютерного зрения](https://habr.com/ru/post/274725/)

* [Пару слов о распознавании образов](https://habr.com/ru/post/208090/)

* [Understanding Convolutions](http://colah.github.io/posts/2014-07-Understanding-Convolutions/)

* Book – [Computer Vision:  Models, Learning, and Inference](http://www.computervisionmodels.com/)

* Book – [Computer Vision: Algorithms and Applications](http://szeliski.org/Book/)


### 2. Работа с цветами <a class="anchor" id="colors"></a>

* [Основы теории цвета. Система CIE XYZ](https://habr.com/ru/post/209738/)

* [У цветового треугольника не два, а один угол](https://habr.com/ru/post/440550/)

* [Changing the contrast and brightness of an image](https://docs.opencv.org/3.4/d3/dc1/tutorial_basic_linear_transform.html)

* [Histograms in OpenCV](https://docs.opencv.org/3.1.0/de/db2/tutorial_py_table_of_contents_histograms.html)

* [Быстрый способ увеличить контрастность цветного изображения с OpenCV](http://qaru.site/questions/608223/whats-the-fastest-way-to-increase-color-image-contrast-with-opencv-in-python-cv2)

* [Определение доминирующих цветов: Python и метод k-средних](https://habr.com/ru/post/156045/)

* [OpenCV на python: поиск цветного объекта](https://robotclass.ru/tutorials/opencv-moments-color-object-search/)


### 3. Features <a class="anchor" id="features"></a>

* [Алгоритмы выделения контуров изображений](https://habr.com/ru/post/114452/)

* [Meanshift and Camshift](https://docs.opencv.org/3.2.0/db/df8/tutorial_py_meanshift.html)

* [Построение SIFT дескрипторов и задача сопоставления изображений](https://habr.com/ru/post/106302/)

* [2D Features frameworks](https://docs.opencv.org/3.4/d9/d97/tutorial_table_of_content_features2d.html)

* [«Выглядит похоже». Как работает перцептивный хэш](https://habr.com/ru/post/120562/)

* [OpenCV - Сравнение изображений через хэш](http://robocraft.ru/blog/computervision/537.html)

* [Построение перспективного искажения - теория](https://habr.com/ru/post/248611/)

* [Bilateral Filtering for Gray and Color Images](http://homepages.inf.ed.ac.uk/rbf/CVonline/LOCAL_COPIES/MANDUCHI1/Bilateral_Filtering.html#Introduction)

* [Выделение и описание контуров](http://wiki.technicalvision.ru/index.php/%D0%92%D1%8B%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5_%D0%B8_%D0%BE%D0%BF%D0%B8%D1%81%D0%B0%D0%BD%D0%B8%D0%B5_%D0%BA%D0%BE%D0%BD%D1%82%D1%83%D1%80%D0%BE%D0%B2)

* [Shape Matching using Hu Moments](https://www.learnopencv.com/shape-matching-using-hu-moments-c-python/)

 * Paper — [Analysis of Hu's moment invariants on image scaling and rotation](https://www.researchgate.net/publication/224146066_Analysis_of_Hu's_moment_invariants_on_image_scaling_and_rotation)

* [Image Moments](http://aishack.in/tutorials/image-moments/)

* [Image Feature Extraction and Matching](https://www.kaggle.com/wesamelshamy/tutorial-image-feature-extraction-and-matching)

* [Feature Detection and Description — OpenCV](https://docs.opencv.org/3.0-beta/doc/py_tutorials/py_feature2d/py_table_of_contents_feature2d/py_table_of_contents_feature2d.html)

* [Детекторы и дескрипторы особых точек FAST, BRIEF, ORB](https://habr.com/ru/post/414459/)

* [Детекторы углов](https://habr.com/ru/post/244541/)

* [A single scale retinex based method for palm vein extraction](https://arxiv.org/abs/1605.08154)


### 4. Object detection <a class="anchor" id="detection"></a>

* [Пару слов о распознавании образов](https://habr.com/ru/post/208090/)

* [Обучение машины — забавная штука: современное распознавание лиц с глубинным обучением](https://habr.com/ru/post/306568/)

* [Application: A Face Detection Pipeline](https://jakevdp.github.io/PythonDataScienceHandbook/05.14-image-features.html)

* [OpenCV shape detection](https://www.pyimagesearch.com/2016/02/08/opencv-shape-detection/)


### 5. Denoising <a class="anchor" id="denoising"></a>

* [Image Quality Assessment: A Survey](https://medium.com/@ocampor/advanced-methods-for-iqa-37581ec3c31f)

* [Восстановление смазанных и расфокусированных изображений с помощью фильтра Винера](https://habr.com/ru/post/424987/)

* [Восстановление расфокусированных и смазанных изображений](https://habr.com/ru/post/136853/)

* [OpenCV - голографическое кодирование картинки](http://robocraft.ru/blog/computervision/549.html)

* [Бинаризация изображений: алгоритм Брэдли](https://habr.com/ru/post/278435/)


### 6. Object Tracking <a class="anchor" id="tracking"></a>

* [Object Tracking using OpenCV](https://www.learnopencv.com/object-tracking-using-opencv-cpp-python/)

* [Real-time Human Detection](https://medium.com/@madhawavidanapathirana/https-medium-com-madhawavidanapathirana-real-time-human-detection-in-computer-vision-part-1-2acb851f4e55)

* [Basic motion detection and tracking with Python and OpenCV](https://www.pyimagesearch.com/2015/05/25/basic-motion-detection-and-tracking-with-python-and-opencv/)

* [Tracking object orientation with image moments](http://raphael.candelier.fr/?blog=Image%20Moments)


### 7. Processing <a class="anchor" id="processing"></a>

* [Преобразование Фурье. Линейная фильтрация в частотной области](http://wiki.technicalvision.ru/index.php/%D0%9F%D1%80%D0%B5%D0%BE%D0%B1%D1%80%D0%B0%D0%B7%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5_%D0%A4%D1%83%D1%80%D1%8C%D0%B5._%D0%9B%D0%B8%D0%BD%D0%B5%D0%B9%D0%BD%D0%B0%D1%8F_%D1%84%D0%B8%D0%BB%D1%8C%D1%82%D1%80%D0%B0%D1%86%D0%B8%D1%8F_%D0%B2_%D1%87%D0%B0%D1%81%D1%82%D0%BE%D1%82%D0%BD%D0%BE%D0%B9_%D0%BE%D0%B1%D0%BB%D0%B0%D1%81%D1%82%D0%B8)

* [Digital Image Processing using Fourier Transform in Python](https://medium.com/@hicraigchen/digital-image-processing-using-fourier-transform-in-python-bcb49424fd82)

### 8. Optical flow <a class="anchor" id="optical_flow"></a>

* [Introduction to Motion Estimation with Optical Flow](https://nanonets.com/blog/optical-flow/)

* [Dense optical flow with Python using OpenCV](https://medium.com/@igorirailean/dense-optical-flow-with-python-using-opencv-cb6d9b6abcaf)

* [A Brief Review of FlowNet](https://towardsdatascience.com/a-brief-review-of-flownet-dca6bd574de0)

* Paper – [An Efficient Optical Flow Based Motion Detection Method for Non-stationary Scenes](https://arxiv.org/abs/1811.08290)

* Paper – [A Robust Visual System for Small Target Motion Detection Against Cluttered Moving Backgrounds](https://arxiv.org/abs/1904.04363)

* Paper - [Optical Flow Based Real-time Moving Object Detection in Unconstrained Scenes](https://arxiv.org/abs/1807.04890)


### Лекции <a class="anchor" id="lectures"></a>

* [UCF Computer Vision Video Lectures 2012](https://www.youtube.com/playlist?list=PLd3hlSJsX_Imk_BPmB_H3AQjFKZS9XgZm)

Курс из 20 лекций по 45-90 минут. Академично и глубоко рассматриваются фундаментальные матрицы изображений, оптический поток, масштабно-инвариантное преобразование признаков, различные алгоритмы и методы работы с изображением

* [Введение в компьютерное зрение](https://www.lektorium.tv/course/22847)

В курсе рассматривают как базовые понятия компьютерного зрения, так и ряд современных алгоритмов, позволяющих решать практические задачи. Отдельно отмечают связь методов компьютерного зрения с обработкой зрительной информации в мозгу человека

* [Лекции по работе с OpenCV](https://www.lektorium.tv/speaker/2895)

* [Алгоритмические основы растровой графики](https://www.intuit.ru/studies/professional_skill_improvements/1281/courses/163/info)

Учебное пособие посвящено изложению основных принципов и алгоритмов, применяемых в растровой машинной графике.
В курсе затрагивается широкий круг вопросов, включающий также проблемы цветопередачи и сжатия изображений.

* [Курс Олимпиадных школ МФТИ](https://github.com/ml-dafe/cv_mipt_olymp_school)


### Usefull Tools <a class="anchor" id="tools"></a>

* [OpenCV Python documentation](https://docs.opencv.org/3.0-beta/index.html)

* [Image manipulation and processing using Numpy and Scipy](http://scipy-lectures.org/advanced/image_processing/)

* [Tutorials: Image processing algorithms](http://aishack.in/tutorials/)