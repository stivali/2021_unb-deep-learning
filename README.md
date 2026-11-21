# Deep Learning Coursework — University of Brasília (2021)

This repository contains five **R Markdown (`.Rmd`) exercise solutions and their rendered HTML versions** prepared for the graduate course **Redes Neurais Profundas (Deep Neural Networks)**, offered by the **Graduate Program in Statistics at the University of Brasília (UnB)** in the first academic semester of 2021 and taught by **Professor Guilherme Souza Rodrigues**.

The exercises were completed by **Matheus Stivali** during his graduate studies. They document practical work with neural-network fundamentals, optimization algorithms, and deep-learning applications using R, including the R interfaces to Keras and TensorFlow.

## Exercise solutions

Each exercise is available as **source code (`.Rmd`)** and as a **rendered HTML document** showing the results produced at the time. The HTML files can be downloaded and opened in a web browser without installing R, Python, Keras, or TensorFlow.

| Exercise | R Markdown | HTML | Topics |
| --- | --- | --- | --- |
| List 1 | [`.Rmd`](listas/lista_1/Lista_1.Rmd) | [HTML](listas/lista_1/Lista_1.html) | Building a feed-forward neural network in R without a dedicated neural-network training framework; activation functions, gradients, and backpropagation. |
| List 2 | [`.Rmd`](listas/lista_2/Lista_2.Rmd) | [HTML](listas/lista_2/Lista_2.html) | Dropout regularization, a revised matrix-based backpropagation implementation, and comparison with Keras. |
| List 3 | [`.Rmd`](listas/lista_3/Lista_3.Rmd) | [HTML](listas/lista_3/Lista_3.html) | Numerical optimization: gradient descent, momentum, RMSProp, and Adam. |
| List 4 | [`.Rmd`](listas/lista_4/Lista_4.Rmd) | [HTML](listas/lista_4/Lista_4.html) | Image preprocessing and convolutional neural networks for an image-classification exercise using Keras/TensorFlow. |
| List 5 | [`.Rmd`](listas/lista_5/Lista_5.Rmd) | [HTML](listas/lista_5/Lista_5.html) | Recurrent neural networks and LSTM models for time-series forecasting, with comparisons to conventional time-series methods. |

## Scope and historical context

These files are **coursework from 2021**, not a maintained software package or a reproducibility archive. The `.Rmd` source files document the methods studied and implemented, while the accompanying HTML files preserve the rendered outputs from the original coursework. The exercises have **not been re-executed or adapted to current versions** of R, Python, Keras, or TensorFlow.

The original work used R alongside Python-based deep-learning libraries accessed through R. Some scripts contain absolute paths to directories on the computer used at the time, and some exercises rely on datasets or images that are **not distributed here**. Consequently, running the files as-is on another computer is not expected to work without additional setup and changes.

The repository includes the exercise solutions in `.Rmd` and HTML formats. Assignment handouts, the course syllabus, source datasets, and PDF/Word outputs are not included. The HTML documents are historical outputs, not evidence of successful execution with current software versions.

## Repository layout

```text
.
├── README.md
├── .gitignore
└── listas/
    ├── lista_1/
    │   ├── Lista_1.Rmd
    │   └── Lista_1.html
    ├── lista_2/
    │   ├── Lista_2.Rmd
    │   └── Lista_2.html
    ├── lista_3/
    │   ├── Lista_3.Rmd
    │   └── Lista_3.html
    ├── lista_4/
    │   ├── Lista_4.Rmd
    │   └── Lista_4.html
    └── lista_5/
        ├── Lista_5.Rmd
        └── Lista_5.html
```

The exercise narratives and code comments are primarily in Portuguese, as originally submitted.
