# Reverse image search proof of concept

This is a demo solution that shows how a reverse image search might work. To get this to work, you can do the following:

1. Build out an OpenSearch serverless collection. You can build one manually, or you can use the [opensearch.yml](./opensearch.yml) CloudFormation template to build one out.

2. Once the OpenSearch serverless collection has been built, run [image-search.ipynb](./image-search.ipynb). This notebook connects to the OpenSearch collection, creates a new index, loads a few images in the index, then allows you to perform a reverse image search.

