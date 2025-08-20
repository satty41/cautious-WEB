
UDID Documentation Assistance – Website

How to use
----------
1) Open google-apps-script/apps-script.gs in Google Apps Script, deploy as a Web App, and copy the deployment URL.
2) Open js/form.js and replace GOOGLE_SCRIPT_URL with your web app URL.
3) Open payment.html -> integration is simulated. To go live, integrate a real gateway (see suggestions below).
4) Replace assets/hero-wheelchair-placeholder.jpg with your AI-generated wheelchair hero image.
5) Host these files on any static hosting (Netlify, Vercel, GitHub Pages, etc.).

Payment Gateway Suggestions (India-friendly, no setup fee)
----------------------------------------------------------
• Razorpay Payment Links or Checkout (popular, quick integration)
• Stripe Payment Links or Checkout (supports India; simple client+server setup)
• PhonePe or Paytm Payment Links (shareable links; minimal dev)
• Cashfree Payment Links

Production Notes
----------------
• Ensure your Apps Script allows cross-origin requests for your domain.
• Consider adding server-side verification for real payments (webhooks).
• Update brand name, logo, and contact info in the header/footer.
