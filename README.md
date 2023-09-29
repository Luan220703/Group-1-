# Cách viết code dành mạng nơ ron với Python, sử dụng thư viện tensorflow
1. Khai báo thư viện:
```
import tensorflow as tf
```
2. Thiết kế model:
```
model = tf.keras.Sequential([
    ...
])
model.compile(optimize = '', loss = '', metrics = [''])
model.summary()
model.fit(x_train, y_train, epochs = integer, batch_size = integer)
model.evaluate(x_test, y_test)
```
