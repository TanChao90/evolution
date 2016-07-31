# Learn logging module

### Intro
- example-basicconfig: use `logging.basicConfig`
- example-fileconfig: use `logging.config.fileConfig`
- example-dictconfig: use `logging.config.dictConfig`
- logger_manager: implementing a logging wrapper


### logging module
- **Loggers** expose the interface that application code directly uses.
- **Handlers** send the log records (created by loggers) to the appropriate destination.
- **Filters** provide a finer grained facility for determining which log records to output.
- **Formatters** specify the layout of log records in the final output.


### Reference
- [logging — Logging facility for Python](https://docs.python.org/3/library/logging.html)
- [logging.config — Logging configuration](https://docs.python.org/3/library/logging.config.html)
- [logging.handlers — Logging handlers](https://docs.python.org/3/library/logging.handlers.html)