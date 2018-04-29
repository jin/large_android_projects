# android_projects

A selection of generated Android projects buildable with Gradle and Bazel.

This project is used for A/B testing build optimizations with the build systems.

For all projects:

- `bazel build //androidAppModule0`
- `gradle assembleDebug`

The projects are generated using various topologies, listed [here](https://github.com/android/android-studio-poet/commit/d7a97aa679438aedac7229b50f72d9526552b8b7).

## [simple_tree](/simple_tree)

### Gradle graph

![](simple_tree/gradle_graph.png)

### Bazel graph

![](simple_tree/bazel_graph.png)

## [variable_tree](/variable_tree)

### Gradle graph

![](variable_tree/gradle_graph.png)

### Bazel graph

![](variable_tree/bazel_graph.png)

## [full](/full)

### Gradle graph

![](full/gradle_graph.png)

### Bazel graph

![](full/bazel_graph.png)

## [connected](/connected)

### Gradle graph

![](connected/gradle_graph.png)

### Bazel graph

![](connected/bazel_graph.png)

## [linear](/linear)

### Gradle graph

![](linear/gradle_graph.png)

### Bazel graph

![](linear/bazel_graph.png)

## [star](/star)

### Gradle graph

![](star/gradle_graph.png)

### Bazel graph

![](star/bazel_graph.png)

## [rectangle](/rectangle)

### Gradle graph

![](rectangle/gradle_graph.png)

### Bazel graph

![](rectangle/bazel_graph.png)

## [connected_rectangle](/connected_rectangle)

### Gradle graph

![](connected_rectangle/gradle_graph.png)

### Bazel graph

![](connected_rectangle/bazel_graph.png)
