# Digital signal processing

![Digital signal processing](img/cic_signal.svg "Improve your skills in DSP!")

Проект содержит интерактивные материалы в виде законченных лекций по **цифровой обработке сигналов** (ЦОС) в виде тетрадок Jupyter Notebook. Это мои заметки по теоретическим аспектам и практическому применению задач ЦОС.  

Материалы представлены с использованием библиотек на языке *Python* (numpy , scipy, matplotlib, seaborn etc). Основная информация взята из **моих лекций**, которые я, будучи аспирантом, читал студентам Московского Энергетического Института (НИУ МЭИ). Частично информация из этих лекций была использована на обучающих семинарах в Центре Современной Электроники, где я выступал в качестве докладчика. Кроме того, в эти лекции входит перевод различных статей, компиляция материалов из достоверных источников и литературы по тематике цифровой обработки сигналов, а также официальная документация по прикладным пакетам и встроенным функциям библиотек scipy и numpy языка **Python**.  

Большая часть обучающего материала для наглядного и интерактивного представления реализована с использованием *Jupyter Notebook*.  

### Main information

| **Title**     | Digital signal processing |
| :-- | :-- |
| **Author**    | Alexander Kapitanov       |
| **Language**  | Python                    |
| **Contact**   | <hidden>                  |
| **Release**   | 10 Jul 2019               |
| **License**   | GNU GPL 3.0               |

### [List of lectures (Russian)](https://github.com/capitanov/dsp-theory/tree/master/src "DSP courses in RU")
### [List of lectures (English)](https://github.com/capitanov/dsp-theory/tree/master/src-en "DSP courses in EN")

- [Сигналы: аналоговые, дискретные, цифровые. Z-преобразование](https://nbviewer.jupyter.org/github/capitanov/dsp-theory/blob/master/src/dsp_theory_01_signals.ipynb "Signals, analog, digital, Z-transform"),
- [Преобразование Фурье: амплитудный и фазовый сигнала, ДПФ и БПФ](https://nbviewer.jupyter.org/github/capitanov/dsp-theory/blob/master/src/dsp_theory_02_spectrum.ipynb "Discrete Fourier Transform. FFT, IFFT"),
- [Свертка и корреляция. Линейная и циклическая свертка. Быстрая свёртка](https://nbviewer.jupyter.org/github/capitanov/dsp-theory/blob/master/src/dsp_theory_03_convolution.ipynb "Correlation, convolution: linear / circular / fast")
- [Случайные процессы. Белый шум. Функция плотности вероятностей](https://nbviewer.jupyter.org/github/capitanov/dsp-theory/blob/master/src/dsp_theory_04_random_noise.ipynb "Random signals AWGN, Noise")
- [Детерминированные сигналы. Модуляция: АМ, ЧМ, ФМ, ЛЧМ. Манипуляция](https://nbviewer.jupyter.org/github/capitanov/dsp-theory/blob/master/src/dsp_theory_05_modulation.ipynb "Modulation. AM-, FM-, Chirp signals")
- [Фильтрация сигналов: БИХ, КИХ фильтры](https://nbviewer.jupyter.org/github/capitanov/dsp-theory/blob/master/src/dsp_theory_06_iir_fir_filters.ipynb "IIR / FIR filters")
- [Оконная фильтрация. Детектирование слабых сигналов с помощью наложения окна](https://nbviewer.jupyter.org/github/capitanov/dsp-theory/blob/master/src/dsp_theory_07_windows.ipynb "Windows, filtration: Hann, Blackman, Flattop, Kaiser etc."), 
- [Ресемплинг: децимация и интерполяция. CIC-фильтры, фильтры скользящего среднего](https://nbviewer.jupyter.org/github/capitanov/dsp-theory/blob/master/src/dsp_theory_08_resampling.ipynb "CIC filters, decimation, interpolation, moving average")
- [Непараметрические методы спектрального анализа](https://nbviewer.jupyter.org/github/capitanov/dsp-theory/blob/master/src/dsp_theory_09_periodogram.ipynb "Spectrum analysis: Welch's Method")
- [Полифазные схемы преобразования Фурье - усреднение по частоте и по времени](https://nbviewer.jupyter.org/github/capitanov/dsp-theory/blob/master/src/dsp_theory_10_polyphase_ffts.ipynb "Spectrum analysis: average spectrum")

### List of requirements

| **Requirements** |
| :-- |
| `jupyter`        |
| `matplotlib`     |
| `seaborn`        |
| `scipy`          |
| `numpy`          |

P.S. Thanks for reading!  
P.P.S. English Version of the notebooks can be found in `src-en` folder.

### Link
  * https://habr.com/users/capitanov/
  
### Contributors:
  * Kapitanov Alexander (capitanov)
  * Vladimir Fadeev (kirlf)
  * Kunal Rustagi (kunalrustagi08) - EN versions.
  
### Release:
  * 2019/07/10.
    
### License:
  * GNU GPL 3.0.
