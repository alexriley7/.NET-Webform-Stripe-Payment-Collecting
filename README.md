# The following is an Accept a payment

In This example it shows how to accept a payment with Stripe Elements using ASP.NET Webforms.

1 Update Global.asax.cs with your Secret API key

2 Update Default.aspx with your Publishable API key

3 Start the Stripe listner for Stripe CLI with:

```
stripe listen --forward-to http://localhost:8080/Webhooks.ashx -l

