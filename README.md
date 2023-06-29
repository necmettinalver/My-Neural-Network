# myNN Class

The `myNN` class is used to implement a simple neural network model. The neural network is trained to solve a classification problem using two input variables (`age` and `affordibility`). The training of the neural network is done using gradient descent.

## Installation

To run this code, you need the following requirements:
- Python 3.x
- NumPy library

You can install NumPy using the following command:



## İçindekiler

- [Proje Hakkında](#proje-hakkında)
- [Kurulum](#kurulum)
- [Kullanım](#kullanım)
- [Kat Contributing](#katkıda-bulunma)
- [Lisans](#lisans)

## Proje Hakkında

Proje hakkında daha detaylı bir açıklama buraya gelebilir. Projenin amacı, kullanım alanı, işlevleri ve benzeri bilgiler bu bölümde paylaşılabilir.

## Kurulum

Projeyi yerel makinenizde çalıştırmak için aşağıdaki adımları takip edin:

1. Adım 1
2. Adım 2
3. Adım 3

Her adımı detaylı olarak açıklayabilir veya gerekirse komut örnekleri de verebilirsiniz.

## Kullanım

API Methods
fit(X, y, epoch, loss_stop)
This method trains the neural network using the input dataset X and target classes y. The parameters are as follows:

X: Input dataset. It should be a dictionary with 'age' and 'affordibility' keys.
y: List of target classes.
epoch: Maximum number of iterations for the training loop.
loss_stop: Acceptable minimum loss value for early stopping.
predict(x)
This method makes a prediction for the given input instance x. The parameter is as follows:

x: Input data for which the prediction is to be made. It should be a dictionary with 'age' and 'affordibility' keys.
sigmoid_numpy(X)
This method applies the sigmoid activation function on the input data X.

log_loss(true, pred)
This method calculates the log loss on the true class labels true and the predicted class probabilities pred.

gradient_descent(age, affordability, y_true, epoch, loss_stop)
This method trains the neural network model using gradient descent. The variables used inside are age, affordability, y_true, epoch, and loss_stop parameters. This method shows the iteration steps during training and returns the best weight and bias values.
## Katkıda Bulunma

Projeye katkıda bulunmak isteyenler için talimatlar. Nasıl katkıda bulunabilecekleri, geliştirme ortamını nasıl kuracakları ve değişiklikleri nasıl gönderebilecekleri hakkında bilgi verilebilir.

## Lisans

Bu projenin lisans bilgileri buraya gelebilir. Hangi lisans altında dağıtıldığı veya kullanılabileceği belirtilmelidir. Örnek olarak:

[MIT Lisansı](https://opensource.org/licenses/MIT)
