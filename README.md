# Mocktail — Alcohol-Free Cocktail Recipes

Welcome to the official support and documentation page for **Mocktail**.

## 🎧 App Support

If you need any help with the app, found a bug, or have a feature request, please feel free to reach out to us. We are always happy to help!

📧 **Contact Email:** mocktailhelp@gmail.com

---

## 🔒 Privacy Policy

**Last Updated:** August 17, 2026

### 1. Summary

Mocktail's recipes, favorites, notes, and "My Bar" features run entirely on your device; if you choose, that data syncs through your own iCloud account. No advertising, analytics, or user-tracking tools are used.

Only two features connect to a server: account sign-in and the AI Assistant. Those are what this policy is really about — please read sections 3 and 4.

### 2. Data That Stays on Your Device

The following is stored on your device and is never sent to our servers:

- Favorite mocktails list
- Personal notes you add to recipes
- "My Bar" (ingredients and equipment you have at home) selections
- App preferences (language, measurement unit, appearance, notification settings)
- Shaker trainer scores and party plan history
- Onboarding completion status

When iCloud sync is enabled, this data is synchronized across your own devices through Apple's iCloud infrastructure. It is held in your private iCloud storage, is subject to Apple's privacy policy, and is not accessible to us. You can turn sync off at any time from **More > iCloud**.

### 3. Account Information

Using the AI Assistant requires signing in with Apple or Google. When you sign in, the following information from your provider is stored on our server (Google Firebase):

- Your email address
- Your name (if the provider shares it)
- Your Firebase user ID (uid)
- Which provider you used and the day you were last active
- Your subscription status and purchased message balance

If you use **"Hide My Email"** with Apple sign-in, we receive Apple's relay address rather than your real one.

You can use the app without signing in; in that case an anonymous session is created in the background, producing only a technical identifier with no personal information. The AI Assistant is not available in an anonymous session.

### 4. AI Assistant and Third-Party Models

Messages you write to the assistant are sent to our server and from there to Google's **Gemini** model to generate a reply. If Gemini is busy, the same request falls back to **Groq**. The name of the recipe you are viewing may be attached as context.

Our server does **not** store the text of your messages. Our technical logs contain only your user ID, which provider answered, and the number of words (tokens) processed — never the content.

**Important:** We currently use Gemini's free usage tier. On that tier, Google may use submitted content to improve its products and train its models. Requests that fall back to Groq are subject to that provider's own terms. Both providers operate servers outside Europe (primarily the United States), so your messages are transferred internationally.

For that reason, **do not write identity details, contact information, financial information, or health information you would rather not share**. The assistant is not a health advisor; consult your doctor about pregnancy, medication, allergies, or chronic conditions.

Your email address, name, and user ID are not sent to these providers — only the message text.

### 5. Usage Limits and Abuse Prevention

To distribute assistant capacity fairly and block automated or fraudulent requests, we keep:

- Your daily and per-minute message counters. These counters are tied to an irreversible cryptographic digest (HMAC) of your email address; your address itself does not appear in that record. The record is deleted automatically after 60 days.
- Purchase receipts, to prevent the same purchase being credited twice. Deleted automatically after 90 days.
- An Apple App Attest check (Firebase App Check) verifying the request genuinely comes from the Mocktail app. This check does not reveal your device's identity to us.

Accounts that abuse the service may have their access blocked.

### 6. Purchases and Subscriptions (Mocktail+)

Payments are processed through the Apple App Store. Mocktail has no access to your credit card or payment details; those are handled solely by Apple and are subject to Apple's privacy policy.

We use **RevenueCat, Inc.** to track subscription and message pack status. Purchase information from Apple and your Firebase user ID are shared with RevenueCat. Your subscription status and remaining message balance are stored on our server against your account — this is what keeps your balance from disappearing when you change devices.

### 7. Notifications

Cocktail-of-the-day, new recipe, and tip notifications are prepared entirely on your device; their content is never sent to any server. You can disable notifications at any time from **More > Notifications**.

### 8. Deleting Your Account and Data

You can permanently delete your account with **"Delete Account"** in the Account Settings screen. Deletion removes your email address, your name, and every record tied to your account (including subscription status and message balance) from the server, along with your sign-in record. This cannot be undone, and any purchased message balance is not refunded.

Technical records that contain no personal data (usage counters tied to the cryptographic digest, and purchase receipts) are kept a little longer to prevent abuse, and are deleted automatically within the periods stated above.

Data on your device and in iCloud remains under your control; removing the app deletes the local data.

### 9. Data Security and Location

Account and usage data is hosted on Google Firebase infrastructure in Europe (Firestore: `eur3`, server functions: `europe-west1`). All connections are encrypted. The database is closed to direct access from the app; only verified server-side operations can reach these records.

As stated in section 4, only the text of assistant messages is transferred to model providers abroad.

### 10. Children's Privacy

Mocktail does not knowingly collect personal data from children under the age of 13. The app's content is intended for a general audience and contains no alcohol.

### 11. Your Rights

Under GDPR and applicable data protection law, you have the right to access your data, request its correction or deletion, object to its processing, and request a copy of it. You can exercise the deletion right instantly from within the app (section 8); for other requests, write to us at the address below.

### 12. Changes

This privacy policy may be updated from time to time. Significant changes will be communicated through app updates, and the "Last Updated" date on this page will be refreshed accordingly.

### 13. Contact

For questions or requests about this privacy policy, please contact us at:

📧 **mocktailhelp@gmail.com**

---

## 📄 Terms of Use (EULA)

