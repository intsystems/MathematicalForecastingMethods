# Mathematical Forecasting Methods, MIPT, 2024-2025

## Описание
Курс посвящен неклассическим математическим моделям в машинном обучении. Рассматриваются линейные, тензорные модели, глубокие нейронные сети и модели, работающие с дифференциальными уравнениями. Данными для моделирования являются видео, аудио, энцефалограммы, фМРТ и другие измерения в естественных науках. Практическими примерами являются BCI, прогнозирование погоды и различных пространственно-временных рядов.

## Материалы
### Семестр 1
| Лекции | Дата | Описание | Презентация | Запись |
|---------|--------|-------------|---------|-------| 
| 1 | Сентябрь, 10 | Введение. Обзор тем. | [slides](https://github.com/intsystems/MathematicalForecastingMethods/blob/main/lectures/lecture_1/lecture1.pdf) | [video](https://www.youtube.com/live/8Hn3Vj0yMic?si=d9vWlQiDTV1XD8mG) |
| 2 | Сентябрь, 17 | Стационарные временные ряды. Модели SARIMA.|[slides](https://github.com/intsystems/MathematicalForecastingMethods/blob/main/lectures/lecture_2/lecture2.pdf)|[video](https://www.youtube.com/live/AXiF5h1M40o?si=ARmq0dPVciU0fB-H) |
| 3 | Сентябрь, 24 | Векторная регрессия, модель VAR. Моделирование волатильности, модель GARCH.| [slides](https://github.com/intsystems/MathematicalForecastingMethods/blob/main/lectures/lecture_3/lecture3.pdf)| |
| 4 | Октябрь, 1 | Нейронные сети для пронозирования временных рядов. CNN, RNN, LSTM, GRU. | [slides](https://github.com/intsystems/MathematicalForecastingMethods/blob/main/lectures/lecture_4/lecture4.pdf)|| |
| 5 | Октябрь, 8 | Динамические методы обработки временных рядов. Время и фаза для периодических временных рядов. Теорема Такенса. CCM. | [slides](https://github.com/intsystems/MathematicalForecastingMethods/blob/main/lectures/lecture_5/lecture5.pdf) | |
| 6 | Октябрь, 15| Основные методы прогноза нерегулярных временных рядов. Локальное Фурье преобразование. SVD, SSA(PCA) и LA. |[slides](https://github.com/intsystems/MathematicalForecastingMethods/blob/main/lectures/lecture_6/lecture6.pdf)| |
| 7 | Октябрь, 22 | Прогноз методом SSA. Выравнивание рядов DTW, DWT-DBA | [slides](https://github.com/intsystems/MathematicalForecastingMethods/blob/main/lectures/lecture_7/lecture7.pdf)| - |
| 8 | Октябрь, 29 | Введение в NeuralODE. | [slides](https://github.com/intsystems/MathematicalForecastingMethods/blob/main/lectures/lecture_8/lecture8.pdf)| - |
| 9 | Ноябрь, 5 | NeuralODE, анализ динамических систем | - | [video](https://www.youtube.com/watch?v=Z389868f-jk&list=PLk4h7dmY2eYF6Q3hRut13RNcn83HrY_cY&index=8) |

| Семинар | Дата | Описание | Код |
|---------|--------|-------------|---------|
| 1 | Октябрь, 31| Декомпозиция временных рядов, FFT и  SSA. |[![Open In Github](https://img.shields.io/static/v1.svg?logo=github&label=Repo&message=Open%20in%20Github&color=lightgrey)](seminars/seminar6.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/file/d/1hsyLrDpYgWlGy08hF6KcOs7KvROYSdV4/view?usp=sharing)|
| 2 | Ноябрь, 14| Введение в NeuralODE. |[![Open In Github](https://img.shields.io/static/v1.svg?logo=github&label=Repo&message=Open%20in%20Github&color=lightgrey)](seminars/seminar8.ipynb)|

### Семестр 2
| Лекции | Дата | Описание | Презентация | Запись |
|---------|--------|-------------|---------|-------| 
| 10 | Март,  | Tensor Notations and Graphical Representations, Basic Multilinear Operations | [slides](https://github.com/intsystems/MathematicalForecastingMethods/blob/main/lectures/lecture_10/lecture10.pdf) | - |
| 11 | Март,  | CP-decomposition and alternated least squares | [slides](https://github.com/intsystems/MathematicalForecastingMethods/blob/main/lectures/lecture_11/lecture11.pdf) | - |
| 12 | Апрель, | Tucker decomposition and Higher-order singular values decomposition  | [slides](https://github.com/intsystems/MathematicalForecastingMethods/blob/main/lectures/lecture_12/lecture12.pdf) | - | | - |
| 13 | Апрель,  | Higher-order PLS and Prediction of the Response Variables | [slides](https://github.com/intsystems/MathematicalForecastingMethods/blob/main/lectures/lecture_13/lecture13.pdf) | - | | - |
| 14 | Апрель,  | Higher-order SSA (Tensor SSA) | [slides](https://github.com/intsystems/MathematicalForecastingMethods/blob/main/lectures/lecture_14/lecture14.pdf) | - | | - |
| 15 | Апрель,  | Tensor-Train Decomposition | [slides](https://github.com/intsystems/MathematicalForecastingMethods/blob/main/lectures/lecture_15/lecture15.pdf) | - | | - |
| 16 | Май, | Обсуждение лабораторных работ | - | - |



## Домашнее задание
### Семестр 1 
| Задание | Дата выдачи | Дата сдачи | Описание | Ссылка |
|---------|--------|-------------|--------|-------|
| 1 | Октябрь, 10 | Октябрь, 24 | Вводная теория: сравнение и анализ статистических моделей. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/16f63TDQWBTRHiEv_qqy09BPEsX5hST45?usp=sharing)|
| 2 | Ноябрь, 6 | Ноябрь, 19 | Dynamical Forecasting Methods, CCM, SSA | [![Open In Github](https://img.shields.io/static/v1.svg?logo=github&label=Repo&message=Open%20in%20Github&color=lightgrey)](homeworks/HW2_ts_dynamical_forecasting.ipynb)  |
| 3 | Ноябрь, 21 | Декабрь, 12 | Индивидуальные задания. (Лабораторная работа) | [ссылка](https://web.archive.org/web/20230610043830/http://machinelearning.ru/wiki/index.php?title=%D0%9C%D0%B0%D1%82%D0%B5%D0%BC%D0%B0%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B8%D0%B5_%D0%BC%D0%B5%D1%82%D0%BE%D0%B4%D1%8B_%D0%BF%D1%80%D0%BE%D0%B3%D0%BD%D0%BE%D0%B7%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F/%D0%9E%D1%81%D0%B5%D0%BD%D1%8C_2022#.D0.A1.D1.81.D1.8B.D0.BB.D0.BA.D0.B8_.D0.BD.D0.B0_.D0.BC.D0.B0.D1.82.D0.B5.D1.80.D0.B8.D0.B0.D0.BB.D1.8B_.D0.BA.D1.83.D1.80.D1.81.D0.B0)  |
### Семестр 2
| Задание | Дата выдачи | Дата сдачи | Описание | Ссылка |
|---------|--------|-------------|--------|-------|
| 1 | Апрель, 2 | Апрель, 16 | CP decomp, ALS, классификация ЭЭГ|[![Open In Github](https://img.shields.io/static/v1.svg?logo=github&label=Repo&message=Open%20in%20Github&color=lightgrey)](homeworks/HW3_tenscomp_tensor_als.ipynb)|
| 2 | Апрель, 16 | Май, 7 | Индивидуальные задания. (Лабораторная работа) ||

## Материалы
### Семестр 1
- [Статистический анализ данных (курс лекций МФТИ, К.В.Воронцов)](http://www.machinelearning.ru/wiki/index.php?title=%D0%A1%D1%82%D0%B0%D1%82%D0%B8%D1%81%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B8%D0%B9_%D0%B0%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7_%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85_%28%D0%BA%D1%83%D1%80%D1%81_%D0%BB%D0%B5%D0%BA%D1%86%D0%B8%D0%B9%2C_%D0%9A.%D0%92.%D0%92%D0%BE%D1%80%D0%BE%D0%BD%D1%86%D0%BE%D0%B2%29)
- [Введение в анализ временных рядов, МГУ](https://mse.msu.ru/wp-content/uploads/2021/03/%D0%92%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5-%D0%B2-%D0%B0%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7-%D0%B2%D1%80%D0%B5%D0%BC%D0%B5%D0%BD%D0%BD%D1%8B%D1%85-%D1%80%D1%8F%D0%B4%D0%BE%D0%B2-1.pdf)
- [Курс лекций Анализ временных рядов ВШЕ, Канторович Г.Г.](https://ej.hse.ru/data/2010/12/31/1208182144/06_01_06.pdf)
### Семестр 2
- [Low-Rank Tensor Networks for Dimensionality Reduction and Large-Scale Optimization Problems: Perspectives and Challenges PART 1](https://www.researchgate.net/publication/307636373_Low-Rank_Tensor_Networks_for_Dimensionality_Reduction_and_Large-Scale_Optimization_Problems_Perspectives_and_Challenges_PART_1)
- [Tensor Networks for Dimensionality Reduction and Large-Scale Optimizations. Part 2 Applications and Future Perspectives](https://www.researchgate.net/publication/317257563_Tensor_Networks_for_Dimensionality_Reduction_and_Large-Scale_Optimizations_Part_2_Applications_and_Future_Perspectives) 
- [Geometric Deep Learning Grids, Groups, Graphs, Geodesics, and Gauges](https://arxiv.org/abs/2104.13478)

## Предыдущие курсы
- [MathematicalForecastingMethods2022](https://github.com/intsystems/MathematicalForecastingMethods/tree/2022-course)
- [Mathematical forecasting](https://m1p.org/index.php/Mathematical_forecasting)



   
   
