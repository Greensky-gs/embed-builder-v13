# Embed builder
This is a command builder for discord.js v13

# Initialise

```js
client.on('messageCreate', (message) => {
    if (message.content.toLowerCase() == '!embed') {
        const { run } = require('./embed.js');

        run(message);
    };
});
```

Of course, it's an example.

## Error
If you encurate an error, please contact me on [this server](https://discord.gg/fHyN5w84g6)