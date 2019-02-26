# Unit Testing

When using the static Log, instead of the injected ILogger directly, all logging uses ILogger.Write instead of ([for example](https://github.com/serilog/serilog/blob/e638941551d353dbc588f0f21ab397d5d259de43/src/Serilog/Log.cs#L279)) ILogger.Verbose.
