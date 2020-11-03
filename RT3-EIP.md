# Enterprise Integration Patterns

- **Body**
  - The data being transmitted, which is generally ignored by the messaging system and simply transmitted as is.
- **Header**
  - Information used by the messaging system that describes the data being transmitted, its origin, its destination, and so on.
- **Message**
  - Package the information into a Message, a data record that the messaging system can transmit through a Message Channel.
- **Message Channel**
  - Connect the applications using a Message Channel, where one application writes information to the channel and the other one reads that information from the channel.
- **Message Endpoint**
  - Connect an application to a messaging channel using a Message Endpoint, a client of the messaging system that the application can then use to send or receive Messages.
- **Message Router**
  - Insert a special filter, a Message Router, which consumes a Message from one Message Channel and republishes it to a different Message Channel, depending on a set of conditions.
- **Message Translator**
  - Use a special filter, a Message Translator, between other filters or applications to translate one data format into another.
- **Pipes and Filters**
  - Use the Pipes and Filters architectural style to divide a larger processing task into a sequence of smaller, independent processing steps (filters) that are connected by channels (pipes).
