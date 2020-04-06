TensorFlowThirdLab

### 1st Stage

В первом коммите (https://github.com/deeChyz/tensorflowThirdLab/commit/f1b6bcb06f7fade7c509367e8c3c0a56e29df23e) в файле train.py лежит код для обучения сверточной сети VGG16. Добавлены все требуемые слои и получены следующие результаты: 

## train, Метрика точности

![Image alt](https://github.com/deeChyz/tensorflowThirdLab/blob/master/1stStageGraphics/train_acc.jpg)

## train, Функция потерь

![Image alt](https://github.com/deeChyz/tensorflowThirdLab/blob/master/1stStageGraphics/train_loss.jpg)

## *************

## test, Метрика точности

![Image alt](https://github.com/deeChyz/tensorflowThirdLab/blob/master/1stStageGraphics/val_acc.jpg)

## test, Функция потерь

![Image alt](https://github.com/deeChyz/tensorflowThirdLab/blob/master/1stStageGraphics/val_loss.jpg)


### **************************************************


### 2nd Stage

Во втором коммите (https://github.com/deeChyz/tensorflowThirdLab/commit/a23a317614a69f925d6452b894b0d7ef683f7372) в файле train.py лежит код для обучения классификатора. Все происходило при замороженной сети, полученной на первом этапе.

## train, Метрика точности

![Image alt](https://github.com/deeChyz/tensorflowThirdLab/blob/master/2ndStageGraphics/train_acc.jpg)

## train, Функция потерь

![Image alt](https://github.com/deeChyz/tensorflowThirdLab/blob/master/2ndStageGraphics/train_loss.jpg)

## *************

## test, Метрика точности

![Image alt](https://github.com/deeChyz/tensorflowThirdLab/blob/master/2ndStageGraphics/val_acc.jpg)

## test, Функция потерь

![Image alt](https://github.com/deeChyz/tensorflowThirdLab/blob/master/2ndStageGraphics/val_loss.jpg)


### **************************************************


### 3nd Stage

Во третьем коммите (https://github.com/deeChyz/tensorflowThirdLab/commit/a23a317614a69f925d6452b894b0d7ef683f7372) в файле train.py лежит код для обучения сети. Все слоя разморожены.

## train, Метрика точности

![Image alt](https://github.com/deeChyz/tensorflowThirdLab/blob/master/3rdStageGraphics/train_acc.jpg)

## train, Функция потерь

![Image alt](https://github.com/deeChyz/tensorflowThirdLab/blob/master/3rdStageGraphics/train_loss.jpg)

## *************

## test, Метрика точности

![Image alt](https://github.com/deeChyz/tensorflowThirdLab/blob/master/3rdStageGraphics/val_acc.jpg)

## test, Функция потерь

![Image alt](https://github.com/deeChyz/tensorflowThirdLab/blob/master/3rdStageGraphics/val_loss.jpg)


### **************************************************


### Объедененные графики. 

## Синий - замороженная, красный - размороженная


## train, Метрика точности

![Image alt](https://github.com/deeChyz/tensorflowThirdLab/blob/master/ConcatGraphics/train_acc.jpg)

## train, Функция потерь

![Image alt](https://github.com/deeChyz/tensorflowThirdLab/blob/master/ConcatGraphics/train_loss.jpg)

## *************

## test, Метрика точности

![Image alt](https://github.com/deeChyz/tensorflowThirdLab/blob/master/ConcatGraphics/var_acc.jpg)

## test, Функция потерь

![Image alt](https://github.com/deeChyz/tensorflowThirdLab/blob/master/ConcatGraphics/var_loss.jpg)
