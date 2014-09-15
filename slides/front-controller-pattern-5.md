###  Front Controller Pattern

7. The Action determines which View to direct the Client to based on criteria such as:
  * Success - May redirect to acknowledgement page, or list view, other indication of success.
  * Failure - Return 404, if attempt to locate information failed.
  * Failure - Return 401, Unauthorized if authenticated user does not have permission to perform an operation.
  * Failure - Input does not validate. Return input form.
8. The Action passes the generated View back to the Handler, giving the Handler an opportunity to decorated error conditions with and apology page before returning an Http Response back to the Client.