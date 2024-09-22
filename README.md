# final-year-project

hey there!
as you might have noticed, the official docker registry image is not secured by default (at the time of writing) and is prone to MitM attack.

therefore, I did a script as my final year project to generate self-signed certificates for docker private registries that you're hosting on your local machine.
it allows you to set your own certificate details such as username and password, and you'll have to parse it while querying your private registries

in fact, I've also made things a bit easier, by writing a script to spin up a private registry as well so that you don't have to go through tons of commands :)

p.s. it works on debian-based linux for now

disclaimer: you're welcomed to play around with the scripts as experiment at your own risk, this project is not meant to serve other purposes beyond that
