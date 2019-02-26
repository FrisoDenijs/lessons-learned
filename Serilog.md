# Unit Testing

When using the static [Log](https://github.com/serilog/serilog/blob/dev/src/Serilog/Log.cs), instead of the injected [ILogger](https://github.com/serilog/serilog/blob/dev/src/Serilog/ILogger.cs) directly, all logging uses [ILogger.Write](https://github.com/serilog/serilog/blob/e638941551d353dbc588f0f21ab397d5d259de43/src/Serilog/ILogger.cs#L91) instead of ([for example](https://github.com/serilog/serilog/blob/e638941551d353dbc588f0f21ab397d5d259de43/src/Serilog/Log.cs#L279)) ILogger.Verbose.
