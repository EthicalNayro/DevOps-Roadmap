## Jenkins

# Main things to remember:
when wanting to use a different agent that will run a different container for each stage, we want to use:

```groovy
pipeline {
    agent none
}
