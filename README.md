# Task 2: Chatbot performance and load testing

A lot of community members are asking for performance and load testing for chatbots.

The task is to develop a tool based on Botium which can be parameterized to:
* run a given conversation script sequential for x times
* run a given conversation script in parallel on x threads
* measure the response times during execution and report it during execution and as final summary

* The script should be developed in Javascript (Node.js)
* As test object you can use [this tutorial](https://chatbotsmagazine.com/3-steps-setup-automated-testing-for-google-assistant-and-dialogflow-de42937e57c6) to setup a simple chatbot with Dialogflow
* See [this Botium sample](https://github.com/codeforequity-at/botium-core/blob/master/samples/scripting/botiumFluentMemory.js) for an example how to run a single convo file against a chatbot with Botium

The code will be the base for a new Botium module which will be published later on (not part of this task).
