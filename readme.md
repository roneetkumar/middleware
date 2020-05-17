# Middleware

building HTTP middleware that will recover from any panics in an application, even if the response write has been partially written to, and then output the stack trace if the application is in development mode.
