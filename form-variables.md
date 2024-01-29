# Form Variables

Within your PHP script, you can access each form field as a PHP variable whose name relates to the names of the form field.

`$_POST` is an array containin data submitted via an HTTP POST request; that is, the form method was set to POST.

There are three of these arrays that may contain form data: $_POST, $_GET, and $_REQUEST.

Taking data directly from the user and outputting it to the browser like this is an extremely risky practice from a security perspective. You should filter input data.

For now, it's enough to know that you should echo out user data to the browser after passing it through function called `htmlspecialchars()`
