# Tensorflow Serving

TensorFlow Serving is a flexible, high-performance serving system for machine learning models, designed for production environments. It deals with the inference aspect of machine learning, taking models after training and managing their lifetimes, providing clients with versioned access via a high-performance, reference-counted lookup table. TensorFlow Serving provides out-of-the-box integration with TensorFlow models, but can be easily extended to serve other types of models and data.

To note a few features:

Can serve multiple models, or multiple versions of the same model simultaneously
Exposes both gRPC as well as HTTP inference endpoints
Allows deployment of new model versions without changing any client code
Supports canarying new versions and A/B testing experimental models
Adds minimal latency to inference time due to efficient, low-overhead implementation
Features a scheduler that groups individual inference requests into batches for joint execution on GPU, with configurable latency controls
Supports many servables: Tensorflow models, embeddings, vocabularies, feature transformations and even non-Tensorflow-based machine learning models

GitHub Repo: [https://github.com/tensorflow/serving](https://github.com/tensorflow/serving)