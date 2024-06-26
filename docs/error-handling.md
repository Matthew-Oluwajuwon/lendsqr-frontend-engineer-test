# ⚠️ Error Handling


### In App Errors

Errors are handled by using the trycatch method in javascript as well as conditionally checking values for availability before usage.

[Error Boundary Example Code](../src/hooks/useLogin.ts)

### Error Tracking

You should track any errors that occur in production. Although it's possible to implement your own solution, it is a better idea to use tools like [Sentry](https://sentry.io/). It will report any issue that breaks the app. You will also be able to see on which platform, browser, etc. did it occur. Make sure to upload source maps to sentry to see where in your source code did the error happen.
