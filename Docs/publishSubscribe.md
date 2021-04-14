# Publish - Subscribe Pattern 
----------------------------------------------------------------------
In Publish Subscribe pattern, only one message is published.
This message is delivered to all clients through **Topics**.
Topics act as a bulletin board.
Publishers and Subscribers are generally anonymous and can dynamically publish or subscribe to the topic. 
The Topic is responsible to hold and deliver messages.
The Topic retains messages as long as it takes to distribute to the present clients.

Below is the Architectural diagram of the Publish-Subscribe pattern:

> ![Publish-Subscribe](pspattern.png)

------------------------------------------------------------------------------

Some characteristics are
- Multiple subscribers for a message.
- Publisher and subscribe have a timing dependency.
  - A client that subscribes to a topic can consume only messages published after the client has created a subscription, 
    the subscriber must continue to be active in order for it to consume messages.
    
--------------------------------------------------------------------------------

For More information refer to [Wikipedia](https://en.wikipedia.org/wiki/Publish%E2%80%93subscribe_pattern).

---------------------------------------------------------------------------------