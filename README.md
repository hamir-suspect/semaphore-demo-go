# Semaphore Continuous Integration Golang demo

[![Build Status](https://semaphore-demos.semaphoreci.com/badges/semaphore-demo-go/branches/fork-and-run.svg)](https://semaphore-demos.semaphoreci.com/projects/semaphore-demo-go)

This is an example program and CI pipeline showing how to run a Go project on [Semaphore](https://semaphoreci.com)

## CI on Semaphore

Feel free to fork this repository and use it to [create a Semaphore project][create-project].

The CI pipeline is defined in `.semaphore/semaphore.yml` and when you run it it will look like this:

![CI pipeline on Semaphore](.semaphore/ci-pipeline.png)

You can extend the pipeline with deployment by implementing a [promotion][promotions].  Refer to Semaphore documentation for additional [deployment examples][deployment-examples].

## License

Copyright (c) 2022 Rendered Text

Distributed under the MIT License. See the file LICENSE.

[create-project]: https://docs.semaphoreci.com/guided-tour/getting-started/
[promotions]: https://docs.semaphoreci.com/essentials/deploying-with-promotions/
[deployment-examples]: https://docs.semaphoreci.com/examples/tutorials-and-example-projects/#deployment
