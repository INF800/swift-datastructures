# Data Structures Library - Swift Programming Language

## How to use: 

- In Swift-Jupyter Notebooks
- In Swift Package Manager



**I Importing in Swift-Jupyter Notebooks**

Use the following in first cell (after restarting runtime)
```
%install-location $cwd/swift-install
%install '.package(url: "https://github.com/rakesh4real/swift-datastructures", from:"0.0.1")' DataStructures
```
*[Link to blank swift-jupyter notebook](https://colab.research.google.com/github/tensorflow/swift/blob/master/notebooks/blank_swift.ipynb)*

Then, import it using
```
import DataStructures
```



**II. Importing in SPM**

In package.swift:
```
// add this in appropriate place
.package(url: "https://github.com/rakesh4real/swift-datastructures", from:"0.0.1")

// add this in appropriate place i.e taget dependancies
.target(
            name: "DataStructures",
            dependencies: ["DataStructures"]
```

Then, import it using
```
import DataStructures
```

*Know more about SPM packages [here](https://github.com/rakesh4real/swift4tensorflow/tree/master/03-creating-packages/Basic)*

## Available Data Structures

- Stack
- Queue
- Array2D
