# Description:
# Transfer learning example for TensorFlow.

licenses(["notice"])  # Apache 2.0

py_binary(
    name = "retrain",
    srcs = [
        "retrain.py",
    ],
    python_version = "PY2",
    srcs_version = "PY2AND3",
    deps = [
        "//tensorflow_hub:expect_numpy_installed",
        "//tensorflow_hub:expect_tensorflow_installed",
        "//tensorflow_hub",
        #  "tensorflow/contrib/quantize:quantize_graph",
    ],
)
