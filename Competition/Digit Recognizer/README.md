# Digit Recognizer

Got 0.99232 on the [Digit Recognizer](https://www.kaggle.com/c/digit-recognizer/)

# Structure:
2 of 32 --> 2 of 64 --> 2 of 128

1st of each of the 2 are  
```python
m.add(keras.layers.BatchNormalization())
```

2nd of each has the following code
```python 
keras.layers.BatchNormalization()
keras.layers.MaxPool2D(2, 2)
keras.layers.Dropout(0.20)
```

# Graphs
![Graphs](/Images/graph.png)


# Conclusion
Got a pretty high placement, and CNN's are pretty cool!
