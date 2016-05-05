# Zmq::Cli

A set of command line tools for working with multi-part 0MQ messages.

## Tools

- **zmq-cli** publishes a single message with the given topic & body to a bound subscriber.
- **zmq-pub** listens to messages (optionally with a topic filter) from a bound publisher.
- **zmq-bridge** relays messages from publishers to subscribers, and stores a copy of the most recent message for each topic in a LevelDB. When a subscriber first connects, the bridge re-publishes the latest message for each topic the subscriber is interested in.


## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/remis-thoughts/zmq-cli.

