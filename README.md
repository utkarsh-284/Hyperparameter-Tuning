# Hyperparameter-Tuning

Welcome to my practice repository! This project contains my code and handwritten notes as I learn deep learning using the book **Hands-On Machine Learning with Scikit-Learn, TensorFlow, and Keras** by Aurélien Géron and the [Deep Learning Specialization playlist by Andrew Ng](https://youtube.com/playlist?list=PLkDaE6sCZn6Hn0vK8co82zjQtt3T2Nkqc&si=3jYzNcxgcTYQg_Vv).

---

## 📚 About This Repository

- **Practice Code:**  
  Jupyter notebooks based on the concepts and exercises from the book, focusing on building, training, and fine-tuning deep neural networks using TensorFlow and Keras.
- **Handwritten Notes:**  
  My personal notes summarizing key points, intuitions, and explanations from both the book and the video playlist.
- **Learning Sources:**  
  - Book: *Hands-On Machine Learning with Scikit-Learn, TensorFlow, and Keras* by Aurélien Géron
  - Playlist: [Deep Learning Specialization by Andrew Ng](https://youtube.com/playlist?list=PLkDaE6sCZn6Hn0vK8co82zjQtt3T2Nkqc&si=3jYzNcxgcTYQg_Vv)

---

## 📝 Contents

- `11_Training_Deep_Neural_Networks.ipynb`:  
  Example notebook demonstrating a deep neural network with batch normalization, training, and evaluation using TensorFlow/Keras.
- `Hyperparameter Tuning.pdf`:  
  File containing scanned handwritten notes and summaries from Andrew Ng's classes.

---

## 🚀 Example: Model Architecture

The notebook implements a sequential deep neural network with the following architecture:

| Layer                   | Output Shape | Parameters |
|-------------------------|--------------|------------|
| Flatten                 | (None, 784)  | 0          |
| BatchNormalization      | (None, 784)  | 3,136      |
| Dense (300 units)       | (None, 300)  | 235,500    |
| BatchNormalization      | (None, 300)  | 1,200      |
| Dense (100 units)       | (None, 100)  | 30,100     |
| BatchNormalization      | (None, 100)  | 400        |
| Dense (10 units, output)| (None, 10)   | 1,010      |

- **Total parameters:** 271,346  
- **Trainable parameters:** 268,978  
- **Non-trainable parameters:** 2,368

---

## 📈 Training Example

Sample training output:

> Epoch 1/2  
> 1719/1719 [6s 3ms/step] - accuracy: 0.7563 - loss: 0.7077 - val_accuracy: 0.8554 - val_loss: 0.3975  
> Epoch 2/2  
> 1719/1719 [5s 3ms/step] - accuracy: 0.8562 - loss: 0.4074 - val_accuracy: 0.8670 - val_loss: 0.3646

---

## 🎯 Learning Goals

- Understand and implement deep neural networks using TensorFlow and Keras.
- Apply techniques such as batch normalization and hyperparameter tuning.
- Reinforce concepts through handwritten notes and practical coding exercises.

---

## 📚 References

- **Book:**  
  [Hands-On Machine Learning with Scikit-Learn, TensorFlow, and Keras by Aurélien Géron]
- **Playlist:**  
  [Deep Learning Specialization by Andrew Ng]

---

## 🙌 Acknowledgements

- Aurélien Géron for the comprehensive book.
- Andrew Ng for the excellent video lectures.
- The open-source community for tools and resources.

---

## 📢 How to Use

1. Clone the repository.
2. Open the Jupyter notebooks in your preferred environment.
3. Browse the `notes/` folder for handwritten summaries.
4. Explore, experiment, and learn!

---

Happy Learning! 🚀

## Contributor
**Utkarsh Bhardwaj**  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Utkarsh284-blue)](https://www.linkedin.com/in/utkarsh284/)
[![GitHub](https://img.shields.io/badge/GitHub-utkarsh--284-lightgrey)](https://github.com/utkarsh-284)  
**Contact**: ubhardwaj284@gmail.com  
**Publish Date**: 15th June, 2025  
