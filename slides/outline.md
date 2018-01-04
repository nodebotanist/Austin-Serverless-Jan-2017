# Talk Outline

* Do we need ops for serverless?
  * Of course!
  * Less built-in visibility
    * Nature of the beast
  * Need more visibility and observability
* The chicken and egg problem
  * Tooling is catching up
  * Platform lock-in vs relying on third-party tools
* The entire breakfast platter
  * Going to need a mix of tools
* What do we want to observe?
  * Platform
    * Cold starts
    * CPU
    * RAM
    * (through these things) cost
  * Code
    * How long your function takes to run
    * function errors
  * Architecture
    * DB connections
    * Comms with other services
* Looking into observability into AWS Lambda functions
  * X-Ray and cloudwatch logs
  * IOpipe