# Deep-Learning-Term-Project

This project is designed to help you tune hyperparameters in deep learning.

By utilizing the TuneParams() class, anyone can easily perform hyperparameter tuning.


## Tuner.ipynb

Tuner consists of three methods except __init__.

It receives a list of rate of train data and test data, running rates, optimizers, and schedulers as input.

Tuner considers all combinations and confirms their performance and then provides the best performance combination to the user.

The following types of hyperparameters are as follows.

    • Batch size - batch_size, default = 32

    • Test rate - rate, default= 0.1

    • Epoch - epochs, default= 50

    • Learning rate - lr, default = 0.1

    • Optimizer – optim, default = sgd, choices = [‘sgd’, ‘adam’]

    • Scheduler – lr_scheduler, default = ‘none’, choices = ['multistep', 'stepLR', 'LambdaLR', 'none']

These arguments can be accessed and modified with self.args.argument_name.

<br>

Default Choice:

    Namespace(batch_size=32, epochs=5, lr=0.1, lr_scheduler='none', optim='sgd', rate=0.1)

## teamb.ipynb


If you want more information, please visit our wiki.
