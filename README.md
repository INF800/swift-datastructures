# Data Structures - Swift Programming Language

### How to use: 

- In swift-jupyter notebooks
- In Swift Package Manager

**Swift-Jupyter Notebooks**

Use the following in first cell (after restarting runtime)
```
%install-location $cwd/swift-install
%install '.package(url: "https://github.com/rakesh4real/swift-datastructures", from:"0.0.1")' DataStructures
```
*[Link to blank swift-jupyter notebook](https://colab.research.google.com/github/tensorflow/swift/blob/master/notebooks/blank_swift.ipynb)*

**In SPM*

In package.swift:
```
// add this in appropriate place
.package(url: "https://github.com/rakesh4real/swift-datastructures", from:"0.0.1")

// add this in appropriate place i.e taget dependancies
.target(
            name: "DataStructures",
            dependencies: ["DataStructures"]
```
