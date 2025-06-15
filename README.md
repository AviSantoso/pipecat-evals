# Pipecat Evals

A framework for evaluating LLM performance in Pipecat pipelines. This tool allows you to run standardized evaluations across different LLM implementations and configurations.

The framework provides a simple way to specify an LLM factory function that creates your model instance, along with a set of evaluation checkers that validate the model's responses. Evaluations can test for accuracy, consistency, safety, and other key metrics.

## Quick Start

See the [examples](examples/) directory for sample evaluations and checker implementations. The framework is designed to be extensible - you can easily add custom checkers for your specific use cases.
