Evony RSS Corner — Netlify Forms + PayPal Sandbox
=================================================
- PayPal SANDBOX only (client-id=sb). Switch to LIVE later by replacing the script tag.
- After approval:
  1) Hidden Netlify Form "consent" captures all order data.
  2) Minimal order info saved in sessionStorage.
  3) Redirect to /success.html (or /spanish/success.html).

See submissions: Netlify → Forms → consent → Submissions (export CSV, email notifications).

To go LIVE later:
<!-- SANDBOX -->
<script src="https://www.paypal.com/sdk/js?client-id=sb&currency=USD"></script>
<!-- LIVE -->
<script src="https://www.paypal.com/sdk/js?client-id=YOUR_LIVE_CLIENT_ID&currency=USD"></script>