**Last Updated:** August 17, 2026

### 1. Service Description

Mocktail is a mobile application designed to help users discover non-alcoholic cocktail (mocktail) recipes, save favorites and personal notes, see what recipes they can make with the ingredients they have on hand, access barista tips, and chat with an AI-powered assistant.

### 2. Health and Allergy Disclaimer

Mocktail does not provide medical advice, diagnose any health condition, or recommend diets or nutritional plans. The app is solely a recipe discovery and tracking tool.

The recipes, nutritional/calorie information, and assistant replies provided in the app are for entertainment and inspirational purposes only. They do not constitute medical, nutritional, or dietary advice. If you have any allergies (food allergies, lactose intolerance, fructose intolerance, etc.), chronic conditions (diabetes, hypertension, heart conditions, etc.), are pregnant or breastfeeding, are taking any medication that may interact with certain ingredients, or have any dietary restrictions, **review all ingredients yourself before preparation and consult your doctor or a qualified professional when needed**.

**Mocktail cannot be held responsible in any way for allergic reactions, digestive issues, medication interactions, or any other negative health outcomes that may arise from preparing or consuming the recipes shown in the app.**

### 3. Accounts and Sign-In

Recipes, favorites, notes, and "My Bar" can be used without an account. The **AI Assistant requires signing in with Apple or Google**.

You are responsible for the security of your account and of the Apple/Google account you sign in with. You can permanently delete your account at any time from the Account Settings screen; deletion cannot be undone, and any purchased message balance is not refunded.

Deleting your account does not affect local data on your device or in iCloud (favorites, notes); that data remains under your control.

### 4. Use of the AI Assistant

The assistant returns replies generated by an artificial intelligence language model. **AI replies may be inaccurate, incomplete, or misleading; the correctness of the information provided is not guaranteed.** Do not rely on the assistant for important decisions.

Messages you write to the assistant are forwarded to third-party model providers (Google Gemini, with Groq as a fallback) to generate the reply. See section 4 of the Privacy Policy for details. Do not write identity details, contact information, financial information, or health information you would rather not share.

Use of the assistant is subject to fair-use limits: signed-in users have daily and per-minute message limits, and Mocktail+ subscribers have a higher daily limit. These limits may change without prior notice.

Because the assistant depends on third-party providers, the service may be interrupted, temporarily slowed, or discontinued. Uninterrupted access is not guaranteed.

### 5. Subscriptions and Payments (Mocktail+)

Should you upgrade to a Mocktail+ subscription, your subscription will automatically renew based on your chosen plan (monthly or yearly).

- You can cancel your subscription at any time from your device's App Store settings.
- Cancellations will take effect at the end of the current subscription period.
- Payment will be charged to your personal iTunes (Apple ID) account upon confirmation of purchase.
- Any unused portion of a free trial period will be forfeited upon purchasing a subscription.
- Subscriptions automatically renew unless canceled at least 24 hours before the end of the current period.
- Use "Restore Purchases" to reactivate an existing subscription tied to your Apple ID on a new device.
- Prices may vary based on taxes and local currency; the price shown in the app is current.

### 6. Message Packs

Message packs, which you can use once your daily assistant allowance is spent, are **one-time (consumable) purchases, not subscriptions**; they do not renew automatically.

- Purchased messages are credited to your account and are available on every device you sign in to.
- They are consumed only after your free daily allowance runs out.
- The per-minute message limit cannot be exceeded using a message pack; that limit exists to prevent abuse, not to control cost.
- Messages from a purchase refunded through Apple are removed from your account balance.
- Deleting your account removes any unused messages, and they are not refunded.

### 7. Notification Disclaimer

Mocktail does not guarantee that reminder and cocktail-of-the-day notifications will be delivered on time. Device settings, battery status, network connectivity, or system updates may affect notification delivery.

### 8. Intellectual Property

The data interface, logos, software algorithms, designs, icons, images, text, and all visual content within the app are protected by copyright.

### 9. Prohibited Conduct

Unauthorized copying of the app's source code, reverse engineering, or exactly duplicating the design to convert it into a commercial asset on different platforms is strictly prohibited.

The following are also prohibited:

- Sending requests to the assistant infrastructure from outside the app, with automated tools, or via scripts
- Creating multiple accounts, or using any other method, to circumvent usage limits
- Attempting to turn the assistant into a general-purpose AI service beyond its intended scope
- Using the assistant to produce unlawful, harmful, or harassing content, or content that infringes the rights of others

Accounts violating these rules may have their access blocked without notice, with no refund for unused allowances. Legal action will be taken upon detection of intellectual property violations.

### 10. Limitation of Liability

The app is provided "as is." The recipe and content information within Mocktail is based solely on the editorial data the user accesses through the app and on replies generated by artificial intelligence. The app does not provide medical or health advisory services. The ultimate responsibility for actions taken and recipes prepared based on the provided information lies entirely with the user.

**Mocktail cannot be held responsible for any consequences — including but not limited to allergic reactions, digestive problems, medication interactions, blood sugar fluctuations, the content of AI-generated replies, service interruptions, or any other negative outcome — arising from preparing, consuming, or otherwise using the recipes and information provided in the app.**

### 11. Changes

These terms may be updated from time to time. Significant changes will be communicated through app updates, and the "Last Updated" date on this page will be refreshed accordingly. Continuing to use the app after an update means you accept the revised terms.

### 12. Contact

For questions about these terms of use, please contact us at:

📧 **mocktailhelp@gmail.com**

---

## Contact Support

📧 **mocktailhelp@gmail.com**
