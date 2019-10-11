# modmail
A modern email submission and delivery stack

Mail stacks are fragmented and complex to set up and maintain.
They often are still configured by default for plaintext storage and encryption during transport is treacherous.

The goal of this project is to create a highly-integrated, scalable, easy to configure mail submission and delivery stack.
A secondary goal is to minimize the cost of hosting this stack on a cloud provider.

## Architectural Philosopy

I'll be using something of a unique architecture in order to reach these goals.

One of the strategies that I've decided to use here is to leverage this as an opportunity to suss out which parts of the modern concepts of in the OS and processor are keeping us from being more productive developers.

What I mean by "productive developers" should not be taken literally as written.
I'm not as interested in how much work a developer can do, but the total productivity of all developers.

If we consider what a developer is, we could reduce it to a person that wants to 

Maybe even a custom OS.

## Email

When we think of the flow of email from a remote user it looks kind of like this:

```
CLIENTr -> SERVr -> SERVl -> CLIENTl

```

Was going to write an instagram clone, but figured this would be more useful.

## Desired Semantics

### Routing

The system will get messages sumbitted from two sources, remote clients and remote servers.
It will send messages TO two destination, .


### Remote Delivery

- Message queueing is required in order to handler outages of the target system.

- Tranport must be TLS encrypted.

### Local Delivery
